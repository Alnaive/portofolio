<template>
    <section class="body-font text-black dark:text-white h-auto" >
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
                <p class="leading-relaxed text-base">Aplikasi yang saya buat untuk skripsi, aplikasi ini berfungsi untuk membuat informasi build character dari user dengan input manual untuk di store ke database lalu data
                    tersebut digunakan untuk membuat referensi statistik build kepada user.
                </p>
                </div>
            </div>
            <div class="xl:w-1/4 md:w-1/2 p-4">
                <a href="https://genshin-tech.com">
                <div class="bg-white shadow-md dark:bg-gray-500 p-6 rounded-lg">
                <h3 class="tracking-widest text-xs font-medium title-font">Laravel Rest API, Vue.js</h3>
                <h2 class="text-lg  font-medium title-font mb-4">Genshin-tech</h2>
                <p class="leading-relaxed text-base">Upgrade dari genshin app, menggunakan API Enka.Network untuk get data secara otomatis dan menggunakan Rest API dari laravel sebagai backend dan vue.js sebagai frontend</p>
                </div>
            </a>
            </div>
            </div>
        </div>
        <section class="container mx-auto px-5">
            <h1 class="text-lg font-medium mb-2">Preview hasil dari aplikasi Genshin</h1>
            <div class="flex flex-col md:flex-row justify-center items-center space-y-4 md:space-x-4">
                <div class="mb-5">
                    <img class="object-contain" src="https://media.discordapp.net/attachments/873515567930290237/1051582630337986591/PortraitYoimiya.png?width=837&height=702" alt="" srcset="">
                </div>  
                <div class="mb-5">
                    <img class="object-contain" src="https://media.discordapp.net/attachments/873515567930290237/1051582630652555414/BuildYoimiya.png" alt="" srcset="">
                </div>
            </div>
        </section>
           
    </section>
</template>
<script setup>
import { Icon } from '@iconify/vue';
</script>