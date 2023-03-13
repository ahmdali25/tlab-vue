<template>
  <div id="app">
    <BaseHeader />
    <main>
      <TheBanner />
    </main>
    <BaseFooter />
  </div>
</template>

<script>
import BaseHeader from "./components/BaseHeader.vue";
import BaseFooter from "./components/BaseFooter.vue";
import TheBanner from "./components/TheBanner.vue";

export default {
  name: "App",
  components: {
    BaseHeader,
    BaseFooter,
    TheBanner,
  },
};
</script>
, BaseFooter

<style>
#app {
  padding-left: 100px;
  padding-right: 100px;
}
</style>
