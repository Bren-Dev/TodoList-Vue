<template>
  <div class="container">
    <div class="wrapperTodoList">
      <div class="header">
        <p class="todoParagraph">
          My Todo List
        </p>
        <p class="doneParagraph">
          1 more to do,
          2 done
        </p>
      </div>
      
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
      
    
      <div class="header">
        <input placeholder="What needs to be done">
        <div class="buttonAdd">
          Add Task
        </div>
      </div>
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

.header{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.todoParagraph{
font-size: 40px;
  color: #3b3a36;
}

.doneParagraph{
font-size: 15px;
  color: #958e86;
}

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

.buttonAdd{
      border: 1px solid #18a1b4;
  border-radius: 3px;
  background-color: transparent;
  color: #18a1b4;
  padding: 8px;
  cursor: pointer;
  transition: all 0.5s;
}

.buttonAdd:hover{
 color: blue;
}

</style>
 