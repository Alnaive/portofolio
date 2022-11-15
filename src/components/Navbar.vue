<template>
    <header class="sticky top-0 z-30 text-black dark:text-white body-font shadow-md bg-white dark:bg-slate-800 ">
    <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center relative">
      <nav class="asbolute left-0 mr-auto">
        <router-link to="/" class="">Home</router-link>
      </nav>
      <nav class="absolute right-14 space-x-4 mr-auto">
        <router-link to="/about" class="hover:border-white">About</router-link>
        <router-link to="/project" class="">Project</router-link>
        <router-link to="/cv" class="">CV</router-link>
      </nav>
      <div class="flex justify-center items-center absolute right-2">
        <button @click="toggleDark()" >
          <Icon icon="bi:moon-fill" width="24" height="24" v-if="isDark"/> 
          <Icon icon="akar-icons:sun-fill" width="28" height="28" v-else/>
        </button>
      </div>
        
      <!-- <nav class="md:ml-auto flex flex-wrap items-center text-base justify-center space-x-4 ">
        <router-link to="/" >Home</router-link>
        <router-link to="/about">About</router-link>
        <router-link to="/project">Project</router-link>
        <button @click="toggleDark()" >ToggleDark</button>
      </nav> -->
    </div>
    </header>
</template>

<script setup>
import {ref} from 'vue';
import { useDark, useToggle } from '@vueuse/core';
import { RouterLink, RouterView } from 'vue-router'
import { Icon } from '@iconify/vue';

const isDark = useDark();
const toggleDark = useToggle(isDark);
const sidebar = ref(false);
function toggleSidebar() {
    sidebar.value = !sidebar.value;
}
</script>