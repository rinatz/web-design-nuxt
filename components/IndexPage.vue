<template>
  <div id="home" class="big-bg">
    <HeaderContent />
    <div class="home-content wrapper">
      <h2 class="page-title">We'll Make Your Day</h2>
      <p>おしゃれなカフェで癒やされてみませんか？無添加の食材で体の中からリフレッシュ。</p>
      <a class="button" href="/menu">メニューを見る</a>
    </div>
  </div>
</template>

<style scoped>
#home {
  background-image: url("/img/coffee.jpeg");
  min-height: 100vh;
}

.big-bg {
  background-size: cover;
  background-position: center top;
  background-repeat: no-repeat;
}

.home-content {
  text-align: center;
  margin-top: 10%;
}

.home-content p {
  font-size: 1.125rem;
  margin: 10px 0 42px;
}

.page-title {
  font-size: 5rem;
  font-family: "Philosopher", serif;
  text-transform: none;
  font-weight: normal;
}

.button {
  font-size: 1.375rem;
  background: #0bd;
  color: #fff;
  border-radius: 5px;
  padding: 18px 32px;
}

@media (max-width: 600px) {
  .page-title {
    font-size: 2.5rem;
  }

  .home-content {
    margin-top: 20%;
  }
}
</style>
