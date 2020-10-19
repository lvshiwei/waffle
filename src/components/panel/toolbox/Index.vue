<template>
  <div class="toolbox">
    <Item v-for="i in items" v-bind="i" :key="i.id" />
  </div>
</template>

<script>
import Item from "./Item";
export default {
  name: "Toolbox",
  components: { Item },

  data() {
    return {
      items: [
        { id: 0, name: "aaaa" },
        { id: 1, name: "bbbb" },
        { id: 2, name: "cccc" },
      ],
    };
  },
};
</script>

<style scoped></style>
