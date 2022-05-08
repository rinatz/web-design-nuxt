<script setup lang="ts">
onMounted(() => {
  const script = document.createElement("script");
  script.setAttribute("src", "https://platform.twitter.com/widgets.js");
  document.getElementById("twitter").appendChild(script);
});
</script>

<template>
  <section id="sns">
    <div class="wrapper">
      <div class="sns-box">
        <h3 class="sub-title">Twitter</h3>
        <a class="twitter-timeline" data-height="315" href="https://twitter.com/TwitterJP?ref_src=twsrc%5Etfw">
          Tweets by TwitterJP
        </a>
        <div id="twitter"></div>
      </div>

      <div class="sns-box">
        <h3 id="youtube" class="sub-title">YouTube</h3>
        <iframe
          title="YouTube video player"
          src="https://www.youtube.com/embed/nYYpxy5utbM"
          width="560"
          height="315"
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

.sns-box {
  width: 30%;
}

#youtube {
  width: 560px;
}
</style>
