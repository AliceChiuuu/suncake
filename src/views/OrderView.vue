<template>
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
            <a href="./ProductView.vue"><button class="back-btn">繼續選購</button></a>
            <a href="./PayView.vue"><button class="next-btn">下一步</button></a>
            <!-- <a href="./product.html" class="back-btn">繼續選購</button></a>
            <a href="./pay.html" button class="next-btn">下一步</button></a> -->
        </div>
    </div>
</template>

<style scoped>
@import'../assets/css/Order.css';
</style>