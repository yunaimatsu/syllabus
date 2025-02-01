<script setup>
import Header from './components/Header.vue';
import SearchBtn from './components/SearchBtn.vue';
</script>

<template>
  <Header></Header>
  <div>
    <h1>シラバス</h1>
  </div>
  <SearchBtn />
</template>

<style scoped>
body {
  margin-top: 9em;
}
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
