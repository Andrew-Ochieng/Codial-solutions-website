<template>
    <div id="contact" class="bg-gray-100 py-8">
        <!--reach-out-->
        <div class="md:m-12 m-6 md:flex justify-between">
            <div class="md:text-left text-center">
                <h1 class="md:text-5xl text-2xl font-semibold tracking-wide md:leading-tight text-sky-400">
                    Got a Project <br> Or Partnership <br> In Mind?
                </h1>
                <div class="md:mt-8 mt-4 flex justify-between">
                    <div class="md:mt-0 mt-4 text-gray-700 flex flex-col justify-center items-center">
                        <div class="p-4 bg-white rounded-lg flex items-center justify-center w-16 mb-3 shadow-lg">
                             <img class="md:w-8 w-6" src="../assets/images/call.png" alt="">
                        </div>
                        <div class="">
                            <h5 class="font-medium mb-2 text-gray-900">Phone:</h5>
                            <p class="md:text-base text-sm">0710815080</p>
                            <p class="md:text-base text-sm">0717195986</p>
                        </div>
                    </div>
                    <div class="md:mt-0 mt-4 text-gray-700 flex flex-col justify-center items-center">
                        <div class="p-4 bg-white rounded-lg flex items-center justify-center w-16 mb-3 shadow-lg">
                            <img class="md:w-8 w-6" src="../assets/images/email.png" alt="">
                        </div>
                        <div class="">
                            <h5 class="font-medium mb-2 text-gray-900">Email:</h5>
                            <p class="md:text-base text-sm">info@codialsolutions.com</p>
                            <p class="md:text-base text-sm">support@codial.com</p>
                        </div>
                    </div>

                </div>
            </div>

            <div class="md:mt-0 mt-8">
                <form action="" method="post">
                    <div class="my-4">
                        <input class="w-full bg-gray-100 focus-within:bg-gray-50 focus-within:rounded-lg pl-1 pr-4 py-3 border-b-2 border-sky-300 outline-none" type="text" id="full-name" placeholder="Full Name">
                    </div>
                    <div class="md:flex justify-between md:space-x-8">
                        <div class="my-4">
                            <input class="w-full bg-gray-100 focus-within:bg-gray-50 focus-within:rounded-lg pl-1 pr-4 py-3 border-b-2 border-sky-300 outline-none" type="email" id="email" placeholder="Email">
                        </div>
                        <div class="my-4">
                            <input class="w-full bg-gray-100 focus-within:bg-gray-50 focus-within:rounded-lg pl-1 pr-4 py-3 border-b-2 border-sky-300 outline-none" type="number" id="phone-number" placeholder="Phone Number">
                        </div>
                    </div>
                    <div class="my-4">
                        <input class="w-full bg-gray-100 focus-within:bg-gray-50 focus-within:rounded-lg pl-1 pr-4 py-3 border-b-2 border-sky-300 outline-none" type="text" id="project-details" placeholder="Project Details">
                    </div>

                    <button class="md:px-6 px-4 md:py-3 py-2 bg-gradient-to-r from-cyan-400 to-sky-500 hover:bg-sky-400 rounded-full font-medium text-gray-100 hover:text-gray-900 hover:scale-105 hover:translate-y-2 duration-500 shadow:lg hover:shadow-xl" type="submit">
                        Send Message
                    </button>
                </form>
            </div>

        </div>

    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>