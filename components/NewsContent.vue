<template>
  <div class="news-contents wrapper">
    <NewsArticle />
    <NewsSideBar />
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
</style>
