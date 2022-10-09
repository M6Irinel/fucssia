<template>
  <main class="grow bg-gray-0" @click="clickWindow">
    <div class="container relative overflow-hidden">
      <div :class="isOpenAside ? '' : 'z-2'" class="relative grow p-3">
        <get-start />
        <container-vue />
        <width-vue />
        <height-vue />
        <margin-vue />
        <padding-vue />
        <color-vue />
        <bg-color-vue />
        <border-vue />
        <flex-vue />
      </div>
    </div>
  </main>
</template>


<script>
import store from "../store.js";
import GetStart from "./documentazioni/get-start.vue";
import ContainerVue from "./documentazioni/container-vue.vue";
import WidthVue from "./documentazioni/width-vue.vue";
import HeightVue from "./documentazioni/height-vue.vue";
import MarginVue from "./documentazioni/margin-vue.vue";
import PaddingVue from "./documentazioni/padding-vue.vue";
import ColorVue from "./documentazioni/color-vue.vue";
import BgColorVue from "./documentazioni/bg-color.vue";
import BorderVue from "./documentazioni/border-vue.vue";
import FlexVue from "./documentazioni/flex-vue.vue";

export default {
  name: "MainVue",

  components: {
    GetStart,
    ContainerVue,
    WidthVue,
    HeightVue,
    MarginVue,
    PaddingVue,
    ColorVue,
    BgColorVue,
    BorderVue,
    FlexVue,
  },

  computed: {
    isOpenAside() {
      return store.isOpenAside;
    },
  },

  methods: {
    clickWindow() {
      store.isOpenAside = false;
    },
  },
};
</script>