<template>
    <div class="invisible md:visible flex container mx-auto items-center justify-center py-8">
      <button class="w-24 h-12 bg-indigo-500 rounded-lg " @click="exportImg()"><span class="flex items-center justify-center"><Icon icon="bxs:file-png" width="32" height="32" />PNG</span></button>
    </div>
    <section class="text-black dark:text-white body-font">
      <div id="exportPDF" class="container px-5 mx-auto flex flex-col bg-white dark:bg-slate-800">
        <div  class=" md:h-[1122.519685px] md:w-[793.7007874px] md:relative mx-auto rounded-lg flex mb-5">
          <div id="exportData" class=" bg-white dark:bg-slate-800 p-2 shadow-lg rounded-lg ">
            <div  class="flex flex-col  sm:flex-row mt-5 rounded-lg">
            <div class="sm:w-1/3  sm:pr-8 sm:py-8 md:w-72">
                <div class="text-center">
                    <div class="w-32 h-32 inline-flex items-center justify-center bg-gray-200 text-gray-400">
                    <img  class="object-contain " src="https://media.discordapp.net/attachments/873515567930290237/1041695411930398742/4_x_6_1985.jpg?width=467&height=701" alt="" srcset="">
                    </div>
                </div>
              <div class="flex flex-col ">
                <h2 class="font-medium title-font mt-4 text-lg text-center ">Muhammad Fery Perdana <br>Web Programmmer</h2>
                <div class="w-full ml-2 h-1 bg-indigo-500 rounded mt-2 mb-4"></div>
                <h1 class="flex mt-2 mb-5 shadow-lg rounded-lg dark:bg-indigo-500 p-2"><Icon icon="bxs:contact" width="32" height="32" /> <span class="ml-2 text-lg ">Kontak</span> </h1>
                <div class="flex space-y-2 ml-2 flex-col">
                    <div class="flex items-center space-x-2">
                        <Icon icon="bi:phone" width="32" />
                        <h1>081242397622</h1>
                    </div>
                    <div class="flex items-center space-x-2">
                        <Icon icon="ic:round-mail-outline" width="32" />
                        <h1>feryperdana@outlook.com</h1>
                    </div>
                    <div class="flex items-center space-x-2">
                        <Icon icon="bxl:github" width="32" height="32" />
                        <h1><a href="https://github.com/Alnaive">Alnaive</a></h1>
                    </div>
                    <div class="flex items-center space-x-2">
                        <Icon icon="mdi:web" width="32" height="32" />
                        <h1><a href="https://feryperdana-gusx.vercel.app">feryperdana-gusx.vercel.app</a></h1>
                    </div>
                    <div class="flex items-center space-x-2">
                        <Icon icon="mdi:linkedin" width="32" height="32"/>
                        <h1><a href="https://linkedin.com/in/fery-perdana">Fery Perdana</a></h1>
                    </div>
                </div>
                <h1 class="flex mt-5 shadow-lg rounded-lg dark:bg-indigo-500 p-2"><Icon icon="bi:database-gear" width="32" height="32" /> <span class="ml-2 text-lg ">Keahlian</span> </h1>
                <div class="flex space-y-2 ml-2 flex-col mt-5">
                    <div class="flex items-center space-x-2">
                        <Icon icon="logos:laravel" width="32" height="32" />
                        <h1>Laravel</h1>
                    </div>
                    <div class="flex items-center space-x-2">
                        <Icon icon="logos:mongodb" width="32" height="32" />
                        <h1>MongoDB</h1>
                    </div>
                    <div class="flex items-center space-x-2">
                        <Icon icon="logos:mysql" width="32" height="32" />
                        <h1>MySql</h1>
                    </div>
                    <div class="flex items-center space-x-2">
                        <Icon icon="logos:nodejs" width="32" height="32" />
                        <h1>Node.js</h1>
                    </div>
                    <div class="flex items-center space-x-2">
                        <Icon icon="logos:tailwindcss-icon" width="32" height="32" />
                        <h1>TailwindCss</h1>
                    </div>
                    <div class="flex items-center space-x-2">
                        <Icon icon="logos:vue" width="32" height="32" />
                        <h1>Vue.js</h1>
                    </div>
                </div>
              </div>
            </div>
            <div class="sm:w-2/3 sm:pl-8 sm:py-8 sm:border-l border-gray-200 sm:border-t-0 border-t mt-4 pt-4 sm:mt-0 text-center sm:text-left">
              <h1 class="text-title font-medium flex dark:bg-indigo-500 p-2 rounded-lg shadow-lg mb-5 md:mb-0"><Icon icon="la:school" width="32" height="32" /><span class="ml-2 text-lg ">Pendidikan</span></h1>
                <div class=" md:pr-10 md:py-6">
                    <div class="flex relative pb-5">
                    <div class="h-full w-10 absolute inset-0 flex items-center justify-center">
                        <div class="h-full w-1 bg-gray-200 pointer-events-none"></div>
                    </div>
                    <div class="flex-shrink-0 w-10 h-10 rounded-full bg-gray-300 dark:bg-indigo-500 inline-flex items-center justify-center  relative z-10">
                        <Icon icon="fa-solid:university" width="32" height="32"/>
                    </div>
                    <div class="flex-grow pl-4">
                        <h2 class="font-medium title-font text-sm mb-1 tracking-wider">2018-2022</h2>
                        <p class="leading-relaxed">UNIVERSITAS MULIA PSDKU SAMARINDA</p>
                        <p class="leading-relaxed">S1 - Sistem Informasi</p>
                    </div>
                    </div>
                    <div class="flex relative pb-4">
                    <div class="h-full w-10 absolute inset-0 flex items-center justify-center">
                        <div class="h-full w-1 bg-gray-200 pointer-events-none"></div>
                    </div>
                    <div class="flex-shrink-0 w-10 h-10 rounded-full bg-gray-300 dark:bg-indigo-500 shadow-md inline-flex items-center justify-center  relative z-10">
                        <Icon icon="ion:school-outline" width="32" height="32" />
                    </div>
                    <div class="flex-grow pl-4">
                        <h2 class="font-medium title-font text-sm mb-1 tracking-wider">2015-2018</h2>
                        <p class="leading-relaxed">SMKTI AIRLANGGA SAMARINDA</p>
                        <p class="leading-relaxed">Rekayasa Perangkat Lunak</p>
                    </div>
                    </div>
                </div>
                <h1 class="text-title font-medium flex dark:bg-indigo-500 p-2 rounded-lg shadow-lg mt-5 md:mt-0 mb-5 md:mb-0"><Icon icon="fluent-mdl2:learning-tools" width="32" height="32" /><span class="ml-2 text-lg">Pengalaman</span></h1>
                <div class=" md:pr-10 md:py-6">
                    <div class="flex relative pb-4">
                    <div class="h-full w-10 absolute inset-0 flex items-center justify-center">
                        <div class="h-full w-1 bg-gray-200 pointer-events-none"></div>
                    </div>
                    <div class="flex-shrink-0 w-10 h-10 rounded-full bg-gray-300 dark:bg-indigo-500 inline-flex items-center justify-center  relative z-10 font-bold">
                        1
                    </div>
                    <div class="flex-grow pl-4">
                        <h2 class="font-medium title-font text-sm mb-1 tracking-wider">2017</h2>
                        <p class="leading-relaxed">Magang di bawalsu samarinda dan selama magang saya membuat sebuah project CRUD sederhana untuk sebuah landing page</p>
                    </div>
                    </div>
                </div>
                <h1 class="text-title font-medium flex dark:bg-indigo-500 p-2 rounded-lg shadow-lg mt-5 md:mt-0 mb-5 md:mb-0"><Icon icon="mdi:gear" width="32" height="32" /><span class="ml-2 text-lg">
                    Project
                </span></h1>
                <div class=" md:pr-10 md:py-6">
                    <div class="flex relative pb-4">
                    <div class="h-full w-10 absolute inset-0 flex items-center justify-center">
                        <div class="h-full w-1 bg-gray-200 pointer-events-none"></div>
                    </div>
                    <div class="flex-shrink-0 w-10 h-10 rounded-full bg-gray-300 dark:bg-indigo-500 inline-flex items-center justify-center  relative z-10 font-bold">
                        1
                    </div>
                    <div class="flex-grow pl-4">
                        <h2 class="font-medium title-font text-lg mb-1 tracking-wider">Genshin-tech.com</h2>
                        <h2 class="font-medium title-font text-sm mb-1 tracking-wider">Laravel REST API, TailwindCss, Vue.js.</h2>
                        <p class="leading-relaxed">
                            Sebuah aplikasi untuk membuat <i>character card</i> secara otomatis serta mengumpulkan data untuk membuat statistik sebuah karakter.
                        </p>
                    </div>
                    </div>
                    <div class="flex relative pb-4">
                    <div class="h-full w-10 absolute inset-0 flex items-center justify-center">
                        <div class="h-full w-1 bg-gray-200 pointer-events-none"></div>
                    </div>
                    <div class="flex-shrink-0 w-10 h-10 rounded-full bg-gray-300 dark:bg-indigo-500 inline-flex items-center justify-center  relative z-10 font-bold">
                        2
                    </div>
                    <div class="flex-grow pl-4">
                        <h2 class="font-medium title-font text-lg mb-1 tracking-wider">Posyandu kembang sepatu</h2>
                        <h2 class="font-medium title-font text-sm mb-1 tracking-wider">Laravel, Blade, Bootstrap.</h2>
                        <p class="leading-relaxed">
                            CRUD, Auth, dan authorization untuk mendata pada posyandu kembang sepatu pada masa COVID.
                        </p>
                    </div>
                    </div>
                    <div class="flex relative pb-4">
                    <div class="h-full w-10 absolute inset-0 flex items-center justify-center">
                        <div class="h-full w-1 bg-gray-200 pointer-events-none"></div>
                    </div>
                    <div class="flex-shrink-0 w-10 h-10 rounded-full bg-gray-300 dark:bg-indigo-500 inline-flex items-center justify-center  relative z-10 font-bold">
                       3
                    </div>
                    <div class="flex-grow pl-4">
                        <h2 class="font-medium title-font text-lg mb-1 tracking-wider">Blog</h2>
                        <h2 class="font-medium title-font text-sm mb-1 tracking-wider">Laravel, Blade, Bootstrap, SEO.</h2>
                        <p class="leading-relaxed">
                            Content management sistem sederhana dengan tambahan package seotools.
                        </p>
                    </div>
                    </div>
                </div>
            </div>
          </div>
          </div>
        </div>
      </div>
    </section>
    <div id="canvas" class="felx container mx-auto"></div>

</template>
<script setup>

import { ref,defineProps } from 'vue';
import { Icon } from '@iconify/vue';
import domtoimage from 'dom-to-image';
import { saveAs } from 'file-saver';
import domToPdf from 'dom-to-pdf';
import html2pdf from 'html2pdf.js/dist/html2pdf.min.js';

function exportImg(){
        var node = document.getElementById("exportData");
    var node1 = document.getElementById("canvas");
    domtoimage.toBlob(document.getElementById("exportData"))
    .then(function (blob) {
        window.saveAs(blob, 'CV.png');
    });
//     var options = {
//   filename: 'test.pdf',
//   overrideWidth: node.ScrollWidth
// };
// domToPdf(node, options, function(pdf) {
//   console.log('done');
// });
    // html2pdf().from(node).save();

}
</script>