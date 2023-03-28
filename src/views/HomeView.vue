<template>
  <Header />
  <div class="container-fluid">
    <div class="d-flex w-100 align-items-center justify-content-center trade flex-wrap mb-5">
      <button class="btn active">Exchange</button><button class="btn">Liquidity</button>
    </div>
    <div class="row justify-content-center align-items-center">
      <div class="col-md-6">
        <div width="100%" class="sc-jRQBWg sc-gKclnd kJWihe kxYByf">
          <div class="sc-jRQBWg sc-gKclnd sc-bvFjSx gREMsN hrZfTH jtGvmi">
            <div class="sc-jRQBWg sc-ekrjqK gREMsN fGxmCX">
              <div class="sc-hGPBjI BcFEZ sc-cQMzAB gEsWlb">
                <div class="sc-jRQBWg sc-dlVxhl gREMsN ksbuMd">
                  <div class="sc-jRQBWg sc-gKclnd sc-bttaWv gREMsN hrZfTH dUHqwx">
                    <div width="100%" class="sc-jRQBWg sc-gKclnd kHGfVa jeEyoz">
                      <div width="100%" class="sc-jRQBWg sc-gKclnd jPEaAA kNfYKT">
                        <div font-size="17px" color="text" class="sc-gsDKAQ bcHSms">Swap</div>
                      </div>
                      <div class="sc-jRQBWg sc-gKclnd gREMsN hrZfTH"><button
                          class="sc-hKwDye klDcJQ sc-eCImPb sc-kNzDjo kUClXB ifrTXD" scale="sm"><svg viewBox="0 0 18 18"
                            width="18px" color="textSubtle" xmlns="http://www.w3.org/2000/svg" class="sc-bdvvtL hbIeON">
                            <path
                              d="m4.4222 0c-2.5517 0-4.4222 2.4246-4.4222 5.1795v7.641c0 2.7548 1.8705 5.1795 4.4222 5.1795h9.1556c2.5517 0 4.4222-2.4246 4.4222-5.1795v-7.641c0-2.7548-1.8705-5.1795-4.4222-5.1795zm0 2.0037h9.1556c1.2382 0 2.4185 1.3013 2.4185 3.1758v7.641c0 1.8744-1.1804 3.1758-2.4185 3.1758h-9.1556c-1.2382 0-2.4185-1.3013-2.4185-3.1758v-7.641c0-1.8744 1.1804-3.1758 2.4185-3.1758zm9.9676 3.1366a1.0018 1.0018 0 0 0-0.69855 0.31699l-3.6023 3.845-1.988-2.0252a1.0019 1.0019 0 0 0-1.4304 0l-3.8078 3.8802a1.0018 1.0018 0 0 0 0.013697 1.4167 1.0018 1.0018 0 0 0 1.4167-0.0137l3.0936-3.1523 2.0037 2.0428a1.0019 1.0019 0 0 0 1.446-0.01566l4.3166-4.6081a1.0018 1.0018 0 0 0-0.045-1.4167 1.0018 1.0018 0 0 0-0.71812-0.27003z">
                            </path>
                          </svg></button></div>
                    </div>
                  </div>
                  <div id="swap-page" class="sc-jRQBWg sc-gKclnd sc-emDsmM gREMsN hrZfTH cvLLnE"
                    style="min-height: 200px;">
                    <div class="sc-cVAmsi ljwusp">
                      <div id="swap-currency-input" class="sc-jRQBWg gREMsN">
                        <div class="sc-gJbFto jJavKJ">
                          <div class="sc-eJRTFu newQG">
                            <div class="sc-kBzgEd WDIeo"><input class="sc-eBTqsU fCkAar token-amount-input"
                                inputmode="decimal" title="Token Amount" autocomplete="off" autocorrect="off" type="text"
                                pattern="^[0-9]*[.,]?[0-9]*$" placeholder="0.0" minlength="1" maxlength="79"
                                spellcheck="false" value=""><button
                                class="sc-hKwDye klDcJQ sc-ezHhwS dGpTDs open-currency-select-button" scale="sm"><img
                                  src="https://ipfs.io/ipfs/QmYqkn8pJUaV9KcEPYEvRPwgbfeozLEvcQ9aEwKNRUL3cR"
                                  class="sc-ksHpcM fkSloz" style="margin-right: 8px;">
                                <div font-size="18px" id="pair" color="text" class="sc-gsDKAQ bOhvRw">PLS</div><svg
                                  viewBox="0 0 24 24" color="text" width="20px" xmlns="http://www.w3.org/2000/svg"
                                  class="sc-bdvvtL cdECTp">
                                  <path
                                    d="M8.11997 9.29006L12 13.1701L15.88 9.29006C16.27 8.90006 16.9 8.90006 17.29 9.29006C17.68 9.68006 17.68 10.3101 17.29 10.7001L12.7 15.2901C12.31 15.6801 11.68 15.6801 11.29 15.2901L6.69997 10.7001C6.30997 10.3101 6.30997 9.68006 6.69997 9.29006C7.08997 8.91006 7.72997 8.90006 8.11997 9.29006Z">
                                  </path>
                                </svg>
                              </button></div>
                            <div class="sc-iseIHH bedyZz">
                              <div color="text" class="sc-gsDKAQ bzOYlz"></div>
                              <div class="sc-jRQBWg sc-gKclnd iauAaS ePttXJ"></div>
                            </div>
                          </div>
                        </div>
                      </div>
                      <div class="sc-jRQBWg sc-jlsrNB sc-hJZKUC laYFtL ieLkdF hDGJgS">
                        <button class="sc-hKwDye cIeiGV sc-eCImPb sc-hWBuOZ kUClXB iBaLQD" scale="sm">
                          <i class="bi bi-arrow-down sc-bdvvtL fKLGoV "></i>
                          <i class="bi bi-arrow-down-up sc-bdvvtL fKLGoV icon-up-down"></i>
                        </button>
                      </div>
                      <div id="swap-currency-output" class="sc-jRQBWg gREMsN">
                        <div class="sc-gJbFto jJavKJ">
                          <div class="sc-eJRTFu newQG">
                            <div class="sc-kBzgEd WDIeo"><input class="sc-eBTqsU fCkAar token-amount-input"
                                inputmode="decimal" title="Token Amount" autocomplete="off" autocorrect="off" type="text"
                                pattern="^[0-9]*[.,]?[0-9]*$" placeholder="0.0" minlength="1" maxlength="79"
                                spellcheck="false" value="">
                                <button
                                class="sc-hKwDye klDcJQ sc-ezHhwS dGpTDs open-currency-select-button" scale="sm">
                                <svg
                                  viewBox="0 0 24 24" class="sc-bdvvtL cdECTp sc-kHxTfl ioWdKk" color="text" width="20px"
                                  xmlns="http://www.w3.org/2000/svg">
                                  <path
                                    d="M12 2C6.48 2 2 6.48 2 12C2 17.52 6.48 22 12 22C17.52 22 22 17.52 22 12C22 6.48 17.52 2 12 2ZM12 20C7.59 20 4 16.41 4 12C4 7.59 7.59 4 12 4C16.41 4 20 7.59 20 12C20 16.41 16.41 20 12 20ZM11 16H13V18H11V16ZM12.61 6.04C10.55 5.74 8.73 7.01 8.18 8.83C8 9.41 8.44 10 9.05 10H9.25C9.66 10 9.99 9.71 10.13 9.33C10.45 8.44 11.4 7.83 12.43 8.05C13.38 8.25 14.08 9.18 14 10.15C13.9 11.49 12.38 11.78 11.55 13.03C11.55 13.04 11.54 13.04 11.54 13.05C11.53 13.07 11.52 13.08 11.51 13.1C11.42 13.25 11.33 13.42 11.26 13.6C11.25 13.63 11.23 13.65 11.22 13.68C11.21 13.7 11.21 13.72 11.2 13.75C11.08 14.09 11 14.5 11 15H13C13 14.58 13.11 14.23 13.28 13.93C13.3 13.9 13.31 13.87 13.33 13.84C13.41 13.7 13.51 13.57 13.61 13.45C13.62 13.44 13.63 13.42 13.64 13.41C13.74 13.29 13.85 13.18 13.97 13.07C14.93 12.16 16.23 11.42 15.96 9.51C15.72 7.77 14.35 6.3 12.61 6.04Z">
                                  </path>
                                </svg>
                                <div font-size="18px" id="pair" color="text" class="sc-gsDKAQ bOhvRw">PLSX</div><svg
                                  viewBox="0 0 24 24" color="text" width="20px" xmlns="http://www.w3.org/2000/svg"
                                  class="sc-bdvvtL cdECTp">
                                  <path
                                    d="M8.11997 9.29006L12 13.1701L15.88 9.29006C16.27 8.90006 16.9 8.90006 17.29 9.29006C17.68 9.68006 17.68 10.3101 17.29 10.7001L12.7 15.2901C12.31 15.6801 11.68 15.6801 11.29 15.2901L6.69997 10.7001C6.30997 10.3101 6.30997 9.68006 6.69997 9.29006C7.08997 8.91006 7.72997 8.90006 8.11997 9.29006Z">
                                  </path>
                                </svg>
                              </button>
                            </div>
                            <div class="sc-iseIHH bedyZz">
                              <div color="text" class="sc-gsDKAQ bzOYlz"></div>
                              <div class="sc-jRQBWg sc-gKclnd iauAaS ePttXJ"></div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="sc-jRQBWg camDuN">
                      <button class="sc-hKwDye kLoNCk" width="100%" scale="md" data-bs-toggle="modal"
                        data-bs-target="#connectModal">Connect
                        Wallet</button>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="modal fade" id="connectModal" tabindex="-1" aria-labelledby="connectModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-sm ">
      <div class="modal-content etAOfZ">
        <div class="modal-header gpgsbt">
          <h1 class="modal-title fs-6" id="connectModalLabel">Connect Wallet</h1>
          <button type="button" class="bg-transparent fs-6 border-0 eSnqot" data-bs-dismiss="modal" aria-label="Close">
            <i class="bi bi-x fs-5 fw-4"></i>
          </button>
        </div>
        <div class="modal-body">
          <div width="320px,,340px" class="sc-jRQBWg sc-gKclnd sc-fXEqDS buOPej hrZfTH hmUoNK">
            <div class="sc-jRQBWg sc-cvZCdy pjwpK bGfhDS">
              <div class="sc-jRQBWg sc-kDTinF gREMsN bxujvL">
                <div class="sc-jRQBWg gREMsN"><button class="sc-hKwDye fWWhTP sc-kmQMED ljDPti"
                    id="wallet-connect-walletconnect" width="100%" scale="md"><svg viewBox="0 0 40 40" width="40px"
                      color="text" xmlns="http://www.w3.org/2000/svg" class="sc-bdvvtL DjEJI">
                      <path
                        d="M8.68096 12.4756C14.9323 6.39698 25.0677 6.39698 31.3191 12.4756L32.0714 13.2071C32.384 13.511 32.384 14.0038 32.0714 14.3077L29.4978 16.8103C29.3415 16.9622 29.0881 16.9622 28.9318 16.8103L27.8965 15.8036C23.5354 11.563 16.4647 11.563 12.1036 15.8036L10.9948 16.8817C10.8385 17.0336 10.5851 17.0336 10.4288 16.8817L7.85517 14.3791C7.54261 14.0752 7.54261 13.5824 7.85517 13.2785L8.68096 12.4756ZM36.6417 17.6511L38.9322 19.8783C39.2448 20.1823 39.2448 20.675 38.9322 20.979L28.6039 31.022C28.2913 31.3259 27.7846 31.3259 27.472 31.022C27.472 31.022 27.472 31.022 27.472 31.022L20.1416 23.8942C20.0634 23.8182 19.9367 23.8182 19.8586 23.8942C19.8586 23.8942 19.8586 23.8942 19.8586 23.8942L12.5283 31.022C12.2157 31.3259 11.709 31.3259 11.3964 31.022C11.3964 31.022 11.3964 31.022 11.3964 31.022L1.06775 20.9788C0.755186 20.6749 0.755186 20.1821 1.06775 19.8782L3.35833 17.6509C3.6709 17.347 4.17767 17.347 4.49024 17.6509L11.8208 24.7789C11.8989 24.8549 12.0256 24.8549 12.1038 24.7789C12.1038 24.7789 12.1038 24.7789 12.1038 24.7789L19.4339 17.6509C19.7465 17.347 20.2533 17.347 20.5658 17.6509C20.5658 17.6509 20.5658 17.6509 20.5658 17.6509L27.8964 24.7789C27.9745 24.8549 28.1012 24.8549 28.1794 24.7789L35.5098 17.6511C35.8223 17.3471 36.3291 17.3471 36.6417 17.6511Z"
                        fill="#3389FB"></path>
                    </svg>
                    <div font-size="14px" color="text" class="sc-gsDKAQ eNNCPm">WalletConnect</div>
                  </button></div>
                <div class="sc-jRQBWg gREMsN"><button class="sc-hKwDye fWWhTP sc-kmQMED ljDPti"
                    id="wallet-connect-metamask" width="100%" scale="md"><svg viewBox="0 0 40 40" width="40px"
                      color="text" xmlns="http://www.w3.org/2000/svg" class="sc-bdvvtL DjEJI">
                      <path d="M36.0112 3.33337L22.1207 13.6277L24.7012 7.56091L36.0112 3.33337Z" fill="#E17726"></path>
                      <path d="M4.00261 3.33337L17.7558 13.7238L15.2989 7.56091L4.00261 3.33337Z" fill="#E27625"></path>
                      <path d="M31.0149 27.2023L27.3227 32.8573L35.2287 35.0397L37.4797 27.3258L31.0149 27.2023Z"
                        fill="#E27625"></path>
                      <path d="M2.53386 27.3258L4.77116 35.0397L12.6772 32.8573L8.9987 27.2023L2.53386 27.3258Z"
                        fill="#E27625"></path>
                      <path d="M12.2518 17.6496L10.0419 20.9712L17.8793 21.3281L17.6048 12.8867L12.2518 17.6496Z"
                        fill="#E27625"></path>
                      <path d="M27.762 17.6494L22.3129 12.7905L22.1207 21.3279L29.9581 20.9711L27.762 17.6494Z"
                        fill="#E27625"></path>
                      <path d="M12.6772 32.8574L17.3989 30.5652L13.336 27.3809L12.6772 32.8574Z" fill="#E27625"></path>
                      <path d="M22.6009 30.5652L27.3226 32.8574L26.6637 27.3809L22.6009 30.5652Z" fill="#E27625"></path>
                      <path d="M27.3226 32.8575L22.6009 30.5653L22.9715 33.6399L22.9303 34.9301L27.3226 32.8575Z"
                        fill="#D5BFB2"></path>
                      <path d="M12.6772 32.8575L17.0694 34.9301L17.042 33.6399L17.3989 30.5653L12.6772 32.8575Z"
                        fill="#D5BFB2"></path>
                      <path d="M17.1518 25.3495L13.2262 24.1965L15.9988 22.92L17.1518 25.3495Z" fill="#233447"></path>
                      <path d="M22.848 25.3495L24.001 22.92L26.801 24.1965L22.848 25.3495Z" fill="#233447"></path>
                      <path d="M12.6773 32.8573L13.3635 27.2023L8.99876 27.3258L12.6773 32.8573Z" fill="#CC6228"></path>
                      <path d="M26.6364 27.2023L27.3227 32.8573L31.0149 27.3258L26.6364 27.2023Z" fill="#CC6228"></path>
                      <path
                        d="M29.9581 20.9709L22.1207 21.3278L22.8482 25.3495L24.0011 22.92L26.8012 24.1965L29.9581 20.9709Z"
                        fill="#CC6228"></path>
                      <path
                        d="M13.2263 24.1965L15.9989 22.92L17.1519 25.3495L17.8793 21.3278L10.0419 20.9709L13.2263 24.1965Z"
                        fill="#CC6228"></path>
                      <path d="M10.0419 20.9709L13.3361 27.3809L13.2263 24.1965L10.0419 20.9709Z" fill="#E27525"></path>
                      <path d="M26.8011 24.1965L26.6638 27.3809L29.958 20.9709L26.8011 24.1965Z" fill="#E27525"></path>
                      <path d="M17.8793 21.3278L17.1519 25.3494L18.0715 30.0985L18.2637 23.8396L17.8793 21.3278Z"
                        fill="#E27525"></path>
                      <path d="M22.1205 21.3278L21.7499 23.8258L21.9283 30.0985L22.848 25.3494L22.1205 21.3278Z"
                        fill="#E27525"></path>
                      <path
                        d="M22.848 25.3496L21.9284 30.0987L22.601 30.5654L26.6638 27.381L26.8011 24.1967L22.848 25.3496Z"
                        fill="#F5841F"></path>
                      <path
                        d="M13.2262 24.1967L13.336 27.381L17.3989 30.5654L18.0714 30.0987L17.1518 25.3496L13.2262 24.1967Z"
                        fill="#F5841F"></path>
                      <path
                        d="M22.9303 34.93L22.9715 33.6398L22.6284 33.3378H17.3714L17.042 33.6398L17.0694 34.93L12.6772 32.8574L14.2145 34.1202L17.3302 36.2751H22.6696L25.7853 34.1202L27.3226 32.8574L22.9303 34.93Z"
                        fill="#C0AC9D"></path>
                      <path
                        d="M22.601 30.5653L21.9284 30.0986H18.0715L17.3989 30.5653L17.0421 33.6399L17.3715 33.3379H22.6285L22.9716 33.6399L22.601 30.5653Z"
                        fill="#161616"></path>
                      <path
                        d="M36.5875 14.3003L37.7542 8.61779L36.011 3.33337L22.6009 13.2846L27.7618 17.6493L35.0365 19.7768L36.6424 17.8964L35.9424 17.3886L37.0679 16.3728L36.2169 15.7003L37.3287 14.863L36.5875 14.3003Z"
                        fill="#763E1A"></path>
                      <path
                        d="M2.24573 8.61779L3.42615 14.3003L2.67123 14.863L3.78302 15.7003L2.93202 16.3728L4.05753 17.3886L3.35752 17.8964L4.96343 19.7768L12.2518 17.6493L17.399 13.2846L4.00263 3.33337L2.24573 8.61779Z"
                        fill="#763E1A"></path>
                      <path
                        d="M35.0365 19.777L27.7619 17.6495L29.958 20.9712L26.6638 27.3811L31.0149 27.3262H37.4797L35.0365 19.777Z"
                        fill="#F5841F"></path>
                      <path
                        d="M12.2517 17.6495L4.96332 19.777L2.53386 27.3262H8.99869L13.336 27.3811L10.0419 20.9712L12.2517 17.6495Z"
                        fill="#F5841F"></path>
                      <path
                        d="M22.1205 21.3276L22.6009 13.2843L24.701 7.56067H15.2988L17.3988 13.2843L17.8792 21.3276L18.0577 23.8531L18.0714 30.0984H21.9283L21.9421 23.8531L22.1205 21.3276Z"
                        fill="#F5841F"></path>
                    </svg>
                    <div font-size="14px" color="text" class="sc-gsDKAQ eNNCPm">Metamask</div>
                  </button></div>
                <div class="sc-jRQBWg gREMsN"><button class="sc-hKwDye fWWhTP sc-kmQMED ljDPti"
                    id="wallet-connect-trust wallet" width="100%" scale="md"><svg viewBox="0 0 40 40" width="40px"
                      color="text" xmlns="http://www.w3.org/2000/svg" class="sc-bdvvtL DjEJI">
                      <path opacity="0.9"
                        d="M19.9959 4.8377L20.7771 3.82105C20.5523 3.64825 20.2766 3.55457 19.9931 3.55457C19.7095 3.55457 19.4339 3.64825 19.209 3.82105L19.9959 4.8377ZM33.425 8.7837H34.7059C34.7081 8.61378 34.6767 8.44509 34.6134 8.28737C34.5502 8.12965 34.4563 7.98603 34.3372 7.8648C34.2181 7.74358 34.0762 7.64714 33.9196 7.58107C33.763 7.515 33.5949 7.4806 33.425 7.47985V8.7837ZM19.9959 36.2161L19.2837 37.2845C19.4936 37.425 19.7405 37.5 19.9931 37.5C20.2457 37.5 20.4925 37.425 20.7024 37.2845L19.9959 36.2161ZM6.57841 8.7837V7.49709C6.40847 7.49783 6.24036 7.53223 6.0838 7.5983C5.92723 7.66437 5.7853 7.76081 5.66621 7.88204C5.54712 8.00326 5.45322 8.14688 5.38995 8.3046C5.32667 8.46232 5.29526 8.63101 5.29754 8.80093L6.57841 8.7837ZM19.2148 5.84861C25.0275 10.3518 31.6846 10.0646 33.4307 10.0646V7.49709C31.6214 7.49709 25.8259 7.72684 20.7943 3.82105L19.2148 5.84861ZM32.1499 8.76073C32.0522 14.7113 31.7995 18.91 31.317 22.0174C30.8345 25.1248 30.1682 26.9399 29.2894 28.238C28.4106 29.5361 27.2848 30.3804 25.6364 31.3626C23.9879 32.3448 21.8799 33.4361 19.2837 35.1535L20.7312 37.2845C23.1895 35.6475 25.2343 34.6021 26.9747 33.5625C28.7284 32.6075 30.2502 31.2779 31.4319 29.6682C32.5806 27.9451 33.3675 25.6475 33.873 22.408C34.3785 19.1685 34.6369 14.809 34.7346 8.80093L32.1499 8.76073ZM20.7312 35.1535C18.1522 33.4304 16.05 32.362 14.413 31.3684C12.776 30.3747 11.6502 29.582 10.7656 28.238C9.8811 26.8939 9.16312 25.1076 8.66915 22.0174C8.17519 18.9273 7.95692 14.7113 7.85928 8.76073L5.29754 8.80093C5.39518 14.809 5.6594 19.18 6.15911 22.408C6.65882 25.636 7.42275 27.9336 8.59448 29.6682C9.77051 31.2788 11.2888 32.6088 13.0402 33.5625C14.7633 34.6021 16.8254 35.6475 19.2837 37.2845L20.7312 35.1535ZM6.57841 10.0646C8.30155 10.0646 14.9644 10.3518 20.7771 5.84861L19.209 3.82105C14.166 7.72684 8.37048 7.49709 6.57266 7.49709L6.57841 10.0646Z"
                        fill="#3688EB"></path>
                    </svg>
                    <div font-size="14px" color="text" class="sc-gsDKAQ eNNCPm">Trust Wallet</div>
                  </button></div><button class="sc-hKwDye fWWhTP sc-kmQMED ljDPti" width="100%" scale="md"><svg
                    viewBox="0 0 24 24" width="40px" color="textSubtle" xmlns="http://www.w3.org/2000/svg"
                    class="sc-bdvvtL jXokrw">
                    <path
                      d="M6 10C4.9 10 4 10.9 4 12C4 13.1 4.9 14 6 14C7.1 14 8 13.1 8 12C8 10.9 7.1 10 6 10ZM18 10C16.9 10 16 10.9 16 12C16 13.1 16.9 14 18 14C19.1 14 20 13.1 20 12C20 10.9 19.1 10 18 10ZM12 10C10.9 10 10 10.9 10 12C10 13.1 10.9 14 12 14C13.1 14 14 13.1 14 12C14 10.9 13.1 10 12 10Z">
                    </path>
                  </svg>
                  <a href="/connect" font-size="14px" color="text" class="sc-gsDKAQ eNNCPm">More</a>
                </button>
              </div>
            </div>
            <div class="sc-jRQBWg NRzzn">
              <p color="textSubtle" class="sc-gsDKAQ ksjaXW">Haven’t got a crypto wallet yet?</p><a
                class="sc-hKwDye husKwV" href="https://docs.pulsex.com" width="100%" target="_blank"
                rel="noreferrer noopener" scale="md">Learn How to Connect</a>
            </div>
          </div>
        </div>

      </div>
    </div>
  </div>

  <Footer/>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "HomeView",
  components: {
    Header,
    Footer
  },
  data() {
    return {
      logo: "logo.726505f2.svg",
      showLogoTitle: true
    };
  },
  methods: {
    reroute(route) {
      location.pathname = route;
    }
  }
};
</script>

<style>
.fCkAar {
  color: rgb(242, 242, 242);
  width: 0px;
  position: relative;
  font-weight: 500;
  outline: none;
  border: none;
  flex: 1 1 auto;
  background-color: transparent !important;
  font-size: 24px !important;
  text-align: left;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  padding: 0px;
  appearance: textfield;
}
</style>