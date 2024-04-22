<script setup></script>
<template>
  <div class="flex flex-col text-center items-center pt-10 h-screen">
    <h1 class="text-5xl font-main font-light">spiderdev.vn</h1>
    <img
      src="/logo.jpg"
      class="w-64 rounded-[3rem] my-10 shadow-lg hover:shadow-xl hover:scale-105 duration-100"
    />
    <h2 class="font-main font-light">Website spiderdev đang được mọi người tích cực hoàn thiện</h2>
    <h2 class="font-main font-light">Mọi người quay lại sau nhé!</h2>

    <div class="bg-gradient-to-tl from-blue-900 to-blue-400 rounded-full mt-5">
      <img
        src="./assets/rolling.svg"
        class="animate-spin"
      />
    </div>
    <hr class="w-32 my-10" />
    <p class="font-main font-light">Theo dõi spiderdev.vn tại các kênh sau</p>
    <div class="drop-shadow-xl w-96 border flex justify-around text-5xl py-4 rounded-xl my-5">
      <a
        href="https://www.facebook.com/spiderdev.vn"
        target="_blank"
        class="text-blue-500 hover:text-blue-600"
        ><i
          class="fa-brands fa-facebook hover:scale-110 duration-100"
          title="spiderdev.vn"
        ></i
      ></a>
      <a
        href="https://github.com/spiderdev-vn"
        target="_blank"
        class="text-gray-800 hover:text-black"
        ><i
          class="fa-brands fa-github hover:scale-110 duration-100"
          title="spiderdev-vn"
        ></i
      ></a>
      <a
        href="https://www.youtube.com/@spiderdev.official"
        target="_blank"
        class="text-red-500 hover:text-red-600"
        ><i
          class="fa-brands fa-youtube hover:scale-110 duration-100"
          title="@spiderdev.official"
        ></i
      ></a>
      <a
        href="https://tiktok.com/@spiderdev.vn"
        target="_blank"
        class="text-gray-800 hover:text-black"
        ><i
          class="fa-brands fa-tiktok hover:scale-110 duration-100"
          title="@spiderdev.vn"
        ></i
      ></a>
    </div>
  </div>
</template>
