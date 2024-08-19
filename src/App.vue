<script setup lang="ts">
   import MyHeader from './components/Header.vue';
   import MyFooter from './components/Footer.vue';
</script>

<template>
  <my-header/>
  <router-link to="/">Home</router-link>
  <router-link to="/about">About</router-link>
  <router-link to="/contact">Contact</router-link>
  <main>
  <router-view />

  </main>

  <my-footer/>

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
