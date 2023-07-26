<template>
  <main p="x4 y10" text="center teal-700 dark:gray-200">
    <ContentDoc v-slot="{ doc }">
      <ContentRenderer :value="doc" />
    </ContentDoc>
  </main>
</template>
