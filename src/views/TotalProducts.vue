<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>商品總覽</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <link rel="stylesheet" href="./css/Total-products.css">
</head>

<body>
    <nav class="bg-decoration-transparent-800">
        <div class="mx-auto max-w-[1920px] px-2 ml:px-6 lg:px-8">
            <div class="relative flex h-16 items-center justify-between">
                <div class="absolute inset-y-0 left-0 flex items-center sm:hidden">
                    <!-- Mobile menu button-->
                    <button type="button"
                        class="relative inline-flex items-center justify-center rounded-md p-2 text-gray-400 hover:bg-gray-700 hover:text-white focus:outline-none focus:ring-2 focus:ring-inset focus:ring-white">
                        <span class="absolute -inset-0.5"></span>
                    </button>
                </div>
                <div class="flex flex-1 items-center justify-center sm:items-stretch sm:justify-start">
                    <div class="flex shrink-0 items-center">
                        <img class="h-8 w-auto"
                            src="https://www.dawncake.com.tw/images/logos/1/%E6%97%A5%E6%97%A5%E5%87%BA%E8%82%A1%E4%BB%BD%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8-01-01-02.png"
                            alt="Your Company">
                    </div>
                    <div class="hidden sm:ml-6 sm:block">
                        <div class="flex space-x-4">
                            <a href="#"
                                class="rounded-md px-3 py-2 text-sm font-medium text-gray-300 hover:text-lg">關於日出</a>
                            <a href="#"
                                class="rounded-md px-3 py-2 text-sm font-medium text-gray-300 hover:text-lg">最新消息</a>
                            <a href="#"
                                class="rounded-md px-3 py-2 text-sm font-medium text-gray-300 hover:text-lg">主打商品</a>
                            <a href="#"
                                class="rounded-md px-3 py-2 text-sm font-medium text-gray-300 hover:text-lg">商品總覽</a>
                            <a href="#"
                                class="rounded-md px-3 py-2 text-sm font-medium text-gray-300 hover:text-lg">常見問題</a>
                        </div>
                    </div>
                </div>

                <!-- 搜尋框，將圖示放在前面 -->
                <div class="relative mr-4 flex items-center">
                    <span class="absolute left-2 text-gray-400">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </span>
                    <input type="text" placeholder="搜尋"
                        class="pl-8 w-36 sm:w-20 p-2 text-gray-700 border rounded-md focus:outline-none focus:ring-2 focus:ring-gray-500">
                </div>

                <div class="absolute inset-y-0 right-0 flex items-center pr-2 sm:static sm:inset-auto sm:ml-6 sm:pr-0">
                    <!-- 購物車圖示 -->
                    <button type="button"
                        class="relative rounded-full p-1 text-gray-400 focus:ring-2 focus:ring-white focus:ring-offset-2 focus:ring-offset-gray-800">
                        <span class="absolute -inset-1.5"></span>
                        <span class="sr-only">View cart</span>
                        <i class="fa-solid fa-cart-shopping text-xl"></i> <!-- 替換成購物車圖示 -->
                    </button>

                    <!-- Profile dropdown -->
                    <div class="relative ml-3">
                        <div>
                            <button type="button"
                                class="relative flex rounded-full text-sm focus:outline-none focus:ring-2 focus:ring-white focus:ring-offset-2 focus:ring-offset-gray-800"
                                id="user-menu-button" aria-expanded="false" aria-haspopup="true">
                                <span class="absolute -inset-1.5"></span>
                                <span class="sr-only">Open user menu</span>
                                <i class="fa-regular fa-user text-xl">登入</i>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Mobile menu, show/hide based on menu state. -->
        <div class="sm:hidden" id="mobile-menu">
            <div class="space-y-1 px-2 pb-3 pt-2">
                <a href="#" class="block rounded-md bg-gray-900 px-3 py-2 text-base font-medium text-white"
                    aria-current="page">Dashboard</a>
                <a href="#"
                    class="block rounded-md px-3 py-2 text-base font-medium text-gray-300 hover:bg-gray-700 hover:text-white">Team</a>
                <a href="#"
                    class="block rounded-md px-3 py-2 text-base font-medium text-gray-300 hover:bg-gray-700 hover:text-white">Projects</a>
                <a href="#"
                    class="block rounded-md px-3 py-2 text-base font-medium text-gray-300 hover:bg-gray-700 hover:text-white">Calendar</a>
            </div>
        </div>
    </nav>
    <script src="https://cdn.tailwindcss.com"></script>


    <div class="text-box">
        <div class="text-box-s">
            <h2>產品名稱</h2>
            <p>介紹文字介紹文字介紹文字。</p>
        </div>
    </div>
    <div class="banner">
        <div class="img"></div>
    </div>
    <!-- Navigation Section -->
    <div class="section">
        <div class="nav-menu">
            <span><a href="">糕餅茶食</a></span>
            <span><a href="">宮原巧克力</a></span>
            <span><a href="">宮原眼科冰淇淋</a></span>
            <span><a href="">綜合禮盒</a></span>
            <span><a href="">彌月禮盒</a></span>
            <span><a href="">選茶</a></span>
            <span><a href="">訂製專區</a></span>
        </div>
    </div>
    <!-- Product Section -->
    <div class="product-section">
        <h2>XX系列</h2>
        <div class="product-grid">
            <div class="product-card">
                <a href="./product.html"><img src="" alt=""></a>
                <div class="text">
                    <div class="content">
                        <span>商品名稱</span>
                        <span>NT$XXX</span>
                    </div>
                    <div class="mask"></div>
                </div>
            </div>
            <div class="product-card">
                <a href="./product.html"><img src="" alt=""></a>
                <div class="text">
                    <div class="content">
                        <span>商品名稱</span>
                        <span>NT$XXX</span>
                    </div>
                    <div class="mask"></div>
                </div>
            </div>
            <div class="product-card">
                <a href="./product.html"><img src="" alt=""></a>
                <div class="text">
                    <div class="content">
                        <span>商品名稱</span>
                        <span>NT$XXX</span>
                    </div>
                    <div class="mask"></div>
                </div>
            </div>
            <div class="product-card">
                <a href="./product.html"><img src="" alt=""></a>
                <div class="text">
                    <div class="content">
                        <span>商品名稱</span>
                        <span>NT$XXX</span>
                    </div>
                    <div class="mask"></div>
                </div>
            </div>
            <div class="product-card">
                <a href="./product.html"><img src="" alt=""></a>
                <div class="text">
                    <div class="content">
                        <span>商品名稱</span>
                        <span>NT$XXX</span>
                    </div>
                    <div class="mask"></div>
                </div>
            </div>
            <div class="product-card">
                <a href="./product.html"><img src="" alt=""></a>
                <div class="text">
                    <div class="content">
                        <span>商品名稱</span>
                        <span>NT$XXX</span>
                    </div>
                    <div class="mask"></div>
                </div>
            </div>
        </div>
        <div class="line"></div>
        <h2>XX系列</h2>
        <div class="product-grid">
            <div class="product-card">
                <a href="./product.html"><img src="" alt=""></a>
                <div class="text">
                    <div class="content">
                        <span>商品名稱</span>
                        <span>NT$XXX</span>
                    </div>
                    <div class="mask"></div>
                </div>
            </div>
            <div class="product-card">
                <a href="./product.html"><img src="" alt=""></a>
                <div class="text">
                    <div class="content">
                        <span>商品名稱</span>
                        <span>NT$XXX</span>
                    </div>
                    <div class="mask"></div>
                </div>
            </div>
            <div class="product-card">
                <a href="./product.html"><img src="" alt=""></a>
                <div class="text">
                    <div class="content">
                        <span>商品名稱</span>
                        <span>NT$XXX</span>
                    </div>
                    <div class="mask"></div>
                </div>
            </div>
            <div class="product-card">
                <a href="./product.html"><img src="" alt=""></a>
                <div class="text">
                    <div class="content">
                        <span>商品名稱</span>
                        <span>NT$XXX</span>
                    </div>
                    <div class="mask"></div>
                </div>
            </div>
            <div class="product-card">
                <a href="./product.html"><img src="" alt=""></a>
                <div class="text">
                    <div class="content">
                        <span>商品名稱</span>
                        <span>NT$XXX</span>
                    </div>
                    <div class="mask"></div>
                </div>
            </div>
            <div class="product-card">
                <a href="./product.html"><img src="" alt=""></a>
                <div class="text">
                    <div class="content">
                        <span>商品名稱</span>
                        <span>NT$XXX</span>
                    </div>
                    <div class="mask"></div>
                </div>
            </div>
        </div>
    </div>
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
</body>

</html>