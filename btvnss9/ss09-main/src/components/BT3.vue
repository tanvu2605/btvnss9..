<template>
    <div>
      <p>Bài 3</p>
      <p>Ngày sinh</p>
      <input type="date" v-model="date" />
      <p>Value: {{ date }}</p>
    </div>
  </template>
  
  <script setup>
  import { ref } from "vue";
  const date = ref("");
  </script>
  
  <style>
  </style>