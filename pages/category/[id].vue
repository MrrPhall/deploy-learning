<template>
  <div>
    <h1>Hi {{ route.params.id }}</h1>
  </div>
</template>

<script lang="ts" setup>
  const route = useRoute();
</script>

<style>

</style>