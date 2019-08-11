<template>
  <div>
    Filter Todos:
    <select id="select" @change="filterTodo($event)">
      <option value="200">200</option>
      <option value="200">100</option>
      <option value="200">50</option>
      <option value="200">10</option>
    </select>
  </div>
</template>
<script>
import { mapActions } from "vuex";
export default {
  name: "FilterTodos",
  methods: mapActions(["filterTodo"])
};
</script>
<style scoped>
select {
  margin-top: 20px;
  padding: 6px;
  border: #41b883 1px solid;
}
</style>