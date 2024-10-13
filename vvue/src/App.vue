<script setup>
import Header from '@/components/HeaderLayout.vue';
import TodoCheckList from '@/components/TodoCheckList.vue';
</script>

<template>
  <div class="container">
    <Header></Header>

    <div class="content-area">
      <TodoCheckList></TodoCheckList>
    </div>
  </div>
</template>

<style lang="scss">
// @import './assets/_variables.scss';
.container {
  max-width: 360px;
  margin: 0 auto;
}
</style>
