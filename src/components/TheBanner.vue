<template>
  <section class="banner">
    <div class="banner-title-wrapper">
      <h1 class="banner-title">
        Dapatkan solusi digital terbaik untuk mengembangkan bisnis Anda
      </h1>
    </div>
    <div class="banner-detail-wrapper">
      <p class="banner-detail">
        Jadikan bisnis semakin berkembang dengan pemilihan teknologi yang tepat
        dan andal
      </p>
    </div>
    <div class="banner-img-wrapper">
      <img class="banner-img" src="../assets/images/banner.svg" alt="Banner" />
    </div>
  </section>
</template>

<script>
export default {
  name: "TheBanner",
};
</script>

<style scoped>
.banner {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.banner-title-wrapper {
  margin-top: 50px;
  display: flex;
  flex-direction: row;
  justify-content: center;
}

.banner-title {
  text-align: center;
  font-weight: 700;
  font-size: 48px;
  font-family: "Quicksand", sans-serif;
  line-height: 150%;
  color: #5a5a5a;
  width: 74.5%;
}

.banner-detail-wrapper {
  margin-top: -20px;
  display: flex;
  flex-direction: row;
  justify-content: center;
}

.banner-detail {
  text-align: center;
  font-weight: 400;
  font-size: 24px;
  font-family: "Nunito", sans-serif;
  line-height: 150%;
  color: #5a5a5a;
  width: 70%;
}

.banner-img-wrapper {
  display: flex;
  flex-direction: row;
  justify-content: center;
}

.banner-img {
  width: 80%;
}
</style>
