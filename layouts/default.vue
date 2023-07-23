<script setup lang="ts">
import Footer from '~/components/Footer.vue'
</script>

<template>
  <main class="min-h-screen px-10 py-20 text-center">
    <slot />
    <div class="">
      <Footer />
    </div>
  </main>
</template>
