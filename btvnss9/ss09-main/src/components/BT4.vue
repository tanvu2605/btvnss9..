<template>
    <div>
      <p>Bài 4</p>
      <p>Tiến độ hoàn thành</p>
      <input type="range" v-model="range" />
      <p>Value: {{ range }} %</p>
    </div>
  </template>
  
  <script setup>
  import { ref } from "vue";
  const range = ref("");
  </script>
  
  <style>
  </style>