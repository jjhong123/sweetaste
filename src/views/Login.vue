<template>
  <div>
    <Header />
    <div class="login">
      <div class="container">
        <!-- Left -->
        <div class="left">
          <h2>會員登入</h2>
          <div class="my_account">
            <!-- <label for="user_id"><i class="material-icons">person</i></label> -->
            <span class="icon"><i class="fas fa-user"></i></span>
            <input
              type="text"
              class="text"
              placeholder="電子信箱/手機號碼"
              id="user_id"
            />
          </div>
          <div class="my_password">
            <!-- <label for="password"><i class="material-icons">vpn_key</i></label> -->
            <span class="icon"><i class="fa fa-search"></i></span>
            <input
              type="password"
              placeholder="請輸入使用者密碼"
              id="password"
            />
          </div>
          <div class="checkbox">
            <input type="checkbox" id="checkbox" />
            記住我
            <!-- <label for="checkbox">{{ checked }}</label> -->
          </div>
          <div class="clearfix"></div>

          <div class="login">登入帳號</div>
        </div>
        <!-- Right -->
        <div class="right">
          <div class="title"><p>連結社群帳號</p></div>
          <div class="platform">
            <img src="../assets/img/facebook.png" alt="facebook" />
          </div>
          <div class="platform">
            <img src="../assets/img/google.png" alt="google" />
          </div>
          <div class="platform">
            <img src="../assets/img/yahoo.png" alt="yahoo" />
          </div>
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>
<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Login",
  components: {
    Header,
    Footer,
  },
};
</script>
