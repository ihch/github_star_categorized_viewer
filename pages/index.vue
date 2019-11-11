<template>
  <div class="container">
    <Header />
    <Inputform />
  </div>
</template>

<script>
import Inputform from '~/components/Inputform.vue';
import Header from '~/components/Header.vue';

export default {
  components: {
    Inputform,
    Header
  }
}
</script>

<style>
</style>
