<template>
    <div v-if="!overlayHidden">
        <div class="w-screen h-screen flex justify-center bg-gray-500 items-center absolute z-10">
            <h1 class="text-[100px] ">
                <button class="animate-in spin-in-180 duration-700 repeat-infinite">Loading</button>
                hello world! 
            </h1>
        </div>
    </div>
    <div v-else class="animate-in slide-in-from-top w-screen bg-gray-500 h-screen flex justify-center items-center absolute z-10">
        <div class="animate-in fade-in-50 delay-700">
            asd
        </div>
    </div>
</template>
<script setup>
import {ref, onMounted} from 'vue'

const overlayHidden = ref(false);
function overlayInterval(){
  setInterval(() => {
    overlayHidden.value = true
  }, 5000)
}
onMounted(() => {
  overlayInterval()
})
</script>