<!--
 * @Author: NanNan
 * @Date: 2023-11-13 11:10:57
 * @LastEditTime: 2023-11-13 13:20:45
 * @Description: 
-->
<script setup>
import moment from 'moment';

import HelloWorld from './components/HelloWorld.vue';

console.log(moment().add(7, 'd'));
</script>

<template>
  <div>
    <a target="_blank" @click="toTopFunc">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
