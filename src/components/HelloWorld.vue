<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <p>{{ value }}</p>
    <input v-model="value" />
  </div>
</template>

<script lang="ts">
export default {
  data() {
    return {
      msg: "You Did It!",
      value: "",
    };
  },
};
</script>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    display: block;
    text-align: left;
  }
}
</style>
