<template>
  <div class="aside">
    <Toolbox />
  </div>
</template>

<script>
import Toolbox from "../panel/toolbox/Index";

export default {
  name: "Asider",
  components: { Toolbox },
};
</script>

<style scoped>
.aside {
  border-right: 0.5px solid #e6e6e6;
  height: 100%;
}
</style>
