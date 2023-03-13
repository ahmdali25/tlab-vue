<template>
  <div id="app">
    <BaseHeader />
    <main>
      <TheBanner />
    </main>
  </div>
</template>

<script>
import BaseHeader from "./components/BaseHeader.vue";
import TheBanner from "./components/TheBanner.vue";

export default {
  name: "App",
  components: {
    BaseHeader,
    TheBanner,
  },
};
</script>

<style>
#app {
  padding-left: 100px;
  padding-right: 100px;
}
</style>
