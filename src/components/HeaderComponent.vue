<script setup>

</script>

<template>
  <header class="header">
    <a href=""  class="logo">
      <img src="@/assets/images/logo.svg" alt="">
    </a>
    <nav>
      <ul class="nav">
        <li class="nav-item">
          <a href="" class="nav-link">Products</a>
        </li>
        <li class="nav-item">
          <a href="" class="nav-link">Features</a>
        </li>
        <li class="nav-item">
          <a href="" class="nav-link">About</a>
        </li>
        <li class="nav-item">
          <a href="" class="nav-link">Contact</a>
        </li>
        <li class="nav-item--login">
          <a href="" class="nav-link nav-link--login">Login</a>
        </li>
        <li class="nav-item--register">
          <a href="" class="nav-link nav-link--register">Register</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
.header {
  max-width: 1202px;
  padding-right: 15px;
  padding-left: 15px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 60px;
}
.nav {
  display: flex;
  align-items: center;
  list-style-type: none;
  padding-left: 0;
  margin: 0;
}
.nav-item {
  margin-left: 32px;
}
.nav-item--login {
  margin-left: 56px;
  padding-right: 24px;
  border-right: 1px solid rgba(242,242,242,0.3);
}
.nav-item--register {
  margin-left: 24px;
}
.nav-link {
  color: var(--white);
  text-decoration: none;
  font-size: 16px;
  transition: .2s ease color;
}
.nav-link:hover {
  color: var(--blue);
}
.nav-item--login {
  font-weight: 500;
}
.nav-link--register {
  background-color: var(--blue);
  padding: 14px 32px;
  border-radius: 32px;
  font-weight: 500;
  transition: .2s ease background-color;
}
.nav-link--register:hover {
  color: var(--white);
  background-color: var(--purple);
}
</style>