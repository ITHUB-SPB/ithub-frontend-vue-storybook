<template>
  <header>
    Header
  </header>
</template>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-bottom: 1px solid rgba(0, 0, 0, 0.1);
  padding: 15px 20px;
  font-family: 'Nunito Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif;
}
</style>

<script lang="ts" setup>
import MyButton from '../components/Button.vue';

defineEmits<{
  (event: 'createAccount'): void;
  (event: 'login'): void;
  (event: 'logout'): void;
}>();
</script>
