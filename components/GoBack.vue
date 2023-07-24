<script setup lang='ts'>
const router = useRouter()
</script>

<template>
  <div>
    <div
      class="m-3 text-sm btn"
      @click="router.back()"
    >
      Back
    </div>

    <NuxtLink
      class="m-3 text-sm btn"
      to="/"
    >
      Home
    </NuxtLink>
  </div>
</template>
