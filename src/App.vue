<script setup>
import LogoVue from './components/LogoVue.vue'
</script>

<template>
<div class="p-16 flex flex-col rounded flex-auto">
  <!-- shadow working -->
  <div class="shadow-2xl p-4 mx-auto w-full max-w-screen-sm">
    <img alt="Vue logo" src="./assets/logo.png" class="mx-auto"/>
  </div>
  
  <!-- shadow not working -->
  <logo-vue></logo-vue>
</div>
</template>
