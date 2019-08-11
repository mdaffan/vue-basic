<template>
  <div id="app">
    <div class="container">
      <addTodo />
      <FilterTodos />
      <Todos />
    </div>
  </div>
</template>

<script>
import Todos from "./components/Todos.vue";
import addTodo from "./components/addTodo";
import FilterTodos from "./components/FilterTodos";

export default {
  name: "app",
  components: {
    Todos,
    addTodo,
    FilterTodos
  }
};
</script>

<style>
body {
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  line-height: 1.6;
  background: #e8f7f0;
}
.conatiner {
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
</style>
