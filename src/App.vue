<template>
  <div id="app">
    <BaseHeader />
  </div>
</template>

<script>
import BaseHeader from "./components/BaseHeader.vue";

export default {
  name: "App",
  components: {
    BaseHeader,
  },
};
</script>

<style>
#app {
  padding-left: 100px;
  padding-right: 100px;
}
</style>
