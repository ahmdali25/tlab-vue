<template>
  <nav>
    <div class="nav">
      <div>
        <img src="../assets/images/brand_logo.svg" alt="TLab Logo" />
      </div>
      <div>
        <ul class="nav-list">
          <li>Company</li>
          <li>Layanan</li>
          <li>Studi Kasus</li>
          <li>Data Center</li>
        </ul>
      </div>
      <div>
        <button class="btn-nav">Hubungi Kami</button>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "BaseHeader",
};
</script>

<style scoped>
.nav {
  display: grid;
  grid-template-columns: 200px 800px 200px;
  padding: 10px;
  align-items: center;
}

.nav-list {
  list-style: none;
  font-family: "Nunito", sans-serif;
  font-size: 16px;
  display: flex;
  flex-direction: row;
  gap: 20px;
}

.nav-list li {
  cursor: pointer;
}

.btn-nav {
  font-family: "Quicksand", sans-serif;
  font-size: 16px;
  padding: 12px 24px;
  height: 48px;
  background: var(--color-primary);
  color: #ffffff;
  box-shadow: 0px 2px 8px rgba(25, 137, 104, 0.19);
  border-radius: 100px;
  border: none;
  cursor: pointer;
}
</style>
