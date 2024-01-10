<script setup>
import { RouterView } from 'vue-router'
import TodoHeader from './components/TodoHeader.vue';
</script>

<template>
  <TodoHeader />

  <RouterView />
</template>



<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Rubik:wght@300&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Rubik', sans-serif;
}

.container {
  max-width: 1100px;
  margin: 0 auto;
}
</style>