<script setup lang="ts">
const { data } = await useFetch('/api/hello')
</script>

<template>
  <div>
    <h1>Index Page</h1>
    
    <p>{{ data }}</p>
  </div>
</template>