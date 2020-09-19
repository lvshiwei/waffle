<template>
  <el-row class="header">
    <el-col :span="3">
      <!-- <el-image class="logo" :src="logo" :fit="fit"></el-image> -->
      <div class="logo">LOGO</div>
    </el-col>
    <el-col :span="18"><Navigator /></el-col>
    <el-col :span="3">
      <div class="top-right"><i class="el-icon-user"></i> jack@email.com</div>
    </el-col>
  </el-row>
</template>

<script>
import Navigator from "../Navigator";
import logo from "@/assets/logo.png";

export default {
  name: "Header",
  components: {
    Navigator,
  },
  data() {
    return {
      logo,
    };
  },
};
</script>
<style lang="stylus">
.header{
  border-bottom: solid 1px #e6e6e6;
}
.logo {
  font-size: 42px;
}
.top-right{
  line-height: 60px;
  vertical-align : middle;
}
</style>
