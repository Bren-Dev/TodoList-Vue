<script setup lang="ts">
</script>

<template>
  <div class="wrapperElementsTodo">
    <h2 class="titleTask">
      oi
    </h2>
    <div class="divIcons">
      <div class="iconExclamation">
        !
      </div>
      <div class="iconTrash">
        x
      </div>
    </div>
  </div>
</template>

<style scoped>
.titleTask{
  font-size: 1rem;
  font-weight: 500;
  color: #000;
}

.divIcons{
     display: flex;
}

.iconExclamation{
  border: green 1px solid;
  padding: 5px;
  margin-right: 10px;
  cursor: pointer;
  border-radius: 2px;
      color: green;
}

.iconTrash{

   border: red 1px solid;
  padding: 5px;
  cursor: pointer;
  border-radius: 2px;
  color: red;
}

.wrapperElementsTodo{
    width: 100%;
    background-color: white;
    border-radius: 3px;
    border: 1px solid #D1D2D6;
    margin-top: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 16px 20px;
}
</style>
