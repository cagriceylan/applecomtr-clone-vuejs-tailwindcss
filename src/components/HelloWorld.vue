<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <div class="w-100 h-screen shadow-lg mx-auto mt-100 text-center">
      <h1 class="text-center text-5xl font-bold">
        iPhone 14
      </h1>

      <h4 class="text-center text-2xl font-medium">
        Pil ömründe büyük gelişme.
        <br>
        İki harika boyut. Ve yepyeni sarı renk seçeneği.
      </h4>
      <p>Satış Tarihi: 24 Mart</p>
      <div class="flex justify-center">
        <a href="www.twitter.com" class="mx-5 text-sky-600">Daha fazla bilgi</a>
        <a href="www.twitter.com" class="mx-5 text-sky-600">Alışveriş yapın</a>
      </div>
      <img class="mx-auto w-6/12 my-10 content-end" :src="require('@/assets/yellowphone.png')"/>
    </div>

    <div class="w-100 shadow-lg mx-auto bg-black">
      <h1 class="text-center text-white text-4xl font-bold">
        iPhone 14 Pro
      </h1>

      <h4 class="text-center text-white text-2xl font-medium">
        Pil ömründe büyük gelişme.
        <br>
        İki harika boyut. Ve yepyeni sarı renk seçeneği.
      </h4>
      <img class="mx-auto max-w-xs" :src="require('@/assets/14pro.png')"/>
    </div>
    
    <div class="w-100 shadow-lg mx-auto bg-black mt-2 place-content-center object-center">
      <img class="mx-auto" :src="require('@/assets/watch.png')"/>
      <h4 class="text-center text-white text-2xl font-medium">
        Gelecek iyi hissettirecek
      </h4>
      <img class="mx-auto max-w-xs object-center" :src="require('@/assets/14pro.png')"/>
    </div>
  </div>
</template>

<script>

import '@/assets/tailwind.css';

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

