<script setup>

    const props = defineProps({
        eventname: String,
        eventicon: String,
    })
</script>

<template>
  <div class="header" style="grid-column: span 5">
    <img style="grid-column: span 1"/>
    <h1 style="grid-column: span 3">{{eventname}}</h1>
    <img style="grid-column: span 1"/>
  </div>
</template>

<style scoped>
</style>