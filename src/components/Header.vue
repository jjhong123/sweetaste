<template>
  <header>
    <nav class="pc_menu">
      <div class="logo">
        <a href="index.html">
          <img alt="Vue logo" src="../assets/img/logo-all-dark.png" />
        </a>
      </div>
      <ul>
        <li>
          <router-link to="/">Home</router-link>
        </li>
        <li>
          <router-link to="/product">甜點</router-link>
        </li>
        <li>
          <router-link to="/login">登入</router-link>
        </li>
        <li>
          <router-link to="/cart">
            <i class="fas fa-shopping-cart"></i>
          </router-link>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {};
</script>

<style></style>
