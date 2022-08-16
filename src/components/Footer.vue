<template>
  <footer class="bottom-0 bg-gray-900 w-full h-auto container">
    <footerWraper>
      <!-- Centre Logo -->
      <div
        class="flex flex-col md:flex-row gap-y-5 md:gap-x-5 justify-center items-center"
      >
        <img
          src="https://ik.imagekit.io/geduCDN/new_logo_min_TP97CGATk4.png"
          alt="GEC Logo"
          class="w-32"
        />
        <p
          class="w-full md:w-72 text-gray-300 font-light tracking-wide text-md"
        >
          GEC (Golden Education Centre) is Best and An ISO (9000:2015) Certified
          Computer Centre in Batala, Punjab
        </p>
      </div>

      <!-- Useful Links -->
      <div class="flex flex-col gap-3 md:gap-y-3 md:items-center md:w-72">
        <h3 class="text-gray-300 text-xl font-sans font-semibold">
          Usefull Links
        </h3>
        <ul class="list-outside list-disc text-left text-gray-300">
          <li class="cursor-pointer text-md hover:text-[#e6c34f] tracking-wide">
            <a>Verification</a>
          </li>
          <li class="cursor-pointer text-md hover:text-[#e6c34f] tracking-wide">
            <a>About Us</a>
          </li>
          <li class="cursor-pointer text-md hover:text-[#e6c34f] tracking-wide">
            <a>Contact Us</a>
          </li>
        </ul>
      </div>

      <!-- Contact Us -->
      <div class="flex flex-col gap-3 md:gap-y-3">
        <h3 class="text-gray-300 text-xl font-sans font-semibold">
          Contact Us
        </h3>
        <p
          class="w-full text-gray-300 font-light tracking-wide text-md md:w-96"
        >
          1<sup>st</sup> Floor King Plaza Market Circular Road, Batala-143505
          Distt Gurdaspur,Punjab,India
        </p>

        <p class="flex gap-2">
          <span class="text-gray-300">Email :</span>
          <a mailto="info@goldenedu.org.in" class="text-[#e6c34f]"
            >info@goldenedu.org.in</a
          >
        </p>
      </div>

    </footerWraper>
    <Copywrite />
  </footer>
</template>

<script setup>
import Copywrite from "./Copywrite.vue";
import FooterWraper from "./Footerwraper.vue";
</script>

<style lang="scss" scoped></style>
