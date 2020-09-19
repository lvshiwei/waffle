<template>
  <el-menu
    router
    :default-active="$route.path"
    class="el-menu-demo"
    mode="horizontal"
  >
    <el-menu-item index="/">首页</el-menu-item>
    <el-menu-item index="2-1">
      功能1
    </el-menu-item>
    <el-menu-item index="2-2"> 选项2</el-menu-item>
    <el-menu-item index="2-3">
      <i class="el-icon-setting"></i> 设置
    </el-menu-item>
  </el-menu>
</template>

<script>
export default {
  name: "Navigator",
};
</script>

<style scoped>
.el-menu {
  border-bottom: 0px !important;
}
</style>
