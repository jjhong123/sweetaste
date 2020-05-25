<template>
  <div>
    <Header />

    <div class="cart">
      <div class="lists">
        <div class="title">您的購物車</div>
        <table>
          <tbody>
            <tr>
              <td class="pic">
                <img src="../assets/img/item1.jpg" alt="" />
              </td>
              <td class="item_title">
                <p>焦糖馬卡龍</p>
                <p class="price">NT$450</p>
              </td>
              <td class="select">
                <span>-</span>
                <input type="number" value="2" />
                <span>+</span>
              </td>
              <td class="total_price">
                <p>NT$900</p>
              </td>
              <td class="delete">
               <i class="far fa-trash-alt"></i>
              </td>
            </tr>
            <tr>
              <td class="pic">
                <img src="../assets/img/item3.jpg" alt="" />
              </td>
              <td class="item_title">
                <p>焦糖馬卡龍</p>
                <p class="price">NT$450</p>
              </td>
              <td class="select">
                <span>-</span>
                <input type="number" value="2" />
                <span>+</span>
              </td>
              <td class="total_price">
                <p>NT$900</p>
              </td>
              <td class="delete">
                <i class="far fa-trash-alt"></i>
              </td>
            </tr>
            <tr>
              <td class="pic">
                <img src="../assets/img/item2.jpg" alt="" />
              </td>
              <td class="item_title">
                <p>焦糖馬卡龍</p>
                <p class="price">NT$450</p>
              </td>
              <td class="select">
                <span>-</span>
                <input type="number" value="2" />
                <span>+</span>
              </td>
              <td class="total_price">
                <p>NT$900</p>
              </td>
              <td class="delete">
                <i class="far fa-trash-alt"></i>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
      <div class="order_info">
        <h2>訂單摘要</h2>
        <div class="price">
          <span>小計</span>
          <span>NT$2700</span>
        </div>
        <div class="fee">
          <span>運費</span>
          <span>NT$300</span>
        </div>
        <div class="total">
          <span>小計</span>
          <span>NT$2700</span>
        </div>
        <div class="checkout"><a href="checkout_1.html">結帳</a></div>
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
  name: "Cart",
  components: {
    Header,
    Footer,
  },
};
</script>
