<template>
  <header class="page-header wrapper">
    <h1>
      <a href="/">
        <img class="page-header__logo" src="/img/logo.png" alt="ロゴ" />
      </a>
    </h1>

    <nav>
      <ul class="page-header__nav">
        <li><a href="/news">News</a></li>
        <li><a href="/menu">Menu</a></li>
        <li><a href="/contact">Contact</a></li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
.page-header {
  display: flex;
  justify-content: space-between;
}

.page-header__logo {
  width: 70px;
  margin-top: 20px;
}

.page-header__nav {
  display: flex;
  font-size: 1.25rem;
  text-transform: uppercase;
  margin-top: 34px;
  list-style: none;
}

.page-header__nav li {
  margin-left: 36px;
}

.page-header__nav a {
  color: #432;
}

.page-header__nav a:hover {
  color: #0bd;
}

@media (max-width: 600px) {
  .page-header {
    flex-direction: column;
    align-items: center;
  }

  .page-header__nav {
    font-size: 1rem;
    margin-top: 10px;
  }

  .page-header__nav li {
    margin: 0 20px;
  }
}
</style>
