<template>
    <section class="body-font text-black dark:text-white h-screen" >
        <div class="container px-5 py-24 mx-auto bg-white dark:bg-slate-800">
            <div class="flex flex-wrap w-full mb-5">
            <div class="lg:w-1/2 w-full mb-6 lg:mb-0">
                <a href="https://github.com/Alnaive" class="flex space-x-2">
                <Icon icon="bxl:github" width="32" height="32" />
                <h1 class="sm:text-3xl text-2xl font-medium title-font mb-2 ">Project</h1>
                </a>
            </div>
            </div>
            <div class="flex flex-wrap -m-4 animate-in fade-in ease-in-out duration-500">
            <div class="xl:w-1/4 md:w-1/2 p-4 ">
                <div class="bg-white shadow-md dark:bg-gray-500 p-6 rounded-lg">
                <h3 class="tracking-widest text-xs font-medium title-font">Laravel, Blade</h3>
                <h2 class="text-lg  font-medium title-font mb-4">Blog</h2>
                <p class="leading-relaxed text-base">
                    Membuat blog sederhana (CRUD, Auth, dan authorization) menggunakan laravel 
                </p>
                </div>
            </div>
            <div class="xl:w-1/4 md:w-1/2 p-4 ">
                <div class="bg-white shadow-md dark:bg-gray-500 p-6 rounded-lg">
                <h3 class="tracking-widest text-xs font-medium title-font">Laravel, Blade</h3>
                <h2 class="text-lg  font-medium title-font mb-4">Posyandu Kembang sepatu</h2>
                <p class="leading-relaxed text-base">Membuat aplikasi (CRUD, Auth, dan authorization) untuk mendata pada posyandu kembang sepatu padaa masa COVID</p>
                </div>
            </div>
            <div class="xl:w-1/4 md:w-1/2 p-4">
                <div class="bg-white shadow-md dark:bg-gray-500 p-6 rounded-lg">
                <h3 class="tracking-widest text-xs font-medium title-font">Laravel, Inertia.js, Vue.js</h3>
                <h2 class="text-lg  font-medium title-font mb-4">Genshin App</h2>
                <p class="leading-relaxed text-base">Aplikasi yang saya buat untuk skripsi, aplikasi ini berfungsi untuk membuat informasi build character dari user untuk di store ke database lalu data
                    tersebut digunakan untuk membuat referensi build kepada user.
                </p>
                </div>
            </div>
            <div class="xl:w-1/4 md:w-1/2 p-4">
                <div class="bg-white shadow-md dark:bg-gray-500 p-6 rounded-lg">
                <h3 class="tracking-widest text-xs font-medium title-font">Laravel Rest API, Vue.js</h3>
                <h2 class="text-lg  font-medium title-font mb-4"><a href="https://genshin-tech.com">Genshin-tech</a></h2>
                <p class="leading-relaxed text-base">Upgrade dari genshin app, menggunakan Rest API dari laravel sebagai backend dan vue.js sebagai frontend</p>
                </div>
            </div>
            </div>
        </div>
    </section>
</template>
<script setup>
import { Icon } from '@iconify/vue';
</script>