<template>
  <div id="app">
    <HelloWorld msg="buraya menü gelecek" :menuItems="menuItems"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

import './assets/tailwind.css';

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data(){
    return{    
      menuItems:["Store",
                  "Mac",
                  "iPad",
                  "iPhone",
                  "Watch",
                  "Airpods",
                  "Tv / Ev",
                  "Aksesuarlar",
                  "Destek"]}


  }
 

}
</script>

