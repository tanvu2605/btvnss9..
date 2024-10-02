<template>
  <div>
    <p>Bài 1</p>
    <p>Email</p>
    <input type="email" v-model="email" />
    <p>Value: {{ email }}</p>
  </div>
</template>

<script setup>
import { ref } from "vue";
const email = ref("");
</script>

<style>
</style>