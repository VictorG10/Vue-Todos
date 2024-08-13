<script setup>
  import { RouterView } from "vue-router";
  import TodoHeader from "./components/TodoHeader.vue";
</script>

<template>
  <TodoHeader />
  <RouterView />
</template>

<style lang="scss">
  .container {
    max-width: 1100px;
    margin: 0 auto;
  }
</style>
