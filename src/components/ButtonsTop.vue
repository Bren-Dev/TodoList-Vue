
<template>
  <div class="header">
    <input
      placeholder="type to search"
    >
    <div class="wrapperButton">
      <button>
        All
      </button>
      <button>
        Active
      </button>
      <button>
        Done
      </button>
    </div>
  </div>
</template>


<style>

input{
    width: 280px;
    padding-left: 10px;
    border: 1px solid #D1D2D6;
    border-radius: 5px;
    outline: 0;
    height: 30px;
    margin: 20px 0 10px 0;
}

.header{
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.wrapperButton{
     display: inline;
}

.wrapperButton button{
 border: 1px solid ;
        border-radius: 3px;
        background-color: transparent;
        color: #737780;
        padding: 8px;
        cursor: pointer;
}



</style>
 