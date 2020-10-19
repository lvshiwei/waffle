<template>
  <div class="whiteboard">
    <drop @drop="handleDrop" class="drop"> </drop>
  </div>
</template>

<script>
export default {
  name: "Whiteboard",
  methods: {
    handleDrop({ name }) {
      alert(name);
    },
  },
};
</script>

<style lang="stylus" scoped>
.whiteboard{
  width: 100%;
  height:100%;

  .drop{
    height : 100%;
  }
}
</style>
