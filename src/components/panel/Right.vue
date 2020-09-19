<template>
  <el-drawer
    class="right-panel"
    title="Properties"
    :modal="false"
    :visible.sync="visible"
  >
    <span>contents here!</span>
  </el-drawer>
</template>

<script>
export default {
  name: "RightPanel",
  data() {
    return {
      visible: true,
    };
  },
};
</script>

<style></style>
