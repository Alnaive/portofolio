<template>
  <h1 class="visible lg:invisible text-center p-5 text-lg font-bold">
    Show Desktop site to dowload the CV
  </h1>
  <div
    class="invisible md:visible flex container mx-auto items-center justify-center py-8"
  >
    <button class="w-24 h-12 bg-indigo-500 rounded-lg" @click="exportImg()">
      <span class="flex items-center justify-center"
        ><Icon icon="bxs:file-png" width="32" height="32" />PNG</span
      >
    </button>
    <button
      class="w-24 h-12 bg-indigo-500 rounded-lg ml-10"
      @click="onDownload"
    >
      <span class="flex items-center justify-center"
        ><Icon icon="bxs:file-pdf" width="32" height="32" />PDF</span
      >
    </button>
  </div>
  <section class="text-black dark:text-white body-font">
    <div
      class="container px-5 mx-auto flex flex-col bg-white dark:bg-slate-800"
    >
      <div
        class="md:w-[793.7007874px] md:h-[1122.519685px] md:relative mx-auto flex mb-5"
      >
        <div
          id="exportData"
          ref="pdfData"
          class="bg-white dark:bg-slate-800 p-2 shadow-lg rounded-lg"
        >
          <div class="flex flex-col sm:flex-row mt-5 rounded-lg">
            <div class="sm:w-1/3 sm:pr-8 sm:py-8 md:w-72">
              <div class="text-center">
                <div
                  class="w-32 h-32 inline-flex items-center justify-center bg-gray-200 text-gray-400"
                >
                  <img
                    class="object-contain"
                    src="../../public/4_x_6_1985.jpg"
                    alt=""
                    srcset=""
                  />
                </div>
              </div>
              <div class="flex flex-col">
                <h2 class="font-medium title-font mt-4 text-lg text-center">
                  Muhammad Fery Perdana <br />IT Generalist
                </h2>
                <div
                  class="w-full ml-2 h-1 bg-indigo-500 rounded mt-2 mb-4"
                ></div>
                <h1
                  class="flex mt-2 mb-5 shadow-lg rounded-lg dark:bg-indigo-500 p-2"
                >
                  <Icon icon="bxs:contact" width="32" height="32" />
                  <span class="ml-2 text-lg">Contact</span>
                </h1>
                <div class="flex space-y-2 ml-2 flex-col">
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
                    <h1>
                      <a href="https://feryperdana.vercel.app/"
                        >feryperdana.vercel.app</a
                      >
                    </h1>
                  </div>
                  <div class="flex items-center space-x-2">
                    <Icon icon="mdi:linkedin" width="32" height="32" />
                    <h1>
                      <a href="https://linkedin.com/in/fery-perdana"
                        >Fery Perdana</a
                      >
                    </h1>
                  </div>
                </div>
                <h1
                  class="flex mt-5 shadow-lg rounded-lg dark:bg-indigo-500 p-2"
                >
                  <Icon icon="bi:database-gear" width="32" height="32" />
                  <span class="ml-2 text-lg">Skill</span>
                </h1>
                <div class="flex space-y-2 ml-2 flex-col mt-5">
                  <div class="flex items-center space-x-2">
                    <Icon
                      icon="ic:baseline-developer-mode"
                      width="32"
                      height="32"
                    />
                    <h1>Web Programmer</h1>
                  </div>
                  <div class="flex items-center space-x-2">
                    <Icon icon="ri:building-fill" width="32" height="32" />
                    <h1>IT infrastructure</h1>
                  </div>
                  <div class="flex items-center space-x-2">
                    <Icon icon="eos-icons:drone" width="32" height="32" />
                    <h1>Drone</h1>
                  </div>
                </div>
              </div>
            </div>
            <div
              class="sm:w-2/3 sm:pl-8 sm:py-8 sm:border-l border-gray-200 sm:border-t-0 border-t mt-4 pt-4 sm:mt-0 text-center sm:text-left"
            >
              <h1
                class="text-title font-medium flex dark:bg-indigo-500 p-2 rounded-lg shadow-lg mb-5 md:mb-0"
              >
                <Icon icon="la:school" width="32" height="32" /><span
                  class="ml-2 text-lg"
                  >Education</span
                >
              </h1>
              <div class="md:pr-10 md:py-6">
                <div class="flex relative pb-5">
                  <div
                    class="h-full w-10 absolute inset-0 flex items-center justify-center"
                  >
                    <div
                      class="h-full w-1 bg-gray-200 pointer-events-none"
                    ></div>
                  </div>
                  <div
                    class="flex-shrink-0 w-10 h-10 rounded-full bg-gray-300 dark:bg-indigo-500 inline-flex items-center justify-center relative z-10"
                  >
                    <Icon icon="fa-solid:university" width="32" height="32" />
                  </div>
                  <div class="flex-grow pl-4">
                    <h2
                      class="font-medium title-font text-sm mb-1 tracking-wider"
                    >
                      2018-2022
                    </h2>
                    <p class="leading-relaxed">
                      UNIVERSITAS MULIA PSDKU SAMARINDA
                    </p>
                    <p class="leading-relaxed">S1 - Information Systems</p>
                  </div>
                </div>
                <div class="flex relative pb-4">
                  <div
                    class="h-full w-10 absolute inset-0 flex items-center justify-center"
                  >
                    <div
                      class="h-full w-1 bg-gray-200 pointer-events-none"
                    ></div>
                  </div>
                  <div
                    class="flex-shrink-0 w-10 h-10 rounded-full bg-gray-300 dark:bg-indigo-500 shadow-md inline-flex items-center justify-center relative z-10"
                  >
                    <Icon icon="ion:school-outline" width="32" height="32" />
                  </div>
                  <div class="flex-grow pl-4">
                    <h2
                      class="font-medium title-font text-sm mb-1 tracking-wider"
                    >
                      2015-2018
                    </h2>
                    <p class="leading-relaxed">SMKTI AIRLANGGA SAMARINDA</p>
                    <p class="leading-relaxed">Software Engineering</p>
                  </div>
                </div>
              </div>
              <h1
                class="text-title font-medium flex dark:bg-indigo-500 p-2 rounded-lg shadow-lg mt-5 md:mt-0 mb-5 md:mb-0"
              >
                <Icon
                  icon="fluent-mdl2:learning-tools"
                  width="32"
                  height="32"
                /><span class="ml-2 text-lg">Experience</span>
              </h1>
              <div class="md:pr-10 md:py-6">
                <div class="flex relative pb-4">
                  <div
                    class="h-full w-10 absolute inset-0 flex items-center justify-center"
                  >
                    <div
                      class="h-full w-1 bg-gray-200 pointer-events-none"
                    ></div>
                  </div>
                  <div
                    class="flex-shrink-0 w-10 h-10 rounded-full bg-gray-300 dark:bg-indigo-500 inline-flex items-center justify-center relative z-10 font-bold"
                  >
                    1
                  </div>
                  <div class="flex-grow pl-4">
                    <h2
                      class="font-medium title-font text-md mb-1 tracking-wider"
                    >
                      2023 - Now
                    </h2>
                    <h2
                      class="font-medium title-font text-md mb-1 tracking-wider"
                    >
                      IT Technician/Support
                    </h2>
                    <h2
                      class="font-medium title-font text-md mb-1 tracking-wider"
                    >
                      PT. Perindustrian Sawit Synergi
                    </h2>
                    <h1 class="">IT Technician Responsibilities:</h1>
                    <ul class="list-disc leading-relaxed text-sm ml-5">
                      <li>
                        Managed IT infrastructure projects, including the
                        development of a server room in collaboration with
                        vendors.
                      </li>
                      <li>
                        LAN cable installation, server rack assembly, access
                        door setup, CCTV installation, and internet
                        configuration using point-to-point and multi-point
                        methods with MikroTik and Ubiquiti radio devices.
                      </li>
                    </ul>
                    <h1 class="">IT Support Responsibilities:</h1>
                    <ul class="list-disc leading-relaxed text-sm ml-5">
                      <li>
                        Handled administrative tasks such as asset management
                        and procurement of equipment.
                      </li>
                      <li>
                        Performed installation and maintenance of PCs, laptops,
                        printers, and drone.
                      </li>
                    </ul>
                  </div>
                </div>
                <div class="flex relative pb-4">
                  <div
                    class="h-full w-10 absolute inset-0 flex items-center justify-center"
                  >
                    <div
                      class="h-full w-1 bg-gray-200 pointer-events-none"
                    ></div>
                  </div>
                  <div
                    class="flex-shrink-0 w-10 h-10 rounded-full bg-gray-300 dark:bg-indigo-500 inline-flex items-center justify-center relative z-10 font-bold"
                  >
                    2
                  </div>
                  <div class="flex-grow pl-4">
                    <h2
                      class="font-medium title-font text-md mb-1 tracking-wider"
                    >
                      2017
                    </h2>
                    <h2
                      class="font-medium title-font text-md mb-1 tracking-wider"
                    >
                      Web Programmer
                    </h2>
                    <h2
                      class="font-medium title-font text-md mb-1 tracking-wider"
                    >
                      Bawaslu kaltim
                    </h2>
                    <h1 class="">Responsibilities:</h1>
                    <ul class="list-disc leading-relaxed text-sm ml-5">
                      <li>
                        internship at Bawalsu Samarinda, I developed a simple
                        CRUD project for a landing page using PHP and Bootstrap
                        as the tech stack.
                      </li>
                    </ul>
                  </div>
                </div>
              </div>
              <!-- <h1
                class="text-title font-medium flex dark:bg-indigo-500 p-2 rounded-lg shadow-lg mt-5 md:mt-0 mb-5 md:mb-0"
              >
                <Icon icon="mdi:gear" width="32" height="32" /><span
                  class="ml-2 text-lg"
                >
                  Project
                </span>
              </h1>
              <div class="md:pr-10 md:py-6">
                <div class="flex relative pb-4">
                  <div
                    class="h-full w-10 absolute inset-0 flex items-center justify-center"
                  >
                    <div
                      class="h-full w-1 bg-gray-200 pointer-events-none"
                    ></div>
                  </div>
                  <div
                    class="flex-shrink-0 w-10 h-10 rounded-full bg-gray-300 dark:bg-indigo-500 inline-flex items-center justify-center relative z-10 font-bold"
                  >
                    1
                  </div>
                  <div class="flex-grow pl-4">
                    <h2
                      class="font-medium title-font text-lg mb-1 tracking-wider"
                    >
                      IT Infrastructure
                    </h2>
                    <h2
                      class="font-medium title-font text-sm mb-1 tracking-wider"
                    >
                      Wifi installation, Server Installation.
                    </h2>
                    <p class="leading-relaxed">
                      In PT. Perindustrian Sawit Synergi, I have been involved
                      in IT infrastructure projects, including the development
                      of a server room in collaboration with vendors.
                    </p>
                  </div>
                </div>
                <div class="flex relative pb-4">
                  <div
                    class="h-full w-10 absolute inset-0 flex items-center justify-center"
                  >
                    <div
                      class="h-full w-1 bg-gray-200 pointer-events-none"
                    ></div>
                  </div>
                  <div
                    class="flex-shrink-0 w-10 h-10 rounded-full bg-gray-300 dark:bg-indigo-500 inline-flex items-center justify-center relative z-10 font-bold"
                  >
                    2
                  </div>
                  <div class="flex-grow pl-4">
                    <h2
                      class="font-medium title-font text-lg mb-1 tracking-wider"
                    >
                      Rails Express
                    </h2>
                    <h2
                      class="font-medium title-font text-sm mb-1 tracking-wider"
                    >
                      Vue.js, Node.js, Mihomo API.
                    </h2>
                    <p class="leading-relaxed">
                      Character showcase for a game Honkai Star Rails using
                      Mihomo API.
                    </p>
                  </div>
                </div>
                <div class="flex relative pb-4">
                  <div
                    class="h-full w-10 absolute inset-0 flex items-center justify-center"
                  >
                    <div
                      class="h-full w-1 bg-gray-200 pointer-events-none"
                    ></div>
                  </div>
                  <div
                    class="flex-shrink-0 w-10 h-10 rounded-full bg-gray-300 dark:bg-indigo-500 inline-flex items-center justify-center relative z-10 font-bold"
                  >
                    3
                  </div>
                  <div class="flex-grow pl-4">
                    <h2
                      class="font-medium title-font text-lg mb-1 tracking-wider"
                    >
                      Approval Email System
                    </h2>
                    <h2
                      class="font-medium title-font text-sm mb-1 tracking-wider"
                    >
                      Microsoft Power App, Microsoft Power Automate.
                    </h2>
                    <p class="leading-relaxed">
                      Simple approval send to email using Microsoft Power App
                      and Microsoft Power Automate.
                    </p>
                  </div>
                </div>
              </div> -->
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script setup>
import { ref, defineProps } from "vue";
import { Icon } from "@iconify/vue";
import domtoimage from "dom-to-image";
import { saveAs } from "file-saver";
import { jsPDF } from "jspdf";

const pdfData = ref(null);

const onDownload = () => {
  // Define A4 dimensions in points
  const a4Width = 595.28; // A4 width in points
  const a4Height = 841.89; // A4 height in points

  // Convert HTML table to PNG image using dom-to-image
  domtoimage.toPng(pdfData.value).then((imageData) => {
    // Create a new jsPDF document in portrait orientation
    const pdf = new jsPDF("p", "pt", "a4"); // "p" for portrait, "a4" for A4 size

    // Add the PNG image to the PDF document
    pdf.addImage(imageData, "PNG", 0, 0, a4Width, a4Height);

    // Save the PDF document
    pdf.save("cv.pdf");
  });
};

const getThisYear = () => {
  const date = new Date();
  return date.getFullYear();
};

function exportImg() {
  var node = document.getElementById("exportData");
  var node1 = document.getElementById("canvas");
  domtoimage
    .toBlob(document.getElementById("exportData"))
    .then(function (blob) {
      window.saveAs(blob, "CV.png");
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
