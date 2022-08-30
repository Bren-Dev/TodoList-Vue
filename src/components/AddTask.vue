<template>
  <div class="header">
    <input placeholder="What needs to be done">
    <div class="buttonAdd">
      Add Task
    </div>
  </div>
</template>

<style>
  .header {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .buttonAdd {
    border: 1px solid #18a1b4;
    border-radius: 3px;
    background-color: transparent;
    color: #18a1b4;
    padding: 8px;
    cursor: pointer;
    transition: all 0.5s;
  }

  .buttonAdd:hover {
    color: blue;
  }
</style>
