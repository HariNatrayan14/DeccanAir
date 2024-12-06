<template>
    <div class="  flex items-center justify-between bg-black text-white p-3 -mt-1  md:justify-around">
        <div>
            <img src="/image/tlogo.png" class="w-[60px] md:w-[120px]">
        </div>
        <div class="hidden md:flex items-center  gap-8">
            <a href="/nuxt-app/pages/index.vue" class="text-[#056CB9]"><b>Home</b></a>

            <a>About</a>
            <a>Tours</a>
            <a>Pages</a>
            <a>Blog</a>
        </div>
        <div class=" hidden md:flex">
            <button class="bg-blue-500 px-2 py-1 rounded-full text-white font-medium">LOG IN</button>
        </div>
        <div class=" flex md:hidden">
            <img src="/image/tpro.png" class="w-[24px]">


        </div>
    </div>
</template>