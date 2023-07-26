<template>
  <main p="x4 y10" text="center teal-700 dark:gray-200">
    <ContentDoc>
      <template #not-fount>
        <div text-4xl>
          <div i-carbon-warning inline-block />
        </div>
        <div>Not found</div>
        <GoBack />
      </template>
    </ContentDoc>
  </main>
</template>
