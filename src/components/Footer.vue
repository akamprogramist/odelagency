<template>
  <div class="space-y-8 bg-grey py-16">
    <div class="flex justify-center space-x-5 text-white border-white">
      <div
        v-for="i in 3"
        class="border-2 border-redish p-2 mt-4 rounded-full hover:bg-redish duration-500"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          strokeWidth="{1.5}"
          stroke="currentColor"
          class="w-8 h-8"
        >
          <path
            strokeLinecap="round"
            strokeLinejoin="round"
            d="M4.26 10.147a60.436 60.436 0 00-.491 6.347A48.627 48.627 0 0112 20.904a48.627 48.627 0 018.232-4.41 60.46 60.46 0 00-.491-6.347m-15.482 0a50.57 50.57 0 00-2.658-.813A59.905 59.905 0 0112 3.493a59.902 59.902 0 0110.399 5.84c-.896.248-1.783.52-2.658.814m-15.482 0A50.697 50.697 0 0112 13.489a50.702 50.702 0 017.74-3.342M6.75 15a.75.75 0 100-1.5.75.75 0 000 1.5zm0 0v-3.675A55.378 55.378 0 0112 8.443m-7.007 11.55A5.981 5.981 0 006.75 15.75v-1.5"
          />
        </svg>
      </div>
    </div>
    <div class="text-white text-center font-extrabold text-4xl">
      Let's Talk?
    </div>
    <button
      class="flex text-white font-bold mx-auto px-8 py-4 border-2 border-redish rounded-lg hover:bg-redish duration-500"
    >
      Getting started
    </button>
  </div>
  <div class="bg-zinc-800 py-10 space-y-1">
    <h1 class="text-white text-center text-xl font-extrabold">Suli Office</h1>
    <p class="text-white text-center text-xl">07700656816</p>
  </div>
  <div class="block py-10 space-y-2">
    <h1 class="text-white text-center">
      2022 &copy; <a href="#" class="text-xl font-extrabold">Odel Agency</a>,
      All rights reserved.
    </h1>
    <div class="flex text-white space-x-8 justify-center">
      <a
        href="#"
        class="hover:text-redish pb-1 hover:border-b-2 border-redish duration-150"
        >Designing</a
      >
      <a
        href="#"
        class="hover:text-redish pb-1 hover:border-b-2 border-redish duration-150"
        >Programming</a
      >
      <a
        href="#"
        class="hover:text-redish pb-1 hover:border-b-2 border-redish duration-150"
        >Social Media</a
      >
    </div>
  </div>
</template>
