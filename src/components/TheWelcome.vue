<template>
 <section class="text-black dark:text-white animate-in fade-in duration-500 h-screen">
  <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
    <div class="lg:flex-grow md:w-1/2 md:ml-24 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
      <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium ">Hi, saya Muhammad Fery Perdana
        <br class="hidden lg:inline-block">Fullstack web developer
      </h1>
      <p class="mb-8 leading-relaxed">Experience with laravel, and vue.js</p>
      <div class="flex justify-center">
        <router-link to="/about" class="inline-flex text-white bg-indigo-500 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded text-lg">Tentang Saya</router-link>
      </div>
    </div>
    <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 md:mr-24">
      <img class="object-cover object-center rounded" alt="hero" src="https://scontent-sin6-3.xx.fbcdn.net/v/t1.6435-9/90614411_2929833050395746_7458422833643782144_n.jpg?stp=dst-jpg_s552x414&_nc_cat=105&ccb=1-7&_nc_sid=174925&_nc_eui2=AeHbgWGsxpdYsrNKsFPEtnbL-Pk5KH09PLD4-TkofT08sK8w6EqTEuqmQq4Lb-vpKGAFHrtef0oCaCuQzjbGsErk&_nc_ohc=cMwHqux9jKMAX-wnkV6&_nc_ht=scontent-sin6-3.xx&oh=00_AfCkyPd6AnrUFfa_UzXzJXko4epaR5EKQMOGswq8yyJuPw&oe=639A6C0D">
    </div>
  </div>
</section>
</template>