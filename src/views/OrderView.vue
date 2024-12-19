<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Order Summary</title>
    <link rel="stylesheet" href="./css/Order.css">
</head>

<body>
    <div class="main">
        <div class="progress-bar">
            <button class="active">訂單內容確認</button>
            <div class="progress-arrow">></div>
            <button>付款方式與配送地址</button>
            <div class="progress-arrow">></div>
            <button>完成訂單</button>
        </div>
        <div class="container">
            <h2>訂單明細</h2>
            <!-- <table>
            <tr>
                <td>產品名稱</td>
                <td>單價</td>
                <td>數量</td>
                <td>小計</td>
            </tr>
        </table> -->

            <div class="name-group">
                <div class="order-item">
                    <div class="item-image">
                        <button class="remove-btn">X</button>
                    </div>
                    <div class="item-details">
                        <p class="item-name">產品名稱</p>
                        <p class="item-price">NT$ 200</p>
                    </div>
                    <div class="item-quantity">
                        <button class="quantity-btn">-</button>
                        <input type="number" value="1">
                        <button class="quantity-btn">+</button>
                    </div>
                    <p class="item-total">NT$ 200</p>
                </div>
                <div class="order-item">
                    <div class="item-image">
                        <button class="remove-btn">X</button>
                    </div>
                    <div class="item-details">
                        <p class="item-name">產品名稱</p>
                        <p class="item-price">NT$ 200</p>
                    </div>
                    <div class="item-quantity">
                        <button class="quantity-btn">-</button>
                        <input type="number" value="1">
                        <button class="quantity-btn">+</button>
                    </div>
                    <p class="item-total">NT$ 200</p>
                </div>
                <div class="order-item">
                    <div class="item-image">
                        <button class="remove-btn">X</button>
                    </div>
                    <div class="item-details">
                        <p class="item-name">產品名稱</p>
                        <p class="item-price">NT$ 200</p>
                    </div>
                    <div class="item-quantity">
                        <button class="quantity-btn">-</button>
                        <input type="number" value="1">
                        <button class="quantity-btn">+</button>
                    </div>
                    <p class="item-total">NT$ 200</p>
                </div>
            </div>
            <div class="summary">
                <p>小計: NT$ 600</p>
            </div>
        </div>
        <div class="actions">
            <a href="./product.html" class="back-btn">繼續選購</button></a>
            <a href="./pay.html" button class="next-btn">下一步</button></a>
        </div>
    </div>
    <footer>
        <div class="footer-content">
            <div class="footer-section">
                <h3>日出徵才</h3>
                <ul>
                    <li><a href="https://www.104.com.tw/" target="_blank">104人力銀行</a></li>
                    <li><a href="https://www.1111.com.tw/" target="_blank">111人力銀行</a></li>
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
                    <li><a href="https://facebook.com" target="_blank"><span><i
                                    class="fa-brands fa-facebook"></i></span></a></li>
                    <li><a href="https://instagram.com" target="_blank"><span><i
                                    class="fa-brands fa-instagram"></i></span></a>
                    </li>
                    <li><a href="https://www.line.me/tw/" target="_blank"><span><i
                                    class="fa-brands fa-line"></i></span></a></li>
                </ul>
            </div>

            <div class="footer-section">
                <h3><i class="fa-solid fa-location-dot"></i>門市資訊</h3>
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