<template>
  <div id="app">
    <BaseHeader />
    <main>
      <TheBanner />
      <TheProject />
      <TheConnect />
    </main>
    <BaseFooter />
  </div>
</template>

<script>
import BaseHeader from "./components/BaseHeader.vue";
import BaseFooter from "./components/BaseFooter.vue";
import TheBanner from "./components/TheBanner.vue";
import TheProject from "./components/TheProject.vue";
import TheConnect from "./components/TheConnect.vue";

export default {
  name: "App",
  components: {
    BaseHeader,
    BaseFooter,
    TheBanner,
    TheProject,
    TheConnect,
  },
};
</script>

<style>
#app {
  padding-left: 100px;
  padding-right: 100px;
}
</style>
