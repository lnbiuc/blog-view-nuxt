<script setup lang="ts">
const data = ref(await useFetch('https://blog.vio.vin/api/articles/title?pageNumber=1&pageSize=5'))
</script>

<template>
  <div>
    {{ data }}
  </div>
</template>

<style scoped>

</style>
