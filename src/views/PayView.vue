<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>商品總覽</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="./css/pay.css">

</head>

<body>
    <!-- ------------------------- -->
        <div class="big-box">
            <div class="main">
                <div class="progress-bar">
                    <button class="active">訂單內容確認</button>
                    <i class="fa-solid fa-chevron-right"></i>
                    <button class="progressbtn">付款方式及資料填寫</button>
                    <i class="fa-solid fa-chevron-right"></i>
                    <button class="submitbtn">完成購買</button>
                </div>
            <section class="form-section">
                <h2>取貨方式</h2>
                <input type="radio" name="pickup" value="宅配">宅配
                <br>
                <input type="radio" name="pickup" value="門市自取">門市自取
            </section>
            <section class="form-section">
                <h2>付款方式</h2>
                <input type="radio" name="payment" value="ATM">ATM帳戶轉帳
                <br>
                <input type="radio" name="payment" value="貨到付款">貨到付款
            </section>
            <section class="form-section">
                <h2>訂購人資料</h2>
                訂購人 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="text" placeholder="Placeholder">
                <br><br>
                電子信箱 &nbsp;&nbsp;<input type="email" placeholder="Placeholder">
                <br><br>
                連絡電話 &nbsp;&nbsp;<input type="tel" placeholder="Placeholder">
                <br><br>
                地址 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="text" placeholder="Placeholder">
            </section>
            <section class="form-section">
                <h2>訂購人資料</h2>
                <input type="radio" name="pickup" value="">是否同訂購人
                <br>
                收件人 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="text" placeholder="Placeholder">
                <br><br>
                電子信箱 &nbsp;&nbsp;<input type="email" placeholder="Placeholder">
                <br><br>
                連絡電話 &nbsp;&nbsp;<input type="tel" placeholder="Placeholder">
                <br><br>
                地址 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="text" placeholder="Placeholder">
                <br><br>
                統編 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="email" placeholder="Placeholder">
                <br><br>
                備註 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="email" placeholder="Placeholder">
            </section>
            <section class="form-section">
                <h2>希望出貨日</h2>
                <div class="content">
                    <table>
                        <!-- 表頭 -->
                        <thead>
                            <!-- tr 表頭列 -->
                            <tr>

                                <th class="month" colspan="7">
                                    <div class="month-title">
                                        <i class="fa-solid fa-chevron-left"></i>
                                        11月
                                        <i class="fa-solid fa-chevron-right"></i>
                                    </div>
                                </th>
                            </tr>
                        </thead>

                        <tbody>
                            <!-- 表內容列 -->
                            <tr>
                                <!-- 內容欄位 -->
                                <td>日</td>
                                <td>一</td>
                                <td>二</td>
                                <td>三</td>
                                <td>四</td>
                                <td>五</td>
                                <td>六</td>
                            </tr>
                            <tr>
                                <td> <input type="radio" id="lastMonth-27" name="option" class="color-toggle" disabled>
                                    <label for="lastMonth-27"><span>27</span></label>
                                </td>
                                <td> <input type="radio" id="lastMonth-28" name="option" class="color-toggle" disabled>
                                    <label for="lastMonth-28"><span>28</span></label>
                                </td>
                                <td> <input type="radio" id="lastMonth-29" name="option" class="color-toggle" disabled>
                                    <label for="lastMonth-29"><span>29</span></label>
                                </td>
                                <td> <input type="radio" id="lastMonth-30" name="option" class="color-toggle" disabled>
                                    <label for="lastMonth-30"><span>30</span></label>
                                </td>
                                <td> <input type="radio" id="lastMonth-31" name="option" class="color-toggle" disabled>
                                    <label for="lastMonth-31"><span>31</span></label>
                                </td>
                                <td> <input type="radio" id="day-1" name="option" class="color-toggle">
                                    <label for="day-1"><span>1</span></label>
                                </td>
                                <td> <input type="radio" id="day-2" name="option" class="color-toggle">
                                    <label for="day-2"><span>2</span></label>
                                </td>
                            </tr>
                            <tr>
                                <td> <input type="radio" id="day-3" name="option" class="color-toggle">
                                    <label for="day-3"><span>3</span></label>
                                </td>
                                <td> <input type="radio" id="day-4" name="option" class="color-toggle">
                                    <label for="day-4"><span>4</span></label>
                                </td>
                                <td> <input type="radio" id="day-5" name="option" class="color-toggle">
                                    <label for="day-5"><span>5</span></label>
                                </td>
                                <td> <input type="radio" id="day-6" name="option" class="color-toggle">
                                    <label for="day-6"><span>6</span></label>
                                </td>
                                <td> <input type="radio" id="day-7" name="option" class="color-toggle">
                                    <label for="day-7"><span>7</span></label>
                                </td>
                                <td> <input type="radio" id="day-8" name="option" class="color-toggle">
                                    <label for="day-8"><span>8</span></label>
                                </td>
                                <td> <input type="radio" id="day-9" name="option" class="color-toggle">
                                    <label for="day-9"><span>9</span></label>
                                </td>
                            </tr>
                            <tr>
                                <td> <input type="radio" id="day-10" name="option" class="color-toggle">
                                    <label for="day-10"><span>10</span></label>
                                </td>
                                <td> <input type="radio" id="day-11" name="option" class="color-toggle">
                                    <label for="day-11"><span>11</span></label>
                                </td>
                                <td> <input type="radio" id="day-12" name="option" class="color-toggle">
                                    <label for="day-12"><span>12</span></label>
                                </td>
                                <td> <input type="radio" id="day-13" name="option" class="color-toggle">
                                    <label for="day-13"><span>13</span></label>
                                </td>
                                <td> <input type="radio" id="day-14" name="option" class="color-toggle">
                                    <label for="day-14"><span>14</span></label>
                                </td>
                                <td> <input type="radio" id="day-15" name="option" class="color-toggle">
                                    <label for="day-15"><span>15</span></label>
                                </td>
                                <td> <input type="radio" id="day-16" name="option" class="color-toggle">
                                    <label for="day-16"><span>16</span></label>
                                </td>
                            </tr>
                            <tr>
                                <td> <input type="radio" id="day-17" name="option" class="color-toggle">
                                    <label for="day-17"><span>17</span></label>
                                </td>
                                <td> <input type="radio" id="day-18" name="option" class="color-toggle">
                                    <label for="day-18"><span>18</span></label>
                                </td>
                                <td> <input type="radio" id="day-19" name="option" class="color-toggle">
                                    <label for="day-19"><span>19</span></label>
                                </td>
                                <td> <input type="radio" id="day-20" name="option" class="color-toggle">
                                    <label for="day-20"><span>20</span></label>
                                </td>
                                <td> <input type="radio" id="day-21" name="option" class="color-toggle">
                                    <label for="day-21"><span>21</span></label>
                                </td>
                                <td> <input type="radio" id="day-22" name="option" class="color-toggle">
                                    <label for="day-22"><span>22</span></label>
                                </td>
                                <td> <input type="radio" id="day-23" name="option" class="color-toggle">
                                    <label for="day-23"><span>23</span></label>
                                </td>
                            </tr>
                            <tr>
                                <td> <input type="radio" id="day-24" name="option" class="color-toggle">
                                    <label for="day-24"><span>24</span></label>
                                </td>
                                <td> <input type="radio" id="day-25" name="option" class="color-toggle">
                                    <label for="day-25"><span>25</span></label>
                                </td>
                                <td> <input type="radio" id="day-26" name="option" class="color-toggle">
                                    <label for="day-26"><span>26</span></label>
                                </td>
                                <td> <input type="radio" id="day-27" name="option" class="color-toggle">
                                    <label for="day-27"><span>27</span></label>
                                </td>
                                <td> <input type="radio" id="day-28" name="option" class="color-toggle">
                                    <label for="day-28"><span>28</span></label>
                                </td>
                                <td> <input type="radio" id="day-29" name="option" class="color-toggle">
                                    <label for="day-29"><span>29</span></label>
                                </td>
                                <td> <input type="radio" id="day-30" name="option" class="color-toggle">
                                    <label for="day-30"><span>30</span></label>
                                </td>
                            </tr>
                        </tbody>
                        <tfoot></tfoot>
                    </table>
                    <div class="bottom">
                        <div class="remark">警告標語 Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea alias,
                            excepturi
                            placeat
                            totam
                            dolore earum sed nemo et ratione neque doloribus eligendi quia exercitationem cum eius
                            voluptate
                            veniam
                            dicta
                            quae!
                            Perferendis, nam. Ut quia aliquid aperiam dolores, accusantium voluptas dicta fugiat nostrum
                            sed
                            unde,
                            exercitationem reiciendis repudiandae perferendis, eaque labore tempore? Aliquid quisquam a
                            aut
                            ab nulla, ex
                            fugiat placeat!
                        </div>
            </section>
            <div class="container"></div>
        <div class="actions">
            <a href="./Order.html" class="back-btn">回到上一步</button></a>
            <a href="./lastpage-new.html" class="next-btn">確認送出</button></a>
        </div>
        </div>
    </div>
    <!-- ------------------------- -->
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