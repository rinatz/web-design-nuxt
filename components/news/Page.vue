<script setup lang="ts">
useHead({
  title: "News",
});
</script>

<template>
  <div>
    <div id="news" class="big-bg">
      <HeaderContent />
      <div class="wrapper">
        <h2 class="page-title">News</h2>
      </div>
    </div>

    <NewsContent />
    <FooterContent />
  </div>
</template>

<style scoped>
#news {
  background-image: url("/img/coffee2.jpeg");
  height: 270px;
  margin-bottom: 40px;
}

#news .page-title {
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
  #news .page-title {
    font-size: 2.5rem;
    margin-top: 30px;
  }
}
</style>
