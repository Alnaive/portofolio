<template>
    <section class="text-black dark:text-white body-font">
      <div :class="skills ? 'container px-5 motion-safe:animate-in slide-in-from-bottom ease-linear duration-500 mx-auto flex flex-col':'container px-5 py-24 mx-auto flex flex-col'">
        <div class="lg:w-4/6 mx-auto">
          <div class="flex flex-col items-center sm:flex-row mt-10">
            <div class="sm:w-1/3 text-center sm:pr-8 sm:py-8 animate-in fade-in ease-linear ">
              <div class="w-32 h-32 rounded-full inline-flex items-center justify-center bg-gray-200 text-gray-400">
                <img class="object-fit rounded-full" src="https://media.discordapp.net/attachments/873515567930290237/1054257646523400212/26233065_1637187756326955_9085236053320698975_o.png?width=701&height=701" alt="" srcset="">
              </div>
              <div class="flex flex-col items-center text-center justify-center">
                <h2 class="font-medium title-font mt-4  text-lg">Muhammad Fery Perdana S.Kom</h2>
                <!-- <h3 class="font-medium title-font text-md">Web Programmer</h3> -->
                <div class="w-12 h-1 bg-indigo-500 rounded mt-2 mb-4"></div>
                <div class="flex space-y-2 flex-col">
                    <div class="flex items-center space-x-2">
                        <Icon icon="fa-solid:university" width="32" />
                        <h1>Universitas Mulia</h1>
                    </div>
                    <div class="flex items-center space-x-2">
                        <Icon icon="bi:phone" width="32" />
                        <h1>081242397622</h1>
                    </div>
                    <div class="flex items-center space-x-2">
                        <Icon icon="entypo:mail" width="32" />
                        <h1>feryperdana@outlook.com</h1>
                    </div>
                </div>
              </div>
            </div>
            <div class="sm:w-2/3 sm:pl-8 sm:py-8 sm:border-l border-gray-200 sm:border-t-0 border-t mt-4 pt-4 sm:mt-0 text-center sm:text-left">
              <p class="animate-in fade-in ease-linear duration-300 leading-relaxed text-lg mb-4  ">
                <i>Fresh graduate</i> dari universitas mulia bidang studi S1 sistem informasi.
                Memiliki pengalaman membuat website dengan framework laravel dan vue.js.
                Bercita-cita sebagai <i>game architect</i> dan sangat menyukai hal-hal berbau astronomi.
              </p>
              <button class="animate-in fade-in ease-linear duration-300 text-white bg-indigo-500 border-0 py-2 px-8 focus:outline-none hover:bg-indigo-600 rounded text-lg" @click="showSkill()">Lihat Kemampuan</button>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="text-black dark:text-white body-font md:h-screen" >
  <div class="container px-5 py-24 mx-auto"  v-if="skills">
    <div class="flex flex-wrap w-full mb-20 flex-col items-center text-center animate-in fade-in ease-linear">
      <h1 class="sm:text-3xl text-2xl font-medium title-font mb-2 ">Kemampuan</h1>
      <p class="lg:w-1/2 w-full leading-relaxed text-gray-500">Berikut ini adalah kemampuan yang saya miliki</p>
    </div>
    <div class="flex flex-wrap -m-4" >
      <div class="xl:w-1/3 md:w-1/2 p-4 animate-in slide-in-from-left-72" duration-500>
        <div class="border border-gray-200 p-6 rounded-lg">
          <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-4">
            <Icon icon="logos:tailwindcss-icon" width="24" height="24" />
          </div>
          <h2 class="text-lg  font-medium title-font mb-2">TailwindCss</h2>
                <p class="leading-relaxed text-base">Utility CSS terbaik dan mudah untuk digunakan biasanya saya menggunakan komponen DaisyUI</p>
        </div>
      </div>
      <div class="xl:w-1/3 md:w-1/2 p-4 animate-in fade-in ease-in-out duration-500">
        <div class="border border-gray-200 p-6 rounded-lg">
          <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-4">
            <Icon icon="cib:laravel" color="red" width="24" height="24" />

          </div>
          <h2 class="text-lg  font-medium title-font mb-2">Laravel</h2>
          <p class="leading-relaxed text-base">Framework PHP termudah untuk membuat sebuah website, dengan mengunakan metode MVC membuat laravel nyaman untuk digunakan sebagai
                    senjata fullstack developer.
                </p>
        </div>
      </div>
      <div class="xl:w-1/3 md:w-1/2 p-4 animate-in slide-in-from-right-72 duration-500">
        <div class="border border-gray-200 p-6 rounded-lg">
          <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-4">
            <Icon icon="logos:vue" width="24" height="24" />
          </div>
          <h2 class="text-lg  font-medium title-font mb-2">Vue.Js</h2>
            <p class="leading-relaxed text-base">Salah satu Frontend terbaik dan mudah untuk digunakan dengan kombinasi Laravel+Inertia atau menggunakan API sebagai perantara data</p>
        </div>
      </div>
      <div class="xl:w-1/3 md:w-1/2 p-4">
        <div class="border border-gray-200 p-6 rounded-lg">
          <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-4">
            <Icon icon="fontisto:mysql" width="24" height="24" />
          </div>
          <h2 class="text-lg  font-medium title-font mb-2">MySql</h2>
          <p class="leading-relaxed text-base">DBMS andalan fullstack developer</p>
        </div>
      </div>
      <div class="xl:w-1/3 md:w-1/2 p-4">
        <div class="border border-gray-200 p-6 rounded-lg">
          <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-4">
            <Icon icon="logos:mongodb" width="24" height="24" />
          </div>
          <h2 class="text-lg  font-medium title-font mb-2">MongoBD</h2>
          <p class="leading-relaxed text-base">NoSQL yang saya gunakan</p>
        </div>
      </div>
      <div class="xl:w-1/3 md:w-1/2 p-4">
        <div class="border border-gray-200 p-6 rounded-lg">
          <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-4">
            <Icon icon="logos:nodejs" width="24" height="24" />
          </div>
          <h2 class="text-lg  font-medium title-font mb-2">Node.Js</h2>
          <p class="leading-relaxed text-base">Backend javascript yang saya geunakan dengan framework Express.js</p>
        </div>
      </div>
      <!-- <div class="xl:w-1/3 md:w-1/2 p-4">
        <div class="border border-gray-200 p-6 rounded-lg">
          <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-4">
            <Icon icon="cib:unreal-engine" width="24" height="24" />
          </div>
          <h2 class="text-lg  font-medium title-font mb-2">Unreal Engine</h2>
          <p class="leading-relaxed text-base">Selama masa kuliah saya mencoba membuat fullstack fps menggunakan asset seadany.
            Membuat level desain adalah bagian favorite apalagi sekarang sudah banyak asset gratis dari Epic Game.
          </p>
        </div>
      </div> -->
    </div>
  </div>
</section>
</template>
<script setup>
import {ref} from 'vue'
import { Icon } from '@iconify/vue';

const skills = ref(false);
function showSkill(){
    skills.value = true;
}
</script>