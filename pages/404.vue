<script setup lang="ts">
const router = useRouter()
</script>

<template>
  <main class="x4 y10 text-center text-teal-700 dark:gray-200">
    <div class="text-4xl">
      <div class="i-carbon-warning inline-block" />
    </div>
    <div>Not found</div>
    <div>
      <button class="btn text-sm m-3 t8" @click="router.back()">
        Back
      </button>
    </div>
  </main>
</template>
