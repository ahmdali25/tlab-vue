<template>
  <section class="connect-section">
    <div class="connect">
      <div class="connect-title-wrapper">
        <h1 class="connect-title">
          Connect & <br />
          Collaborate
        </h1>
      </div>
      <div class="connect-detail-wrapper">
        <p class="connect-detail">
          Integritas dan kreativitas menjadi kunci dalam membangun produk
          digital terbaik untuk bisnis Anda
        </p>
        <div class="connect-navigation-wrapper">
          <span class="connect-navigation">Lihat Semua Layanan TLab</span>
          <img src="../assets/images/arrow.svg" alt="Icon Arrow" />
        </div>
      </div>
    </div>
    <div class="testimonial">
      <div class="testimonial-card testimonial-card-secondary">
        <p class="testimonial-card-detail">
          Our experience tells us it's better this way. Not only because it is
          more efficient - the outcome is simply much better.
        </p>
        <div class="testimonial-assets">
          <img
            class="testimonial-assets-image"
            src="../assets/images/assets-testimonial1.svg"
            alt="Testimonial"
          />
        </div>
        <div class="testimonial-partner">
          <div>
            <img
              class="testimonial-partner-icon"
              src="../assets/images/icon-avatar.png"
              alt="Icon"
            />
          </div>
          <div>
            <p class="testimonial-partner-name">Hamdan Hamedan</p>
            <p class="testimonial-partner-position">CEO of Kesan Indonesia</p>
          </div>
        </div>
      </div>
      <div class="testimonial-card testimonial-card-tertiary">
        <p class="testimonial-card-detail">
          Sejak akhir 2012, mulai dari konsep POS sederhana. Terus berkembang
          memenuhi kebutuhan. Dengan Tlab sistem dapat bertumbuh sesuai
          kebutuhan.
        </p>
        <div class="testimonial-assets">
          <img
            class="testimonial-assets-image"
            src="../assets/images/assets-testimonial2.svg"
            alt="Testimonial"
          />
        </div>
        <div class="testimonial-partner">
          <div>
            <img
              class="testimonial-partner-icon"
              src="../assets/images/icon-avatar.png"
              alt="Icon"
            />
          </div>
          <div>
            <p class="testimonial-partner-name">Hamdan Hamedan</p>
            <p class="testimonial-partner-position">CEO of Kesan Indonesia</p>
          </div>
        </div>
      </div>
      <div class="testimonial-card testimonial-card-primary">
        <p class="testimonial-card-detail">
          Kreativitas, tanggung jawab, serta komunikasi yang andal menjadi kunci
          kelancaran kerjasama kami bersama TLab dalam membangun aplikasi
          Anterin.
        </p>
        <div class="testimonial-assets">
          <img
            class="testimonial-assets-image"
            src="../assets/images/assets-testimonial3.svg"
            alt="Testimonial"
          />
        </div>
        <div class="testimonial-partner">
          <div>
            <img
              class="testimonial-partner-icon"
              src="../assets/images/icon-avatar.png"
              alt="Icon"
            />
          </div>
          <div>
            <p class="testimonial-partner-name">Hamdan Hamedan</p>
            <p class="testimonial-partner-position">CEO of Anterin</p>
          </div>
        </div>
      </div>
    </div>
    <div class="clients">
      <div class="clients-logo">
        <div>
          <img src="../assets/images/google.svg" alt="Google" />
        </div>
        <div>
          <img src="../assets/images/jaya-motor.svg" alt="Jaya Motor" />
        </div>
        <div>
          <img src="../assets/images/suhu.svg" alt="Suhu" />
        </div>
        <div>
          <img src="../assets/images/anterin.svg" alt="Anterin" />
        </div>
        <div>
          <img src="../assets/images/kesan.svg" alt="Kesan" />
        </div>
        <div>
          <img src="../assets/images/ipb.svg" alt="IPB" />
        </div>
      </div>
      <div class="clients-logo clients-logo-two">
        <div>
          <img src="../assets/images/klhk.svg" alt="KLHK" />
        </div>
        <div>
          <img src="../assets/images/pemprov.svg" alt="Pemprov" />
        </div>
        <div>
          <img src="../assets/images/ugm.svg" alt="UGM" />
        </div>
        <div>
          <img src="../assets/images/gojek.svg" alt="Gojek" />
        </div>
        <div>
          <img src="../assets/images/grab.svg" alt="Grab" />
        </div>
        <div>
          <img src="../assets/images/uber.svg" alt="Uber" />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "TheConnect",
};
</script>

<style scoped>
.connect-section {
  margin-left: -105px;
  margin-right: -105px;
  background-color: #f7fcff;
}

.connect {
  padding-left: 120px;
  padding-right: 120px;
  padding-top: 40px;
  padding-bottom: 40px;
  display: grid;
  grid-auto-flow: column;
  grid-auto-columns: 40% 60%;
  gap: 10px;
}

.connect-title {
  font-family: "Quicksand";
  font-weight: 700;
  font-size: 32px;
  line-height: 150%;
  color: var(--text-primary);
  margin-bottom: -10px;
}

.connect-detail-wrapper {
  width: 95%;
}

.connect-detail {
  font-family: "Nunito Sans";
  font-weight: 400;
  font-size: 18px;
  line-height: 178%;
  color: var(--text-primary);
}

.connect-navigation-wrapper {
  display: flex;
  align-items: center;
  gap: 10px;
  cursor: pointer;
}

.connect-navigation {
  font-family: "Quicksand";
  font-weight: 700;
  font-size: 16px;
  line-height: 180.5%;
  letter-spacing: 0.005em;
  color: var(--text-tertiary);
}

.testimonial {
  display: flex;
  flex-direction: row;
  gap: 32px;
  padding-left: 120px;
  padding-right: 120px;
}

.testimonial-card {
  position: relative;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  border-radius: 8px;
  padding: 31px 23px;
  height: 564px;
  width: 30%;
}

.testimonial-card-primary {
  background: var(--color-primary);
}

.testimonial-card-secondary {
  background: var(--color-secondary);
}

.testimonial-card-tertiary {
  background: var(--color-tertiary);
}

.testimonial-card-detail {
  font-family: "Quicksand";
  font-weight: 700;
  font-size: 24px;
  line-height: 150%;
  color: #ffffff;
}

.testimonial-assets {
  position: absolute;
  bottom: 0;
  top: 71%;
  left: 0;
  right: 0;
}

.testimonial-assets-image {
  width: 100%;
  height: 189px;
}

.testimonial-partner {
  position: absolute;
  display: flex;
  flex-direction: row;
  gap: 10px;
  align-items: center;
  bottom: 0;
  top: 85%;
  left: 0;
  right: 0;
  background: #ffffff;
  width: 62%;
  height: 8%;
  padding: 24px;
  border-top-right-radius: 8px;
}

.testimonial-partner-icon {
  width: 53px;
}

.testimonial-partner-name {
  font-family: "Nunito Sans";
  font-weight: 400;
  font-size: 16px;
  letter-spacing: 0.005em;
  color: var(--text-primary);
}

.testimonial-partner-position {
  font-family: "Nunito Sans";
  font-weight: 400;
  font-size: 14px;
  letter-spacing: 0.005em;
  margin-top: -12px;
}

.clients {
  background: #ffffff;
  padding-bottom: 100px;
  margin-top: -172px;
}

.clients-logo {
  padding-top: 240px;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 38px;
}

.clients-logo-two {
  padding-top: 43px;
}
</style>
