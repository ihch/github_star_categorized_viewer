<template>
  <div class="header">
    <div class="header__title">Header Title</div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
})
</script>

<style scoped>
.header {
  display: flex;
  align-items: center;
  color: #cfd0d1;
  background-color: #24292e;
  height: 65px;
  padding: 16px;
}

.header__title {
  color: rgba(255, 255, 255, 0.9);
  font-size: 2rem;
  text-align: justify;
}
</style>
