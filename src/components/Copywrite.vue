<template>
  <div
    class="w-full bg-inherit text-gray-300 font-extralight bottom-0 py-2.5 flex flex-col md:flex-row gap-2 justify-between md:px-[10%] items-center"
  >
    <p class="text-sm">
      &copy; {{ toyear > fromyear ? `${fromyear} - ${toyear}` : `${fromyear}` }}
      <span> | Golden Education Centre</span>
    </p>
    <p>
      Made in ❤️ India by
      <span
        ><a href="https://www.linkedin.com/in/damanohri/" target="_blank" class="text-[#e6c34f]"
          >@daman.ohri</a
        ></span
      >
    </p>
  </div>
</template>

<script setup>
import { ref } from "vue";

const year = new Date().getFullYear();
const fromyear = ref("2022");
const toyear = ref(year);
</script>
