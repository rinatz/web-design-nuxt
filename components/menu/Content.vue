<script setup lang="ts">
const items = [
  { img: "/img/menu1.jpeg", caption: "メニュー1", class: "item big-box" },
  { img: "/img/menu2.jpeg", caption: "メニュー2", class: "item" },
  { img: "/img/menu3.jpeg", caption: "メニュー3", class: "item" },
  { img: "/img/menu4.jpeg", caption: "メニュー4", class: "item" },
  { img: "/img/menu5.jpeg", caption: "メニュー5", class: "item" },
  { img: "/img/menu6.jpeg", caption: "メニュー6", class: "item" },
  { img: "/img/menu7.jpeg", caption: "メニュー7", class: "item" },
  { img: "/img/menu8.jpeg", caption: "メニュー8", class: "item" },
  { img: "/img/menu9.jpeg", caption: "メニュー9", class: "item" },
];
</script>

<template>
  <div class="wrapper grid">
    <template v-for="item in items">
      <figure :class="item.class">
        <img :src="item.img" alt="" />
        <figcaption>{{ item.caption }}</figcaption>
      </figure>
    </template>
  </div>
</template>

<style scoped>
.grid {
  display: grid;
  gap: 26px;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  margin-top: 6%;
  margin-bottom: 50px;
}

.big-box {
  grid-column: 1 / 3;
  grid-row: 1 / 3;
}

.big-box img {
  height: 93%;
  width: 100%;
  object-fit: cover;
}

@media (max-width: 600px) {
  .big-box {
    grid-column: auto;
    grid-row: auto;
  }

  .big-box img {
    height: 100%;
  }
}
</style>
