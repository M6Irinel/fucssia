<template>
  <aside
    :class="isOpenAside ? 'visible z-1' : ' invisible'"
    class="
      absolute
      top
      right
      left
      bg-gray-0-5
      transition-filter
      duration-5
      relative-lg
      visible-lg
    "
  >
    <a
      v-for="(el, i) in arrayAside"
      :key="i"
      @click="closeAside"
      :class="(i % 2 == 0) ? 'border-green-6' : 'border-violet-6'"
      class="block pl-20-lg pr-5 py-2 t-right decoration-none black bold gray-7-H border-b"
      :href="'#' + el.href"
    >
      {{ el.name }}
    </a>
  </aside>
</template>


<script>
import store from "../store.js";
import ArrayAside from "../arrays/array-aside.json";

export default {
  name: "AsideVue",

  data() {
    return {
      arrayAside: ArrayAside,
    };
  },

  computed: {
    isOpenAside() {
      return store.isOpenAside;
    },
  },

  methods: {
    closeAside() {
      store.isOpenAside = false;
    },
  },
};
</script>

<style scoped lang="scss">
.bg-gray-0-5 {
    background-color: rgb(245, 245, 245);
}
</style>