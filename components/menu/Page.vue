<script setup lang="ts">
useHead({
  title: "Menu",
});
</script>

<template>
  <div>
    <div id="menu" class="big-bg">
      <HeaderContent />
      <div class="menu-content wrapper">
        <h2 class="page-title">Menu</h2>
        <p>
          体に優しい自然食を提供する、WCB CAFE。無添加の食材を利用したメニューが特徴です。
          おいしいブレンドコーヒーとヘルシーなオーガニックフードで体の内側から癒やされてください。
        </p>
      </div>
    </div>

    <MenuContent />
    <FooterContent />
  </div>
</template>

<style scoped>
#menu {
  background-image: url("/img/menu-bg.jpeg");
  min-height: 100vh;
}

.big-bg {
  background-size: cover;
  background-position: center top;
  background-repeat: no-repeat;
}

.menu-content {
  max-width: 560px;
  margin-top: 10%;
}

.page-title {
  text-transform: uppercase;
  font-size: 5rem;
  font-family: "Philosopher", serif;
  font-weight: normal;
  text-align: center;
}

@media (max-width: 600px) {
  .page-title {
    font-size: 2.5rem;
    margin-top: 20%;
  }
}
</style>
