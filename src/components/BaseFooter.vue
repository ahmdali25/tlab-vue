<template>
  <footer>
    <div class="main-footer">
      <div>
        <h1 class="footer-title">TLab Amazing Delivering Innovation</h1>
        <div class="footer-icons-wrapper">
          <div class="footer-icon">
            <img src="../assets/images/fb.svg" alt="Icon Facebook" />
          </div>
          <div class="footer-icon">
            <img src="../assets/images/instagram.svg" alt="Icon Instagram" />
          </div>
          <div class="footer-icon">
            <img src="../assets/images/youtube.svg" alt="Icon Youtube" />
          </div>
        </div>
        <p class="footer-copyright">
          2010 - {{ getCurrentYear }} &copy; TLab. All rights reserved.
        </p>
      </div>
      <div class="footer-list-wrapper">
        <p class="footer-list-title">Company</p>
        <ul class="footer-list">
          <li class="list">About</li>
          <li class="list">Career</li>
          <li class="list">Clients</li>
          <li class="list">Logo</li>
          <li class="list">Brand Identity</li>
          <li class="list">Article</li>
          <li class="list">Studi Kasus</li>
          <li class="list">Kontak</li>
        </ul>
      </div>
      <div class="footer-list-wrapper">
        <p class="footer-list-title">Layanan</p>
        <ul class="footer-list">
          <li class="list">IT Managed Services</li>
          <li class="list">IT Consultant</li>
          <li class="list">IT Training</li>
          <li class="list">Big Data</li>
          <li class="list">Artificial Intelligent</li>
          <li class="list">Cloud Computing</li>
          <li class="list">Internet Of Things</li>
          <li class="list">Web Development</li>
          <li class="list">Mobile App Development</li>
          <li class="list">System Integration</li>
          <li class="list">System Information</li>
        </ul>
      </div>
      <div class="footer-list-wrapper">
        <p class="footer-list-title">Kontak</p>
        <ul class="footer-list">
          <li class="list list-company list-bold">
            PT. Teknologi Kode Indonesia contact@tlab.co.id
          </li>
          <li class="list list-custom">
            Head Office <br />
            Jl Tanjung No.126, Sorosutan, Umbulharjo, Yogyakarta - 55162
          </li>
          <li class="list">
            <div class="list-wrapper">
              <img src="../assets/images/phone.svg" alt="Icon Phone" />
              <span>(0274) - 2870394</span>
            </div>
          </li>
          <li class="list list-custom">
            Jakarta Office <br />
            SOHO Pancoran Unit S-1210 Jl. Let. Jend. MT. Haryono Kav 2-3
            Pancoran, Jakarta Selatan 12810
          </li>
          <li class="list">
            <div class="list-wrapper">
              <img src="../assets/images/phone.svg" alt="Icon Phone" />
              <span>(0274) - 2870394</span>
            </div>
          </li>
        </ul>
      </div>
    </div>
    <div class="footer-half-circle"></div>
  </footer>
</template>

<script>
export default {
  name: "BaseFooter",
  computed: {
    getCurrentYear() {
      return new Date().getFullYear();
    },
  },
};
</script>

<style scoped>
footer {
  position: relative;
  margin-left: -105px;
  margin-right: -105px;
  background-color: #f7fcff;
  color: var(--text-primary);
}

.main-footer {
  display: grid;
  grid-template-columns: 350px 220px 270px 280px;
  padding-top: 80px;
  padding-bottom: 10px;
  padding-left: 120px;
  padding-right: 120px;
}

.footer-title {
  line-height: 150%;
  font-family: "Quicksand", sans-serif;
}

.footer-copyright {
  font-weight: 400;
  font-size: 14px;
  font-family: "Nunito", sans-serif;
}

.footer-icons-wrapper {
  margin-top: -10px;
  margin-bottom: 20px;
  display: grid;
  grid-template-columns: 30px 30px 30px;
  gap: 15px;
}

.footer-icon {
  display: flex;
  justify-content: center;
}

.footer-list-wrapper {
  padding-top: 25px;
}

.footer-list-title {
  margin-left: 40px;
  font-weight: 700;
  font-size: 14px;
  font-family: "Quicksand", sans-serif;
  color: var(--text-primary);
  opacity: 0.5;
}

.footer-list {
  list-style: none;
}

.footer-list .list {
  line-height: 40px;
  font-size: 16px;
  font-weight: 400;
  font-family: "Nunito", sans-serif;
}

.footer-list .list .list-wrapper {
  display: flex;
  flex-direction: row;
  align-content: center;
  gap: 10px;
}

.footer-list .list-company {
  font-family: "Quicksand", sans-serif !important;
}

.footer-list .list-bold {
  font-weight: 700;
}

.footer-list .list-custom {
  margin-top: 20px;
}

.footer-half-circle {
  position: absolute;
  width: 325px;
  height: 305px;
  top: 59.79%;
  bottom: -31.78%;
  background: #5a5a5a;
  opacity: 0.1;
  border-radius: 0 225px 0 0;
}
</style>
