<template>
  <div>
    <input type="text" v-model="username">
    <p>your name {{ username }}</p>
  </div>
</template>

<script lang="ts">
export default {
  data() {
    return {
      username: ""
    };
  }
}
</script>

<style scoped>
</style>
