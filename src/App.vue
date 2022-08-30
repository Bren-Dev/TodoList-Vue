<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import ButtonsTop from './components/ButtonsTop.vue'
import Header from './components/Header.vue';
import AddTask from './components/AddTask.vue';
import WrapperElements from './components/WrapperElements.vue';
</script>

<template>
  <div class="container">
    <div class="wrapperTodoList">
      <Header />
      <ButtonsTop />
      <WrapperElements />
      <AddTask />
    </div>
  </div>
</template>

<style scoped>
  .container{
 background-color: #eff2f7;
  display: flex;
  justify-content: center;
  align-items: flex-start;
  width: 100vw;
  min-height: 100vh;
}

.wrapperTodoList{
  width: 40%;
  margin: 2rem 0;
}

</style>
