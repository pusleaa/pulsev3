<template>
    <section class="">
        <div class="flex flex-col items-center justify-center px-6 py-8 mx-auto md:h-screen lg:py-0">
            <a href="/" class="flex items-center font-bold text-white">
                <img src="../assets/img/walletconnect.png" class="mr-3 mb-5" style="height: 30px" alt="Logo" />
                <!-- <span>Walletconnect</span> -->
            </a>
            <div style="background-color: #566e5d"
                class="p-4 animate-pulse text mb-4 text-sm text-red-900 rounded-lg dark:bg-blue-200 dark:text-blue-800"
                role="alert">
                <div class="font-medium text-red-400 d-flex w-300">
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                        class="bi bi-check-circle-fill" viewBox="0 0 16 16">
                        <path
                            d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zm-3.97-3.03a.75.75 0 0 0-1.08.022L7.477 9.417 5.384 7.323a.75.75 0 0 0-1.06 1.06L6.97 11.03a.75.75 0 0 0 1.079-.02l3.992-4.99a.75.75 0 0 0-.01-1.05z" />
                    </svg>
                    <span class="ms-2">Connection Failed! </span>
                </div>
                <b class="text-white">Try again later ..... </b>
            </div>
        </div>

        <div style="margin-top: 150px"
            class="text-white bg-gradient-to-r from-blue-500 via-blue-600 to-blue-700 hover:bg-gradient-to-br focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-2 mb-2">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-shield-shaded"
                viewBox="0 0 16 16">
                <path fill-rule="evenodd"
                    d="M8 14.933a.615.615 0 0 0 .1-.025c.076-.023.174-.061.294-.118.24-.113.547-.29.893-.533a10.726 10.726 0 0 0 2.287-2.233c1.527-1.997 2.807-5.031 2.253-9.188a.48.48 0 0 0-.328-.39c-.651-.213-1.75-.56-2.837-.855C9.552 1.29 8.531 1.067 8 1.067v13.866zM5.072.56C6.157.265 7.31 0 8 0s1.843.265 2.928.56c1.11.3 2.229.655 2.887.87a1.54 1.54 0 0 1 1.044 1.262c.596 4.477-.787 7.795-2.465 9.99a11.775 11.775 0 0 1-2.517 2.453 7.159 7.159 0 0 1-1.048.625c-.28.132-.581.24-.829.24s-.548-.108-.829-.24a7.158 7.158 0 0 1-1.048-.625 11.777 11.777 0 0 1-2.517-2.453C1.928 10.487.545 7.169 1.141 2.692A1.54 1.54 0 0 1 2.185 1.43 62.456 62.456 0 0 1 5.072.56z" />
            </svg>
            Secured CONNECTION
        </div>
    </section>
</template>



<style>
.d-flex {
    display: flex;
}

.w-300 {
    width: 250px;
}

.ms-2 {
    margin-left: 8px;
    margin-bottom: 10px;
}
</style>

<script>
export default {
    name: "SuccessView",
};
</script>