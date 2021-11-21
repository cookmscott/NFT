<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import Home from "./components/Home.vue";
</script>

<template>
  <Home />
</template>

<style>
@import "hiq/dist/hiq.min.css";

:root {
  --hiq-font-family-base: "Inconsolata", monospace;
  --hiq-max-container-width: 60rem;
}

/* Wrap Border */
body:before,
body:after {
  content: "";
  position: fixed;
  background: #522c69;
  left: 0;
  right: 0;
  height: 10px;
}
body:before {
  top: 0;
}
body:after {
  bottom: 0;
}
body {
  border-left: 10px solid #522c69;
  border-right: 10px solid #522c69;
}
</style>
