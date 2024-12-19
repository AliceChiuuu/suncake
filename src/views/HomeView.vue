<!-- <script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script> -->

<!-- <template>
  <main>
    <TheWelcome />
  </main>
</template> -->

<template>
  <body>
    <!-- 頁首 -->
    <div class="container">
      <!-- 輪播Banner容器 -->
      <div class="carousel-container">
        <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="https://via.placeholder.com/1200x800/FF5733/FFFFFF?text=Banner+1" class="d-block w-100"
                alt="Banner 1">
            </div>
            <div class="carousel-item">
              <img src="https://via.placeholder.com/1200x800/33A1FF/FFFFFF?text=Banner+2" class="d-block w-100"
                alt="Banner 2">
            </div>
            <div class="carousel-item">
              <img src="https://via.placeholder.com/1200x800/8E44AD/FFFFFF?text=Banner+3" class="d-block w-100"
                alt="Banner 3">
            </div>
          </div>
          <section>
            <div class="textbox">
              <h1>日出</h1>
              <h1>乳酪蛋糕</h1>
              <h1>DawnCake</h1><br><br>
              <h4>DawnCake</h4><br><br>
              <h4>內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文</h4>
            </div>
          </section>
          <!-- 左箭頭 -->
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <!-- 右箭頭 -->
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
    </div>
    <!-- 內文區 -->
    <main class="contanierall">
      <section class="newsbanner">
        <span>最新消息</span>
        <h5 class="newstext">內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文</h5>
        <button class="newsbtn">瞭 解 更 多</button>
      </section>
      <section class="products">
        <span>主打商品</span>
        <div class="box">
          <div class="onecard">
            <p>土鳳梨酥</p>
            <h5>內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文</h5>
            <button class="productsbtn">瞭 解 更 多</button>
            <!-- <a href="./Total-products.html" class="productsbtn">瞭 解 更 多</button></a> -->
          </div>
          <div class="twocard">
            <p>乳酪蛋糕</p>
            <h5>內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內文內</h5>
            <button class="productsbtn2">瞭 解 更 多</button>
          </div>
        </div>
      </section>
      <section class="products-all">
        <span>系列產品</span>
        <div class="productsbox">
          <div class="cards">
            <a href="./Total-products.html">
              <div class="boxtext">糕餅/茶食</div>
            </a>
          </div>
          <div class="cards">
            <a href="./Total-products.html">
              <div class="boxtext">宮原巧克力</div>
            </a>
          </div>
          <div class="cards">
            <a href="./Total-products.html">
              <div class="boxtext">宮原冰淇淋</div>
            </a>
          </div>
          <div class="cards">
            <a href="./Total-products.html">
              <div class="boxtext">選茶</div>
            </a>
          </div>
          <div class="cards">
            <a href="./Total-products.html">
              <div class="boxtext">綜合禮盒</div>
            </a>
          </div>
          <div class="cards">
            <a href="./Total-products.html">
              <div class="boxtext">彌月禮盒</div>
            </a>
          </div>
        </div>
      </section>
      <section class="history">
        <span>品牌故事</span>
        <div class="historyimg"></div>
        <button class="history-btn">瞭 解 更 多</button>
      </section>
    </main>
  </body>
</template>

<style scoped>
@import'../assets/index.css';
</style>