<script setup lang="ts">
onMounted(() => {
  const script = document.createElement("script");
  script.setAttribute("src", "https://platform.twitter.com/widgets.js");
  document.getElementById("twitter-widget").appendChild(script);
});
</script>

<template>
  <section id="sns">
    <div class="wrapper">
      <div class="twitter">
        <h3 class="sub-title">Twitter</h3>
        <a class="twitter-timeline" data-height="315" href="https://twitter.com/TwitterJP?ref_src=twsrc%5Etfw">
          Tweets by TwitterJP
        </a>
        <div id="twitter-widget"></div>
      </div>

      <div class="youtube">
        <h3 class="sub-title">YouTube</h3>
        <iframe title="YouTube video player" src="https://www.youtube.com/embed/nYYpxy5utbM" width="560" height="315"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen>
        </iframe>
      </div>
    </div>
  </section>
</template>

<style scoped>
#sns {
  background: #faf7f0;
  padding: 4% 0;
}

#sns .wrapper {
  display: flex;
  justify-content: flex-start;
  gap: 5rem;
}

#sns .sub-title {
  margin-bottom: 30px;
  border-bottom: 2px #0bd solid;
}

.twitter {
  flex-grow: 1;
}

.youtube {
  flex-grow: 2;
}

.youtube iframe {
  width: 100%;
}

.youtube iframe {
  width: 100%;
}

@media (max-width: 600px) {
  #sns .wrapper {
    margin-top: 1rem;
    flex-direction: column;
    gap: 1rem;
  }
}
</style>
