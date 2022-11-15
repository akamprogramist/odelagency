<template>
  <nav class="bg-black px-2 sm:px-4 py-2.5">
    <div class="container flex flex-wrap justify-between items-center mx-auto">
      <a href="https://flowbite.com/" class="flex items-center">
        <span
          class="self-center text-white text-2xl font-bold whitespace-nowrap"
          >Odel Agency</span
        >
      </a>
      <button
        data-collapse-toggle="navbar-default"
        type="button"
        class="inline-flex items-center p-2 text-white rounded-lg md:hidden hover:bg-grey"
        aria-controls="navbar-default"
        aria-expanded="false"
      >
        <span class="sr-only">Open main menu</span>
        <svg
          class="w-6 h-6"
          aria-hidden="true"
          fill="currentColor"
          viewBox="0 0 20 20"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            fill-rule="evenodd"
            d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
            clip-rule="evenodd"
          ></path>
        </svg>
      </button>
      <div class="hidden w-full md:block md:w-auto" id="navbar-default">
        <ul
          class="flex flex-col text-center p-4 mt-4 bg-grey rounded-lg md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium md:border-0 md:bg-grey"
        >
          <li>
            <a
              href="#"
              class="block py-2 pr-4 pl-3 text-white rounded hover:bg-redish md:p-0"
              >Home</a
            >
          </li>
          <li>
            <a
              href="#"
              class="block py-2 pr-4 pl-3 text-white rounded hover:bg-redish md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0"
              >About</a
            >
          </li>
          <li>
            <a
              href="#"
              class="block py-2 pr-4 pl-3 text-white rounded hover:bg-redish md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0"
              >Services</a
            >
          </li>
          <li>
            <a
              href="#"
              class="block py-2 pr-4 pl-3 text-white rounded hover:bg-redish md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0"
              >Pricing</a
            >
          </li>
          <li>
            <a
              href="#"
              class="block py-2 pr-4 pl-3 text-white rounded hover:bg-redish md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0"
              >Contact</a
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
