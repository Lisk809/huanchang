<script setup lang="ts">
import Card from "./components/Card.vue";
import Nav from "./components/Nav.vue";
</script>

<template>
  <Nav />
  <div>
    <img src="/logo.png" class="logo" alt="Huanchang logo" />
  </div>
  <Card />
  <div class="footer">
    <a href="https://beian.miit.gov.cn">沪 ICP 备 2022018614 号 - 1</a>
  </div>
</template>

<style scoped>
.logo {
  height: 15em;
  padding: 1.5em;
  will-change: filter;
  transform: translateX(20px) translateY(60px);
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #0b242b);
}
.footer {
  color: #888;
  position: absolute;
  bottom: 5px;
  width: 100vw;
  text-align: center;
}
</style>
