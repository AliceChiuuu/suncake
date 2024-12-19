<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>product</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
  <link rel="stylesheet" href="./css/product.css">
</head>

<body>
  <nav class="contanior-all">
    <div class="logo">
      <img src="./img/日日出股份有限公司-01-01-02.png" alt="">
    </div>
    <ul class="right-menu">
      <li class="test">
        <label for="sun">關於日出</label>
        <input type="checkbox" id="sun" hidden>
        <ul class="openb">
          <li>品牌故事</li>
          <li>門市資訊</li>
        </ul>
      </li>
      <li class="test">
        <label for="new">最新消息</label>
        <input type="checkbox" id="new" hidden>
        <ul class="openb">
          <li>活動資訊</li>
          <li>新品上市</li>
          <li>媒體報導</li>
        </ul>
      </li>
      <li class="test">
        <label for="hot">主打商品</label>
        <input type="checkbox" id="hot" hidden>
        <ul class="openb">
          <li>土鳳梨酥</li>
          <li>乳酪蛋糕</li>
          <li>快速出貨</li>
        </ul>
      </li>
      <li class="test">
        <label for="shop">商品總覽</label>
        <input type="checkbox" id="shop" hidden>
        <ul class="openb">
          <li>糕點/茶食</li>
          <li>宮原巧克力</li>
          <li>宮原冰淇淋</li>
          <li>綜合禮盒</li>
          <li>彌月禮盒</li>
          <li>選茶</li>
          <li>訂製專區</li>
        </ul>
      </li>
      <li class="test">
        <label for="question">常見問題</label>
        <input type="checkbox" id="question" hidden>
        <ul class="openb">
          <li>關於會員</li>
          <li>購買須知</li>
          <li>保存方法</li>
        </ul>
      </li>
    </ul>
    </div>
    <div class="left-menu">
      <div class="search">
        <i class="fa-solid fa-magnifying-glass"></i>
        <span class="hide-text">搜尋</span>
      </div>
      <div class="shopbox">
        <i class="fa-solid fa-cart-shopping"></i>
      </div>
      <div class="login">
        <i class="fa-regular fa-circle-user"></i>
        <span class="hide-text">登入</span>
      </div>
    </div>
  </nav>

  <main>
    <div class="shop-top">
      <div class="shop-top-left">
        <!-- Swiper -->
        <div style="--swiper-navigation-color: #fff; --swiper-pagination-color: #fff" class="swiper mySwiper2">
          <div class="swiper-wrapper">
            <div class="swiper-slide">
              <img src="https://swiperjs.com/demos/images/nature-1.jpg" />
            </div>
            <div class="swiper-slide">
              <img src="https://swiperjs.com/demos/images/nature-2.jpg" />
            </div>
            <div class="swiper-slide">
              <img src="https://swiperjs.com/demos/images/nature-3.jpg" />
            </div>
            <div class="swiper-slide">
              <img src="https://swiperjs.com/demos/images/nature-4.jpg" />
            </div>
            <div class="swiper-slide">
              <img src="https://swiperjs.com/demos/images/nature-5.jpg" />
            </div>
            <div class="swiper-slide">
              <img src="https://swiperjs.com/demos/images/nature-6.jpg" />
            </div>
            <div class="swiper-slide">
              <img src="https://swiperjs.com/demos/images/nature-7.jpg" />
            </div>
            <div class="swiper-slide">
              <img src="https://swiperjs.com/demos/images/nature-8.jpg" />
            </div>
            <div class="swiper-slide">
              <img src="https://swiperjs.com/demos/images/nature-9.jpg" />
            </div>
            <div class="swiper-slide">
              <img src="https://swiperjs.com/demos/images/nature-10.jpg" />
            </div>
          </div>
          <!-- <div class="swiper-button-next"></div>
        <div class="swiper-button-prev"></div> -->
        </div>
        <div class="space">
          <div thumbsSlider="" class="swiper mySwiper">
            <div class="swiper-wrapper">
              <div class="swiper-slide">
                <img src="https://swiperjs.com/demos/images/nature-1.jpg" />
              </div>
              <div class="swiper-slide">
                <img src="https://swiperjs.com/demos/images/nature-2.jpg" />
              </div>
              <div class="swiper-slide">
                <img src="https://swiperjs.com/demos/images/nature-3.jpg" />
              </div>
              <div class="swiper-slide">
                <img src="https://swiperjs.com/demos/images/nature-4.jpg" />
              </div>
              <div class="swiper-slide">
                <img src="https://swiperjs.com/demos/images/nature-5.jpg" />
              </div>
              <div class="swiper-slide">
                <img src="https://swiperjs.com/demos/images/nature-6.jpg" />
              </div>
              <div class="swiper-slide">
                <img src="https://swiperjs.com/demos/images/nature-7.jpg" />
              </div>
              <div class="swiper-slide">
                <img src="https://swiperjs.com/demos/images/nature-8.jpg" />
              </div>
              <div class="swiper-slide">
                <img src="https://swiperjs.com/demos/images/nature-9.jpg" />
              </div>
              <div class="swiper-slide">
                <img src="https://swiperjs.com/demos/images/nature-10.jpg" />
              </div>
            </div>
          </div>
          <div class="swiper-button-next top-next"></div>
          <div class="swiper-button-prev top-prev"></div>
        </div>
      </div>
      <div class="shop-top-right">
        <div class="container">
          <div class="container-top">
            <div class="title">一份日出</div>
            <div class="price">NT1000</div>
          </div>
          <div class="content">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Delectus, sit nihil? Animi,
            optio
            alias fugiat hic soluta eum! Rerum magni odio deserunt laboriosam perferendis? Saepe voluptatibus ut dolores
            sapiente corporis!</div>
          <div class="container-bot">
            <div class="quantity-selector">
              <span class="count">數量&nbsp;&nbsp;&nbsp;</span>
              <button class="quantity-button" id="decrease">-</button>&nbsp;&nbsp;&nbsp;
              <span class="quantity" id="quantity">1</span>&nbsp;&nbsp;&nbsp;
              <button class="quantity-button" id="increase">+</button>
            </div>
            <a href="./Order.html" button type="button" class="buy">
              <span>加入購物車</span>
              </button>
            </a>
          </div>
        </div>
      </div>
    </div>

    <div class="shop-mid">
      <div class="shop-mid-top">
        <!-- 商品介紹 -->
        <input type="radio" id="button1" class="button-toggle" name="button-group" checked>
        <label for="button1" class="button button1">
          <span>商品介紹</span>
        </label>

        <!-- 保存方式 -->
        <input type="radio" id="button2" class="button-toggle" name="button-group">
        <label for="button2" class="button button2">
          <span>保存方式</span>
        </label>

        <!-- 注意事項 -->
        <input type="radio" id="button3" class="button-toggle" name="button-group">
        <label for="button3" class="button button3">
          <span>注意事項</span>
        </label>
      </div>
      <div class="shop-mid-content">
        <div class="content-page" id="Product">
          <div class="img img1"></div>
          <div class="img img2"></div>
        </div>
        <div class="content-page" id="Preservation">
          <div class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem iusto cumque mollitia
            cupiditate odio sint quaerat quia, autem repellat doloribus. Voluptatem iusto voluptate qui quidem eius,
            quibusdam laboriosam ipsum nostrum!
            Saepe ullam provident deleniti recusandae facilis? Ipsum aperiam voluptatem deleniti non, blanditiis illo
            fugit voluptas esse cum ratione architecto distinctio unde, expedita doloribus aliquid officiis, amet
            adipisci? Sapiente, temporibus cupiditate.
            Tempora perferendis inventore repellendus suscipit at quisquam labore nam amet? Velit sapiente corporis iste
            exercitationem! Quidem officia, omnis optio minus ut laborum eligendi esse non molestiae saepe assumenda,
            aliquid sint.
            Aut, perferendis nulla? Architecto nulla minima corporis eaque dolores. Explicabo officia aliquam minima,
            iste
            temporibus cum asperiores suscipit culpa repellendus est vel quaerat illum quidem inventore! Accusantium
            quod
            dignissimos quis.
            Sapiente, rem? Quasi fuga repellendus ut atque dolore, omnis sapiente cum est cumque officiis molestias
            earum
            illum dolores quos rem dolorem aspernatur vero necessitatibus ipsam, voluptatem qui! Est, odit saepe!
            Vel ipsum ipsam dignissimos laudantium fugit odio sit recusandae quisquam magni consequuntur animi a et
            quaerat cum obcaecati architecto numquam delectus nisi impedit, tempora modi cumque minus. Illo, eius saepe?
          </div>
          <div class="img"></div>
        </div>
        <div class="content-page" id="Notice">
          <div class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit voluptates assumenda
            aut error dolore architecto, autem, quaerat voluptatem numquam aspernatur iste esse adipisci? Ipsam rerum a,
            corporis maxime sed nisi!
            Molestiae esse id autem, rem illum ipsam cum labore unde fugit dolor? Autem, fugit harum dolor quaerat
            ducimus
            doloribus dolorem sed? Voluptas recusandae expedita veniam fugiat numquam repellendus tempora dicta?
            Debitis eos asperiores nulla at praesentium rerum aliquid consectetur ut placeat nisi commodi velit nam
            omnis,
            ab qui doloribus aliquam esse quaerat, pariatur dicta! Optio temporibus atque nihil vero quas.
            Debitis, quo vitae vero optio sit quas illo commodi voluptatem voluptas, quis quisquam suscipit tempora eius
            vel eveniet. Ea nemo ipsum odio accusamus veniam sed facilis consectetur sit, repudiandae neque!
            Ducimus officia, eaque voluptatem veritatis commodi sed culpa totam distinctio ipsa assumenda laborum soluta
            optio deserunt labore enim nobis, voluptates, corporis provident id recusandae tempora eligendi dolorum
            adipisci? Sunt, ab.
            Sequi et optio eligendi, est incidunt inventore corrupti eum minima consequatur vero placeat blanditiis
            explicabo numquam dicta accusamus totam quisquam molestias illum? Rem consectetur culpa, enim assumenda
            necessitatibus alias temporibus.
            Nostrum rem consequuntur consectetur! Ullam doloremque aliquam omnis numquam totam quisquam nostrum corporis
            delectus beatae tenetur! Eius, quos autem, perferendis officiis, corrupti libero fugiat nemo veritatis
            reiciendis quas doloribus natus.
            Tempore perferendis quis quae, commodi tempora, fuga laboriosam nisi atque, explicabo minus non vitae?
            Placeat, nobis doloremque expedita quod nisi ut voluptas, repellat animi a neque, culpa possimus omnis
            debitis?
            Dolorum error officia eveniet eum ex rerum magnam, nulla adipisci, quod voluptate illum laudantium facilis
            blanditiis aspernatur voluptatibus maiores provident totam. Ea optio excepturi, quis officiis illo iusto
            praesentium aperiam.
            Obcaecati perspiciatis aliquid hic odio fuga facilis, reprehenderit aspernatur nihil voluptas libero error
            quaerat asperiores ad tempore accusantium in vel quidem cumque. Voluptatum possimus numquam labore voluptate
            atque, recusandae repudiandae!</div>
        </div>
      </div>
    </div>

    <div class="shop-bot">
      <div class="recommend">推薦商品</div>
      <!-- Swiper -->
      <div class="space-out">
        <div class="space">
          <div class="swiper mySwiper3">
            <div class="swiper-wrapper">
              <div class="swiper-slide"><span>Slide 1</span><span>12322222</span></div>
              <div class="swiper-slide"><span>Slide 1</span><span>12322222</span></div>
              <div class="swiper-slide"><span>Slide 1</span><span>12322222</span></div>
              <div class="swiper-slide"><span>Slide 1</span><span>12322222</span></div>
              <div class="swiper-slide"><span>Slide 1</span><span>12322222</span></div>
              <div class="swiper-slide"><span>Slide 1</span><span>12322222</span></div>
              <div class="swiper-slide"><span>Slide 1</span><span>12322222</span></div>
              <div class="swiper-slide">Slide 8</div>
              <div class="swiper-slide">Slide 9</div>
            </div>
          </div>
          <div class="swiper-button-next bot-next"></div>
          <div class="swiper-button-prev bot-prev"></div>
        </div>
      </div>
    </div>
  </main>

  <!-- 頁面尾 -->
  <footer>
    <div class="footer-content">
      <div class="footer-section">
        <h3>日出徵才</h3>
        <ul>
          <li>
            <a href="https://www.104.com.tw/" target="_blank">104人力銀行</a>
          </li>
          <li>
            <a href="https://www.1111.com.tw/" target="_blank">111人力銀行</a>
          </li>
        </ul>
      </div>
      <div class="footer-section">
        <h3>聯絡資訊</h3>
        <ul>
          <li>服務信箱：service1@dawncake.com.tw</li>
          <li>宅配服務專線：+886-4-2359-7477</li>
        </ul>
      </div>

      <div class="footer-section">
        <h3>社交媒體</h3>
        <ul class="social-links">
          <li>
            <a href="https://facebook.com" target="_blank">
              <span><i class="fa-brands fa-facebook"></i></span>
            </a>
          </li>
          <li>
            <a href="https://instagram.com" target="_blank">
              <span><i class="fa-brands fa-instagram"></i></span>
            </a>
          </li>
          <li>
            <a href="https://www.line.me/tw/" target="_blank">
              <span><i class="fa-brands fa-line"></i></span>
            </a>
          </li>
        </ul>
      </div>

      <div class="footer-section">
        <h3>
          <i class="fa-solid fa-location-dot"></i>
          門市資訊
        </h3>
      </div>
    </div>

    <div class="footer-bottom">
      <p>
        廠登：9970239000&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;產品責任險：1403&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第082050102號&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;食品業者登錄字號：B-128389018-00000-8
      </p>
      <br>
      <p>&copy; 2002-2024 日出.</p>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>

  <!-- nav -->
  <script>
    // 這裡用querySelectorAll找出所有的點擊鈕的label =>就是所有的點擊鈕
    let menu = document.querySelectorAll('.right-menu>li>label');
    // 這裡用querySelectorAll選取所有的right-menu>li底下的input =>也是所有的點擊鈕
    let rightMenu = document.querySelectorAll('.right-menu>li>input');
    // 這裡用forEach找出所有的點擊鈕的 item => 就是每一個點擊鈕 ,key => 就是每一個點擊鈕的索引, 這樣就可以知道是哪一個點擊鈕被點擊 ex:關於日出的key是0,最新消息的key是1
    menu.forEach((item, key) => {
      // 這裡用addEventListener監聽每一個點擊鈕的點擊事件,當我點擊時就觸發下面的forEach
      item.addEventListener('click', function () {
        rightMenu.forEach((items, itemkey) => {
          // 這裡判斷如果點擊的點擊鈕的索引等於點擊的點擊鈕的索引就不做事,如果不等於就把所有的點擊鈕都關掉
          if (key == itemkey) return;
          items.checked = false
        });
      })
    });
  </script>

  <!-- 上方輪播 -->
  <script>
    var swiper = new Swiper(".mySwiper", {
      spaceBetween: 10,
      slidesPerView: 4,
      freeMode: true,
      watchSlidesProgress: true,
    });
    var swiper2 = new Swiper(".mySwiper2", {
      spaceBetween: 10,
      navigation: {
        // nextEl: ".swiper-button-next",
        // prevEl: ".swiper-button-prev",
        nextEl: ".top-next",
        prevEl: ".top-prev",
      },
      thumbs: {
        swiper: swiper,
      },
    });
  </script>

  <!-- 商品數量 -->
  <script>
    document.getElementById("increase").addEventListener("click", function () {
      let quantity = document.getElementById("quantity");
      quantity.textContent = parseInt(quantity.textContent) + 1;
    });

    document.getElementById("decrease").addEventListener("click", function () {
      let quantity = document.getElementById("quantity");
      if (parseInt(quantity.textContent) > 1) {
        quantity.textContent = parseInt(quantity.textContent) - 1;
      }
    });
  </script>

  <!-- 轉換頁面 -->
  <script>
    // 獲取所有的radio按鈕和對應的內容頁
    const buttons = document.querySelectorAll('.button-toggle');
    const pages = document.querySelectorAll('.content-page');

    // 為每個按鈕添加點擊事件
    buttons.forEach(button => {
      button.addEventListener('change', function () {
        // 隱藏所有內容頁
        pages.forEach(page => page.style.display = 'none');

        // 根據選中的按鈕顯示對應的內容
        if (document.getElementById('button1').checked) {
          document.getElementById('Product').style.display = 'block';
        } else if (document.getElementById('button2').checked) {
          document.getElementById('Preservation').style.display = 'block';
        } else if (document.getElementById('button3').checked) {
          document.getElementById('Notice').style.display = 'block';
        }
      });
    });

    // 頁面加載時，根據預設的選擇顯示相應的內容
    window.addEventListener('load', function () {
      if (document.getElementById('button1').checked) {
        document.getElementById('Product').style.display = 'block';
      }
    });
  </script>

  <!-- 下方輪播 -->
  <script>
    var swiper = new Swiper(".mySwiper3", {
      spaceBetween: 10,
      slidesPerView: 3,
      freeMode: true,
      watchSlidesProgress: true,
      navigation: {
        nextEl: ".bot-next",
        prevEl: ".bot-prev",
      },
    });
  </script>

</body>

</html>