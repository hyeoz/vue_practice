<script lang="ts">
export default {
  data() {
    return {
      fruits: ["banana"],
    };
  },
};
</script>

<template>
  <form id="">
    <label for="banana">
      <input
        type="checkbox"
        id="banana"
        v-model="fruits"
        value="banana"
      />BANANA
    </label>
    <label for="orange">
      <input
        type="checkbox"
        id="orange"
        v-model="fruits"
        value="orange"
      />ORANGE
    </label>
    <label for="apple">
      <input type="checkbox" id="apple" v-model="fruits" value="apple" />APPLE
    </label>
  </form>
</template>
