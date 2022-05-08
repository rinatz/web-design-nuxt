<script setup lang="ts">
useHead({
  title: "Contact",
});
</script>

<template>
  <div id="contact" class="big-bg">
    <HeaderContent />
    <div class="wrapper">
      <h2 class="page-title">Contact</h2>
      <ContactForm />
    </div>
  </div>

  <ContactContent />
  <FooterContent />
</template>

<style scoped>
#contact {
  background-image: url("/img/cat.jpeg");
  background-blend-mode: darken;
  background-color: rgba(0, 0, 0, 0.3);
  min-height: 100vh;
}

.big-bg {
  background-size: cover;
  background-position: center top;
  background-repeat: no-repeat;
}

.page-title {
  text-transform: uppercase;
  font-size: 5rem;
  font-family: "Philosopher", serif;
  font-weight: normal;
  text-align: left;
}

@media (max-width: 600px) {
  #contact .page-title {
    font-size: 2.5rem;
    margin-top: 30px;
  }
}
</style>
