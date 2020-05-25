<template>
  <div>
    <Header />
    <div class="slide"></div>
    <div class="product_area">
      <div class="container">
        <div class="left">
          <div class="list">
            <ul>
              <li class="active">甜點類別</li>
              <li>所有甜點(12)</li>
              <li>本日精選(12)</li>
              <li>人氣推薦(12)</li>
              <li>新品上市(12)</li>
            </ul>
          </div>
        </div>
        <div class="right">
          <!-- Productlistbox -->
          <div class="product_list">
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
            <div class="item">
              <div class="img_box">
                <img src="../assets/img/item4.jpg" alt />
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
                <img src="../assets/img/item5.jpg" alt />
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
                <img src="../assets/img/item6.jpg" alt />
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
          <!-- Nav -->
        <nav aria-label="Page navigation example" style="float:right;padding-right:20px;">
          <ul class="pagination">
            <li class="page-item">
              <a class="page-link" href="#"><i class="fas fa-angle-left"></i></a>
            </li>
            <li class="page-item active"><a class="page-link" href="#">1</a></li>
            <li class="page-item"><a class="page-link" href="#">2</a></li>
            <li class="page-item"><a class="page-link" href="#">3</a></li>
            <li class="page-item">
              <a class="page-link" href="#"><i class="fas fa-angle-right"></i></a>
            </li>
          </ul>
        </nav>
        <!-- End -->
        <div class="clearfix"></div>
          <!-- End -->
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
  name: "Product",
  components: {
    Header,
    Footer,
  },
};
</script>
