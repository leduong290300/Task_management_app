<template>
  <div class="todo-item">
    <div class="checker">
      <span class="checker"><input type="checkbox" /></span>
    </div>
    <span class="content">Create theme</span>
    <div class="btn-icon">
      <b-icon
        class="icon icon-edit"
        icon="pencil-square"
        variant="success"
      ></b-icon>
      <b-icon class="icon icon-trash" icon="trash" variant="danger"></b-icon>
    </div>
  </div>
</template>
<script>
export default {
  name: "TaskItems",
};
</script>
