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
          <router-link to="/" class="router-link-exact-active router-link-active">Home</router-link>
          <!-- <a href="#/" aria-current="page" class="router-link-exact-active router-link-active">Home</a> -->
        </li>
        <li>
          <router-link to="product">甜點</router-link>
          <!-- <a href="#/product" class>甜點</a> -->
        </li>
        <li>
          <router-link to="login">登入</router-link>
          <!-- <a href="#/login" class>登入</a> -->
        </li>
        <li>
          <router-link to="cart">
            <i class="fas fa-shopping-cart" aria-hidden="true"></i>
          </router-link>

          <!-- <a href="#/cart" class>
            <i class="fas fa-shopping-cart" aria-hidden="true"></i>
          </a>-->
        </li>
      </ul>
    </nav>
    <nav class="mb_menu">
      <i class="fas fa-align-justify hamburger"></i>

      <!-- <div class="logo">
        <a href="index.html">
          <img alt="Vue logo" src="../assets/img/logo-all-dark.png" />
        </a>
      </div>-->
      <img src="../assets/img/logo-all-dark.png" alt="Logo" />
      <router-link to="/cart">
        <i class="fas fa-shopping-cart" aria-hidden="true"></i>
      </router-link>

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
      </ul>
    </nav>
  </header>
</template>

<script>
import $ from "jquery";
export default {
  created() {},
  mounted() {
    let vm = this;
    $(".hamburger").click(vm.menuHandler);
  },
  methods: {
    menuHandler() {
      $(".mb_menu ul")
        .stop()
        .slideToggle();
    }
  }
};
</script>

<style></style>
