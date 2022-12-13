<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue'
import Overlay from './components/Overlay.vue'
import HelloWorld from './components/HelloWorld.vue'
import {ref, onMounted} from 'vue'

const overlayHidden = ref(false);
function overlayTimeout(){
  setTimeout(() => {
    overlayHidden.value = true
  }, 5000)
}
onMounted(() => {
  overlayTimeout()
})
</script>

<template>
<div class="w-screen h-screen flex flex-col md:flex-row space-x-4 justify-center  items-center" v-if="!overlayHidden">
  <div class="w-16 h-16 md:w-24 md:h-24 rounded-full animate-spin border-8 border-solid border-green-500 border-t-transparent"></div>
  <h1 class="text-3xl text-center mt-4 md:mt-none md:text-left"> Tunggu Sebentar...
  <br> <span class="text-lg">Cuman animasi timeout jangan ditutup</span>
  </h1>
</div>
<div v-else class="h-auto md:h-auto dark:bg-gray-800 bg-white animate-in zoom-in-90">
  <Navbar/>
  <RouterView />
</div>
     
  <!-- <div class="w-screen h-screen dark:bg-gray-800 bg-white absolute z-20">
    <Overlay/>
    <Navbar/>
    <RouterView />
  </div> -->
</template>

