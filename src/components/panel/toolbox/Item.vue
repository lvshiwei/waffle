<template>
  <drag :transfer-data="{ id, name }">
    <div class="toolbox-item">{{ name }}</div>
  </drag>
</template>

<script>
export default {
  name: "ToolboxItem",
  props: {
    id: Number,
    name: String,
  },
};
</script>

<style></style>
