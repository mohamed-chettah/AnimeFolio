<script setup lang="ts">

onMounted(() => {
  const data = $fetch('http://backend.test/user')
  console.log(data)
})


</script>

<template>
  <div class="flex justify-center items-center">
    <h1>AnimeFolio</h1>

  </div>
</template>

<style scoped>

</style>