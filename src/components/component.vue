<script setup>

</script>

<template>
 <nav class="flex justify-between py-10 px-20 sm:flex sm:justify-between lg:flex lg:justify-between xl:flex xl:justify-between">
        <div class="flex gap-5">
            <img src="../assets/image/Group 8.png" alt="">
            <h1 class="pt-4 font-bold">AeroVision</h1>
        </div>
        <div class="flex justify-between gap-20">
            <div class="hidden sm:hidden md:hidden lg:block xl:block">
                <ul class="flex justify-between gap-10 pt-4 font-bold">
                    <li>Home</li>
                    <li>About Me</li>
                    <li>Services</li>
                    <li>Blog</li>
                    <li>Blog</li>
                </ul>
            </div>
            <div>
                <button class="hidden sm:hidden md:block lg:block xl:block   h-12 bg-blue-600 text-white font-bold  rounded-full w-32">
                    Let’s chat
                </button>
                <button class=" lg:hidden xl:hidden md:hidden">
                    <img src="../assets/image/menu-02.png" alt="">
                </button>
            </div>
        </div>
    </nav>
</template>
