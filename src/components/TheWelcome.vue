<template>
 <section class="text-black dark:text-white animate-in fade-in duration-500 md:h-screen">
  <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
    <div class="lg:flex-grow md:w-1/2 md:ml-24 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
      <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium ">Halo, saya Muhammad Fery Perdana
        <br class="hidden lg:inline-block">Web Programmer
      </h1>
      <div class="flex justify-center">
        <router-link to="/about" class="inline-flex text-white bg-indigo-500 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded text-lg">Tentang Saya</router-link>
      </div>
    </div>
    <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 md:mr-24">
      <img class="object-cover object-center rounded" alt="hero" src="https://media.discordapp.net/attachments/873515567930290237/1054257646523400212/26233065_1637187756326955_9085236053320698975_o.png?width=701&height=701">
    </div>
  </div>
</section>
</template>