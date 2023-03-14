<template>
  <div class="hello">
    <div class="relative">
      <div class="mainMenu">
        <div class="flex mx-40 text-center py-2">
          <a><img class="mx-auto w-5 h-5" :src="require('@/assets/apple-logo.png')" /></a>
          <a v-for="item in menuItems" :key="item">{{ item }}</a>
          <a>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
              stroke="currentColor" class="w-5 h-5">
              <path stroke-linecap="round" stroke-linejoin="round"
                d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" />
            </svg>
          </a>
          <a>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
              stroke="currentColor" class="w-5 h-5">
              <path stroke-linecap="round" stroke-linejoin="round"
                d="M15.75 10.5V6a3.75 3.75 0 10-7.5 0v4.5m11.356-1.993l1.263 12c.07.665-.45 1.243-1.119 1.243H4.25a1.125 1.125 0 01-1.12-1.243l1.264-12A1.125 1.125 0 015.513 7.5h12.974c.576 0 1.059.435 1.119 1.007zM8.625 10.5a.375.375 0 11-.75 0 .375.375 0 01.75 0zm7.5 0a.375.375 0 11-.75 0 .375.375 0 01.75 0z" />
            </svg>
          </a>
        </div>
      </div>
    </div>

    <div class="w-100 h-full shadow-lg mx-auto mt-20 text-center">
      <h1 class="text-center text-5xl font-bold">iPhone 14</h1>

      <h4 class="text-center text-2xl font-small my-5">
        Pil ömründe büyük gelişme.
        <br />
        İki harika boyut. Ve yepyeni sarı renk seçeneği.
      </h4>
      <p class="text-gray-600 text-xl">Satış Tarihi: 24 Mart</p>
      <div class="flex justify-center mt-5">
        <a href="www.twitter.com" class="mx-5 text-sky-600 hover:underline text-xl">Daha fazla bilgi ></a>
        <a href="www.twitter.com" class="mx-5 text-sky-600 hover:underline text-xl">
          Alışveriş yapın ></a>
      </div>
      <img class="mx-auto w-4/12 mt-20 content-end" :src="require('@/assets/yellowphone.png')" />
    </div>

    <div class="w-100 h-100 shadow-lg mx-auto bg-black">
      <h1 class="text-center text-white text-5xl font-bold pt-20">
        iPhone 14 Pro
      </h1>

      <h4 class="text-center text-white text-2xl font-medium">
        Pil ömründe büyük gelişme.
        <br />
        İki harika boyut. Ve yepyeni sarı renk seçeneği.
      </h4>
      <div class="flex justify-center mt-5">
        <a href="www.twitter.com" class="mx-5 text-sky-600 hover:underline text-xl">Daha fazla bilgi ></a>
        <a href="www.twitter.com" class="mx-5 text-sky-600 hover:underline text-xl">Satın alın></a>
      </div>
      <img class="mx-auto w-8/12 mt-20 content-end" :src="require('@/assets/14pro.png')" />
    </div>

    <div class="w-100 shadow-lg mx-auto bg-black mt-2 place-content-center object-center text-center">
      <img class="mx-auto pt-10 w-2/12" :src="require('@/assets/watch.png')" />
      <h1 class="text-red-600 text-xl font-bold">SERIES 8</h1>
      <h4 class="text-white text-2xl font-medium">
        Gelecek iyi hissettirecek.
      </h4>
      <div class="flex justify-center mt-5">
        <a href="www.twitter.com" class="mx-5 text-sky-600 hover:underline text-xl">Daha fazla bilgi ></a>
        <a href="www.twitter.com" class="mx-5 text-sky-600 hover:underline text-xl">Satın alın></a>
      </div>
      <img class="mx-auto w-5/12 mt-5 content-end" :src="require('@/assets/watch-red.png')" />
    </div>

    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
import "@/assets/tailwind.css";

export default {
  name: "HelloWorld",
  props: {
    msg: String,
    menuItems: [],
  },
};
</script>
