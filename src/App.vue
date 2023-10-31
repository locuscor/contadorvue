<script setup>
import {ref} from "vue";
var counter = ref(0);

</script>

<template>
  <div>
    <h1>{{ counter }}</h1>
    <button @click="--counter">-</button>
    <button @click="++counter">+</button>
  </div>
</template>

<style scoped>

</style>