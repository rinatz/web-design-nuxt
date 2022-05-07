<template>
  <article>
    <header class="post-info">
      <h2 class="post-title">店内ギャラリーの絵が新しくなりました</h2>
      <p class="post-date">3/30 <span>2022</span></p>
      <p class="post-cat">カテゴリー: お店の紹介</p>
    </header>

    <img src="/img/shop.jpeg" />

    <p>
      体に優しい自然食を提供する、WCB CAFE。無添加の食材を利用したメニューが特徴です。
      おいしいブレンドコーヒーとヘルシーなオーガニックフードで体の内側から癒やされてください。
      体に優しい自然食を提供する、WCB CAFE。無添加の食材を利用したメニューが特徴です。
      おいしいブレンドコーヒーとヘルシーなオーガニックフードで体の内側から癒やされてください。
      体に優しい自然食を提供する、WCB CAFE。無添加の食材を利用したメニューが特徴です。
      おいしいブレンドコーヒーとヘルシーなオーガニックフードで体の内側から癒やされてください。
    </p>
    <p>体に優しい自然食を提供する、WCB CAFE。</p>
  </article>
</template>

<style scoped>
article {
  width: 50%;
}

.post-info {
  position: relative;
  padding-top: 4px;
  margin-bottom: 40px;
}

.post-date {
  background: #0bd;
  border-radius: 50%;
  color: #fff;
  width: 100px;
  height: 100px;
  font-size: 1.625rem;
  text-align: center;
  position: absolute;
  top: 0;
  padding-top: 10px;
}

.post-date span {
  font-size: 1rem;
  border-top: 1px rgba(255, 255, 255, 0.5) solid;
  padding-top: 6px;
  display: block;
  width: 60%;
  margin: 0 auto;
}

.post-title {
  font-family: "Yu Mincho", "YuMincho", serif;
  font-size: 2rem;
  font-weight: normal;
}

.post-title, .post-cat {
  margin-left: 120px;
}

@media (max-width: 600px) {
  article {
    width: 100%;
  }

  .post-info {
    margin-bottom: 30px;
  }

  .post-date {
    width: 70px;
    height: 70px;
    font-size: 1rem;
  }

  .post-date span {
    font-size: 0.875rem;
    padding-top: 2px;
  }

  .post-title {
    font-size: 1.375rem;
  }

  .post-cat {
    font-size: 0.875rem;
    margin-top: 10px;
  }

  .post-title, .post-cat {
    margin-left: 80px;
  }
}
</style>
