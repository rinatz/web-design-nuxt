<script setup lang="ts">
const route = useRoute();

useHead({
  title: "Home",
  titleTemplate: "WCB Cafe - %s",
  meta: [
    { name: "description", content: "ブレンドコーヒーとヘルシーなオーガニックフードを提供するカフェ" },
    { name: "msapplication-TileColor", content: "#da532c" },
    { name: "theme-color", content: "#ffffff" },
  ],
  link: [
    { rel: "icon", type: "image/x-icon", href: "/favicon/favicon.ico" },
    { rel: "icon", type: "image/png", sizes: "32x32", href: "/favicon/favicon-32x32.png" },
    { rel: "icon", type: "image/png", sizes: "16x16", href: "/favicon/favicon-16x16.png" },
    { rel: "apple-touch-icon", sizes: "180x180", href: "/favicon/apple-touch-icon.png" },
    { rel: "manifest", href: "/favicon/site.webmanifest" },
    { rel: "mask-icon", href: "/safari-pinned-tab.svg", color: "#5bbad5" },
    { rel: "stylesheet", href: "https://fonts.googleapis.com/css2?family=Philosopher" },
  ],
});
</script>

<template>
  <div>
    <NuxtPage />
  </div>
</template>
