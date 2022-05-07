<template>
  <div class="news-contents wrapper">
    <NewsArticle class="article" />
    <NewsSideBar class="aside" />
    <img class="ad" src="/img/wagashi.jpeg" alt="新メニュー登場" />
  </div>
</template>

<style scoped>
.news-contents {
  display: flex;
  justify-content: space-between;
  margin-bottom: 50px;
}

.article {
  order: 2;
}

.aside {
  order: 3;
}

.ad {
  order: 1;
}

@media (max-width: 600px) {
  .news-contents {
    flex-direction: column;
  }

  .article {
    order: 1;
  }

  .aside {
    order: 2;
  }

  .ad {
    order: 3;
    max-height: 250px;
    object-fit: cover;
  }
}
</style>
