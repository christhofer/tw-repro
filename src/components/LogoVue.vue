<script setup>
</script>

<template>
<div>
  <!-- not working, eventhough .someclass is not used -->
  <div class="shadow-2xl p-4 mx-auto w-full max-w-screen-sm">
    <img alt="Vue logo" src="../assets/logo.png" class="mx-auto"/>
  </div>
</div>
</template>
<!-- run `npm run dev`, and uncomment this style -->
<!-- The shadow should disappear eventhough .someclass is not used -->
<!-- Recomment again, and vite will show error overlay -->
<!-- <style lang="postcss" scoped>
.someclass {
  @apply shadow;
}
</style> -->