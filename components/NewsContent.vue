<template>
  <div class="news-contents wrapper">
    <NewsArticle class="article" />
    <NewsSideBar class="aside" />
    <img class="ad" src="~/assets/img/wagashi.jpeg" alt="新メニュー登場" />
  </div>
</template>

<style scoped>
.news-contents {
  display: flex;
  justify-content: space-between;
  margin-bottom: 50px;
}

@media (max-width: 600px) {
  .news-contents {
    flex-direction: column;
  }
}

.ad {
  order: 1;
}

.article {
  order: 2;
}

.aside {
  order: 3;
}
</style>
