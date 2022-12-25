<template>
  <div class="text-white my-20 space-y-8">
    <p class="text-5xl font-bold mx-8">About</p>
    <p class="text-redish mx-8 font-lightbold">
      WE'RE MORE THAN A DIGITAL AGENCY
    </p>
    <p class="mx-8">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore corrupti
      temporibus fuga earum asperiores, alias excepturi sit. Impedit, fugit
      laudantium.
    </p>
  </div>
  <div class="relative px-8 my-8 hover:opacity-70" v-for="i in 3">
    <img
      src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b6/Image_created_with_a_mobile_phone.png/1200px-Image_created_with_a_mobile_phone.png"
    />
    <div class="absolute text-white bottom-5 left-16">
      <h3 class="text-2xl font-extrabold">Top Left</h3>
      <p class="text-lg">be better with us</p>
    </div>
  </div>
  <div v-for="i in 3" class="text-white mx-8 my-16 space-y-5">
    <p class="font-bold text-2xl">Who we are</p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore corrupti
      temporibus fuga earum asperiores, alias excepturi sit. Impedit, fugit
      laudantium.
    </p>
  </div>
</template>
