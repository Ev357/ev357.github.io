<template>
  <div>{{ count }}</div>
  <button @click="count += 1">Add</button>
</template>

<script setup>
const count = ref(0);
</script>
