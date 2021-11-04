<template>
  <div class="todo-list">
    <!-- TaskItems -->
    <TaskItems />
  </div>
</template>
<script>
import TaskItems from "./TaskItems.vue";
export default {
  name: "TaskList",
  components: {
    TaskItems,
  },
};
</script>
<style></style>
