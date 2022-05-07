<template>
  <div>
    <div id="menu" class="big-bg">
      <HeaderContent />
      <div class="wrapper">
        <h2 class="page-title">Menu</h2>
      </div>
    </div>

    <MenuContent />
    <FooterContent />
  </div>
</template>

<style scoped>
#menu {
  background-image: url("/img/menu9.jpeg");
  height: 270px;
  margin-bottom: 40px;
}

#menu .page-title {
  text-transform: uppercase;
  font-size: 5rem;
  font-family: "Philosopher", serif;
  font-weight: normal;
  text-align: center;
}

.big-bg {
  background-size: cover;
  background-position: center top;
  background-repeat: no-repeat;
}

@media (max-width: 600px) {
  #menu .page-title {
    font-size: 2.5rem;
    margin-top: 30px;
  }
}
</style>
