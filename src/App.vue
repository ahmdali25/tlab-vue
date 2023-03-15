<template>
  <div id="app">
    <BaseHeader />
    <router-view></router-view>
    <BaseFooter />
  </div>
</template>

<script>
import BaseHeader from "./components/BaseHeader.vue";
import BaseFooter from "./components/BaseFooter.vue";

export default {
  name: "App",
  components: {
    BaseHeader,
    BaseFooter,
  },
};
</script>

<style>
#app {
  padding-left: 100px;
  padding-right: 100px;
}
</style>
