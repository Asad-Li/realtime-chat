<template>
  <div class="mx-5 mt-5">
    <div class="flex flex-row">
      <slot />
    </div>
    <div class="text-4xl flex flex-row justify-center">
      <footer>
        <UButton class="m-1" color="neutral" icon="si:add-fill" variant="subtle"></UButton>
        <UButton class="m-1" color="neutral" icon="si:remove-fill" variant="subtle"></UButton>
        <UButton class="m-1" color="neutral" icon="tabler:pencil" variant="subtle"></UButton>
      </footer>
      <UInput class="mt-1.5 ml-1 " ></UInput>
    </div>
  </div>
</template>

<style scoped>

</style>
<script setup lang="ts">
</script>
