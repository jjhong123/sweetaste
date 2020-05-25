<template>
  <div>
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Header />
    <div class="slide"></div>
    <!-- TOPIC -->
    <div class="topic_area">
      <div class="topic">
        <div class="blur_bg"></div>
        <div class="text">
          <p>本日精選</p>
        </div>
      </div>
      <div class="topic">
        <div class="blur_bg"></div>
        <div class="text">
          <p>人氣推薦</p>
        </div>
      </div>
      <div class="topic">
        <div class="blur_bg"></div>
        <div class="text">
          <p>新品上市</p>
        </div>
      </div>
    </div>
    <!-- Chose -->
    <div class="chose_area">
      <div class="contain" id="why_1">
        <div class="pic_1"></div>
        <div class="reason">
          <p>是非成敗轉頭空，滾滾長江東逝水，白髮漁樵江渚上，古今多少事，都付笑談中。</p>
          <p>青山依舊在，幾度夕陽紅。慣看秋月春風。一壺濁酒喜相逢，浪花淘盡英雄。是非成敗轉頭空，滾滾長江東逝水，白髮漁樵江渚上，古今多少事，都付笑談中。</p>
          <img src="../assets/img/lg-為什麼選擇了做甜點.png" alt />
        </div>
      </div>
    </div>
    <!-- Chose-2 -->
    <div class="chose_area">
      <div class="contain" id="why_2">
        <div class="reason">
          <p>是非成敗轉頭空，滾滾長江東逝水，白髮漁樵江渚上，古今多少事，都付笑談中。</p>
          <p>青山依舊在，幾度夕陽紅。慣看秋月春風。一壺濁酒喜相逢，浪花淘盡英雄。是非成敗轉頭空，滾滾長江東逝水，白髮漁樵江渚上，古今多少事，都付笑談中。</p>
          <img src="../assets/img/lg-為什麼一定要吃甜點.png" alt />
        </div>
        <div class="pic_2"></div>
      </div>
    </div>

    <!-- noreason -->
    <div class="noreason"></div>
    <!-- product -->
    <div class="products">
      <div class="item">
        <div class="img_box">
          <img src="../assets/img/item1.jpg" alt />
          <p class="cate">本日精選</p>
          <i class="far fa-heart"></i>
        </div>
        <div class="item_info">
          <div class="title">焦糖瑪卡龍</div>
          <div class="price">NT$ 450</div>
        </div>
        <a class="addcart" href="cart.html">加入購物車</a>
      </div>
      <div class="item">
        <div class="img_box">
          <img src="../assets/img/item2.jpg" alt />
          <p class="cate">本日精選</p>
          <i class="far fa-heart"></i>
        </div>
        <div class="item_info">
          <div class="title">焦糖瑪卡龍</div>
          <div class="price">NT$ 450</div>
        </div>
        <a class="addcart" href="cart.html">加入購物車</a>
      </div>
      <div class="item">
        <div class="img_box">
          <img src="../assets/img/item3.jpg" alt />
          <p class="cate">本日精選</p>
          <i class="far fa-heart"></i>
        </div>
        <div class="item_info">
          <div class="title">焦糖瑪卡龍</div>
          <div class="price">NT$ 450</div>
        </div>
        <a class="addcart" href="cart.html">加入購物車</a>
      </div>
    </div>
    <!-- Footer -->
    <Footer/>
    <!-- END -->
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Header,
    Footer
  }
};
</script>
