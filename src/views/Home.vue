<template>
  <main>
    <TheBanner />
    <TheProject />
    <TheConnect />
  </main>
</template>

<script>
import TheBanner from "../components/TheBanner.vue";
import TheProject from "../components/TheProject.vue";
import TheConnect from "../components/TheConnect.vue";

export default {
  name: "Home",
  components: {
    TheBanner,
    TheProject,
    TheConnect,
  },
};
</script>
