<template>
  <button
    class="
      aspect-ratio-1
      rounded-full
      z-full
      fixed
      bottom-10
      right-10
      border border-violet-8
      bg-violet-6
      fs-8
      bold
      green-6
      t-shadow-5-dark
      d-none-lg
    "
    @click="isOpenAside"
  >
    ?
  </button>
</template>


<script>
import store from "../store.js";

export default {
  name: "ButtonAside",

  methods: {
    isOpenAside() {
      store.isOpenAside = !store.isOpenAside;
    },
  },
};
</script>


<style scoped lang="scss">
button {
  width: 70px;
}
</style>