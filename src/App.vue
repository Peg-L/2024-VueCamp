<script setup>
import { ref } from 'vue'
const num = ref(0)
</script>

<template>
  <div class="d-flex">
    <button type="button" @click="num--">-</button>
    <span class="px-10">
      {{ num }}
    </span>
    <button type="button" @click="num++">+</button>
  </div>
</template>

<style scoped>
.d-flex {
  display: flex;
}

.px-10 {
  padding: 0 40px;
}
</style>
