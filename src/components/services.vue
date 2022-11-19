<template>
  <div class="text-white">
    <div class="my-20 space-y-8">
      <p class="text-5xl font-bold mx-8">Services</p>
      <p class="text-redish mx-8 font-lightbold">
        WE WORK WITH YOU, NOT FOR YOU
      </p>
    </div>
    <div
      v-for="i in 3"
      class="flex text-black rounded py-8 px-8 mx-8 my-8 spa bg-white justify-between hover:bg-redish hover:text-white hover:pr-5 hover:pl-16 duration-300"
    >
      <p class="text-2xl font-bold">Digital Strategy</p>
      <svg
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke-width="2"
        stroke="currentColor"
        class="w-6 h-6 mt-1"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          d="M17.25 8.25L21 12m0 0l-3.75 3.75M21 12H3"
        />
      </svg>
    </div>
  </div>
</template>
