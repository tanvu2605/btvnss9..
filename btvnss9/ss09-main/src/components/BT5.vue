<template>
  <div>
    <p>Bài 5</p>
    <p>Giới tính :{{ gender }}</p>
    <div class="container">
      <div>
        <input type="radio" v-model="gender" name="gender" value="nam"  />
        <label for="male">Nam</label>
      </div>
      <div>
        <input type="radio" v-model="gender" name="gender" value="nữ" />
        <label for="female">Nữ</label>
      </div>
      <div>
        <input type="radio" v-model="gender" name="gender" value="gayyyy" />
        <label for="gayy">Khac</label>
      </div>
    </div>
  </div>
</template>
  
  <script setup>
import { ref } from "vue";
const gender = ref("");
</script>
  
  <style scoped>
</style>