<template>
  <section class="body-font h-full">
    <div class="container px-5 py-24 mx-auto flex flex-wrap">
      <div class="lg:w-1/2 md:w-1/2 md:pr-16 lg:pr-0 pr-0">
        <h1
          class="title-font font-mono font-medium text-[100px] text-black dark:text-white"
        >
          Hey, I'm Fery!
        </h1>
        <p class="font-mono mt-4 text-[20px]">
          an IT Generalist with a diverse skill set, including expertise in web
          development, system analyst, IT infrastructure management, project
          management, PC hardware maintenance, photography, and drone piloting.
          My ability to adapt and handle multiple IT-related tasks makes me a
          versatile professional capable of supporting a wide range of technical
          needs.
        </p>
        <div class="flex mt-10 space-x-2">
          <button class="btn w-32 bg-green-500 text-white">About Me</button>
          <Icon icon="devicon:linkedin" width="50" height="50" />
          <Icon icon="skill-icons:instagram" width="50" height="50" />
        </div>
      </div>
      <div
        class="lg:w-1/2 rounded-lg flex flex-col items-center md:ml-auto w-full mt-10 md:mt-0"
      >
        <img
          class="rounded-lg h-[580px] w-[420px] object-cover"
          src="../../public/20250127_195259.jpg"
        />
      </div>
    </div>
  </section>
  <section class="text-gray-600 body-font">
    <div class="container px-5 py-24 mx-auto flex flex-col">
      <div class="mx-auto">
        <div class="flex flex-col sm:flex-row mt-10">
          <div class="sm:w-1/3 text-center sm:pr-8 sm:py-8">
            <div
              class="rounded-lg inline-flex items-center justify-center bg-gray-200 text-gray-400"
            >
              <img
                class="rounded-lg lg:h-[620px] lg:w-[420px] object-cover"
                src="../../public/20250216_204622.jpg"
                alt=""
                srcset=""
              />
            </div>
            <!-- <img
              class="rounded-lg h-[320px] w-[420px] scale-200 object-cover"
              src="https://cdn.discordapp.com/attachments/1164452737262551050/1284174952131461198/1726241545304.jpg?ex=67b00adf&is=67aeb95f&hm=4143d8bee785329a514ff66778752ab10d652be6ef1cb5a2f2751977c52482ff&"
              alt=""
              srcset=""
            /> -->
          </div>
          <div
            class="lg:flex space-x-4 sm:w-2/3 sm:pl-8 sm:py-8 sm:border-l border-gray-200 sm:border-t-0 border-t mt-4 pt-4 sm:mt-0 text-center sm:text-left"
          >
            <div class="flex flex-col space-y-4">
              <h1 class="font-bold text-4xl text-white">
                Here what you can expect from me...
              </h1>
              <div class="card bg-primary text-primary-content w-96 lg:ml-10">
                <div class="card-body">
                  <h2 class="card-title">Website</h2>
                  <p>Creating web app using a framework</p>
                  <div class="card-actions justify-end"></div>
                </div>
              </div>
              <div class="flex items-center text-center space-x-4">
                <div class="card bg-primary text-primary-content lg:w-56">
                  <div class="card-body">
                    <h2 class="card-title">Laravel</h2>
                  </div>
                </div>
                <div
                  class="card items-center bg-primary text-primary-content lg:w-56"
                >
                  <div class="card-body">
                    <h2 class="card-title">Express.js</h2>
                  </div>
                </div>
              </div>
              <div class="card bg-primary text-primary-content w-96">
                <div class="card-body">
                  <h2 class="card-title">Vue.Js</h2>
                </div>
              </div>
            </div>
            <div class="flex flex-wrap space-y-4 mt-4">
              <div class="card bg-primary text-primary-content w-96">
                <div class="card-body">
                  <h2 class="card-title">Infrastructure</h2>
                  <p>
                    Lan termination, pulling cable, setting up router, CCTV, and
                    radio topology setup.
                  </p>
                </div>
              </div>
              <div class="card bg-primary text-primary-content w-96">
                <div class="card-body">
                  <h2 class="card-title">Hardware</h2>
                  <p>PC & Laptop, pc master race.</p>
                </div>
              </div>
              <div class="card bg-primary text-primary-content w-96">
                <div class="card-body">
                  <h2 class="card-title">Etc</h2>
                  <p>Photography, Drone Pilot, System Analyst.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import { Icon } from "@iconify/vue";
</script>
