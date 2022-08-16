<template>
  <section class="text-gray-600 body-font relative">
    <div class="h-[450px] md:h-[600px] mx-auto flex sm:flex-nowrap flex-wrap">
      <div
        class="w-full bg-gray-300  overflow-hidden p-3 md:p-10 flex items-end justify-start relative"
      >
        <iframe
          width="100%"
          height="100%"
          class="absolute inset-0"
          frameborder="0"
          title="map"
          marginheight="0"
          marginwidth="0"
          scrolling="no"
          src="https://maps.google.com/maps?width=100%&height=600&hl=en&q=%C4%B0zmir+(My%20Business%20Name)&ie=UTF8&t=&z=14&iwloc=B&output=embed"
          style="filter: grayscale(0.1) contrast(1) opacity(0.7)"
        ></iframe>
        <div class="bg-white relative flex flex-wrap py-6 rounded shadow-md">
          <div class="lg:w-1/2 px-6 ">
            <h2
              class="title-font font-semibold text-gray-900 tracking-widest text-xs"
            >
              ADDRESS
            </h2>
            <p class="mt-1">
              1<sup>st</sup> Floor King Plaza Market Circular Road, Batala-143505
          Distt Gurdaspur,Punjab,India
            </p>
          </div>
          <div class="lg:w-1/2 px-6 mt-4 lg:mt-0">
            <h2
              class="title-font font-semibold text-gray-900 tracking-widest text-xs"
            >
              EMAIL
            </h2>
            <a class="text-indigo-500 leading-relaxed">example@email.com</a>
            <h2
              class="title-font font-semibold text-gray-900 tracking-widest text-xs mt-4"
            >
              PHONE
            </h2>
            <p class="leading-relaxed">123-456-7890</p>
          </div>
        </div>
      </div>

    </div>
  </section>
</template>
