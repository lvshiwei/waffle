<template>
  <el-container>
    <el-header>
      <Header />
    </el-header>

    <el-container>
      <el-aside>
        <Aside />
      </el-aside>

      <el-main class="main">
        <slot>Nothing</slot>
      </el-main>

      <RightPanel />
    </el-container>
  </el-container>
</template>
<script>
import Header from "./Header";
import Aside from "./Asider";
import RightPanel from "../panel/Right";

export default {
  name: "Layout",
  components: {
    Header,
    Aside,
    RightPanel,
  },
};
</script>
<style scoped>
.el-header {
  padding: 0px;
}
.el-main {
  padding: 0px;
}
</style>
