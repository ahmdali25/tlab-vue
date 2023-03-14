<template>
  <section class="project">
    <div class="project-title-wrapper">
      <h1 class="project-title">Rangkaian Proyek Menarik TLab</h1>
    </div>
    <div class="project-wrapper">
      <div>
        <div class="project-detail-wrapper">
          <p class="project-detail">
            Integritas dan kreativitas menjadi kunci dalam membangun produk
            digital terbaik untuk bisnis Anda
          </p>
        </div>
        <div class="project-navigation-wrapper">
          <span class="project-navigation">Lihat Semua Layanan TLab</span>
          <img src="../assets/images/arrow.svg" alt="Icon Arrow" />
        </div>
        <div class="project-image">
          <div class="project-image-card">
            <h6 class="project-image-card-title">IT Managed Service</h6>
            <p
              class="project-image-card-detail project-image-card-detail-custom"
            >
              kesan.id - Kedaulatan Santri dan Kepribadian Muslim
            </p>
          </div>
          <img
            class="image"
            src="../assets/images/project-kesan.png"
            alt="Project Kesan"
          />
        </div>
      </div>
      <div class="project-image-wrapper">
        <div class="project-image">
          <div class="project-image-card project-image-card-medium">
            <h6 class="project-image-card-title">Application Development</h6>
            <p class="project-image-card-detail">
              Anterin.id <br />
              Ridesharing company
            </p>
          </div>
          <img
            class="image"
            src="../assets/images/project-anterin.png"
            alt="Project Anterin"
          />
        </div>
        <div class="project-image">
          <div class="project-image-card project-image-card-medium">
            <h6 class="project-image-card-title">Artificial Intelligence</h6>
            <p class="project-image-card-detail">
              Juru.id <br />
              Smart Parking
            </p>
          </div>
          <img
            class="image"
            src="../assets/images/project-juru.png"
            alt="Project Juru"
          />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "TheProject",
};
</script>

<style scoped>
.project {
  padding-top: 40px;
  padding-bottom: 40px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.project-wrapper {
  display: grid;
  grid-template-columns: 60% 40%;
  gap: 10px;
}

.project-title-wrapper {
  width: 30%;
}

.project-title {
  font-family: "Quicksand";
  font-weight: 700;
  font-size: 32px;
  line-height: 150%;
  color: var(--text-primary);
  margin-bottom: -10px;
}

.project-detail-wrapper {
  width: 95%;
}

.project-detail {
  font-family: "Nunito Sans";
  font-weight: 400;
  font-size: 18px;
  line-height: 178%;
  color: var(--text-primary);
}

.project-navigation-wrapper {
  display: flex;
  align-items: center;
  gap: 10px;
  cursor: pointer;
  margin-bottom: 40px;
}

.project-navigation {
  font-family: "Quicksand";
  font-weight: 700;
  font-size: 16px;
  line-height: 180.5%;
  letter-spacing: 0.005em;
  color: var(--text-tertiary);
}

.project-image-wrapper {
  display: flex;
  flex-direction: column;
  gap: 32px;
}

.project-image {
  position: relative;
}

.project-image-card {
  position: absolute;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  background: #ffffff;
  bottom: 0;
  left: 0;
  padding: 24px;
  border-radius: 0px 8px;
  width: 55%;
  height: 38%;
}

.project-image-card-medium {
  width: 56%;
  height: 30%;
}

.project-image-card-title {
  font-family: "Quicksand";
  font-weight: 700;
  font-size: 14px;
  line-height: 180.5%;
  letter-spacing: 0.005em;
  color: var(--text-primary);
}

.project-image-card-detail {
  font-family: "Quicksand";
  font-weight: 700;
  font-size: 24px;
  line-height: 150%;
  margin-top: -30px;
  color: var(--text-primary);
}

.project-image-card-detail-custom {
  width: 72%;
}

.image {
  width: 95%;
}
</style>
