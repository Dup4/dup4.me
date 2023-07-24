<script setup lang="ts">
import NavBar from '~/components/NavBar.vue'
</script>

<template>
  <NavBar />
  <main class="px-10 py-20 text-center">
    <slot />
    <!-- <div class="">
      <Footer />
    </div> -->
  </main>
</template>
