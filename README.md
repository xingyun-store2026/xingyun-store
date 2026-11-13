<!DOCTYPE html>

<html lang="zh-CN">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<meta name="theme-color" content="#090d1c">

<title>星云商城 - 数字生活服务</title>

<style>

* {

  margin: 0;

  padding: 0;

  box-sizing: border-box;

}

body {

  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI",

  "PingFang SC", "Microsoft YaHei", sans-serif;

  background: #090d1c;

  color: #fff;

  min-height: 100vh;

}

.container {

  width: 100%;

  max-width: 520px;

  margin: auto;

  padding: 20px 16px 100px;

}

.header {

  display: flex;

  align-items: center;

  justify-content: space-between;

  margin-bottom: 28px;

}

.logo {

  font-size: 25px;

  font-weight: 800;

  letter-spacing: 1px;

  background: linear-gradient(90deg,#8b9cff,#d29aff);

  -webkit-background-clip: text;

  color: transparent;

}

.cart {

  background: #1b2140;

  border: 1px solid #343c69;

  padding: 10px 15px;

  border-radius: 20px;

  font-size: 13px;

}

.hero {

  padding: 28px 22px;

  border-radius: 22px;

  background: linear-gradient(135deg,#293b80,#603b9e,#30265f);

  box-shadow: 0 12px 35px #22245a55;

  margin-bottom: 22px;

}

.hero-tag {

  display: inline-block;

  background: #ffffff22;

  padding: 6px 12px;

  border-radius: 20px;

  font-size: 12px;

  margin-bottom: 15px;

}

.hero h1 {

  font-size: 27px;

  margin-bottom: 10px;

}

.hero p {

  color: #dedcff;

  font-size: 13px;

  line-height: 1.8;

}

.notice {

  background: #151b32;

  border: 1px solid #252e51;

  border-radius: 13px;

  padding: 14px;

  font-size: 13px;

  color: #c7cfff;

  margin-bottom: 28px;

}

.section-title {

  display: flex;

  align-items: center;

  justify-content: space-between;

  margin-bottom: 16px;

}

.section-title h2 {

  font-size: 19px;

}

.section-title span {

  font-size: 12px;

  color: #8792c5;

}

.search {

  width: 100%;

  padding: 14px 16px;

  border-radius: 13px;

  background: #151b32;

  border: 1px solid #293456;

  color: white;

  outline: none;

  font-size: 14px;

  margin-bottom: 20px;

}

.search:focus {

  border-color: #8c79ff;

}

.products {

  display: grid;

  grid-template-columns: 1fr 1fr;

  gap: 13px;

}

.card {

  background: linear-gradient(150deg,#1b2342,#12182d);

  border: 1px solid #303b64;

  border-radius: 17px;

  padding: 17px 14px;

  min-width: 0;

}

.card-icon {

  width: 43px;

  height: 43px;

  border-radius: 13px;

  display: flex;

  align-items: center;

  justify-content: center;

  font-size: 22px;

  background: linear-gradient(135deg,#554bc0,#8d5bd5);

  margin-bottom: 14px;

}

.card h3 {

  font-size: 16px;

  margin-bottom: 8px;

}

.card p {

  color: #9ca8d0;

  font-size: 12px;

  line-height: 1.6;

  min-height: 38px;

}

.price {

  font-size: 22px;

  font-weight: 800;

  color: #b6a2ff;

  margin: 15px 0;

}

.price small {

  font-size: 12px;

  font-weight: 400;

}

.buy {

  width: 100%;

  padding: 11px 5px;

  border: none;

  border-radius: 10px;

  background: linear-gradient(90deg,#7065ef,#a36bea);

  color: white;

  font-size: 13px;

  font-weight: 700;

  cursor: pointer;

}

.buy:active {

  opacity: .75;

  transform: scale(.98);

}

.empty {

  display: none;

  color: #9ca8d0;

  text-align: center;

  padding: 35px 0;

  font-size: 14px;

}

.service {

  margin-top: 28px;

  padding: 19px;

  border-radius: 16px;

  background: #151b32;

  border: 1px solid #293456;

}

.service h3 {

  font-size: 16px;

  margin-bottom: 10px;

}

.service p {

  color: #9ca8d0;

  font-size: 13px;

  line-height: 1.9;

}

.footer {

  text-align: center;

  padding: 30px 0 10px;

  color: #68749e;

  font-size: 11px;

  line-height: 2;

}

.bottom {

  position: fixed;

  bottom: 0;

  left: 0;

  right: 0;

  background: #10162aee;

  backdrop-filter: blur(15px);

  border-top: 1px solid #293456;

  display: flex;

  justify-content: center;

  padding: 14px;

  color: #aab4dc;

  font-size: 12px;

}

@media (max-width: 350px) {

  .products {

    grid-template-columns: 1fr;

  }

}

</style>

</head>

<body>

<div class="container">

  <header class="header">

    <div class="logo">✦ 星云商城</div>

    <div class="cart">🛒 购物车 <b id="cartCount">0</b></div>

  </header>

  <section class="hero">

    <div class="hero-tag">✦ NEBULA DIGITAL STORE</div>

    <h1>欢迎来到星云商城</h1>

    <p>探索优质数字商品与会员服务<br>

    简约 · 高效 · 便捷的数字购物体验</p>

  </section>

  <div class="notice">

    📢 商城公告：欢迎来到星云商城，请在购买前仔细阅读商品说明。

  </div>

  <div class="section-title">

    <h2>精选商品</h2>

    <span>PRODUCT CENTER</span>

  </div>

  <input

    class="search"

    id="searchInput"

    type="search"

    placeholder="🔍 搜索商品名称..."

  >

  <div class="products" id="products">

    <div class="card" data-name="月度会员">

      <div class="card-icon">🌙</div>

      <h3>月度会员</h3>

      <p>数字会员服务体验套餐</p>

      <div class="price">¥29 <small>/ 月</small></div>

      <button class="buy" onclick="addCart('月度会员',29)">立即购买</button>

    </div>

    <div class="card" data-name="季度会员">

      <div class="card-icon">⭐</div>

      <h3>季度会员</h3>

      <p>三个月数字会员服务</p>

      <div class="price">¥79 <small>/ 季</small></div>

      <button class="buy" onclick="addCart('季度会员',79)">立即购买</button>

    </div>

    <div class="card" data-name="半年会员">

      <div class="card-icon">💎</div>

      <h3>半年会员</h3>

      <p>六个月数字会员服务</p>

      <div class="price">¥139 <small>/ 半年</small></div>

      <button class="buy" onclick="addCart('半年会员',139)">立即购买</button>

    </div>

    <div class="card" data-name="年度会员">

      <div class="card-icon">👑</div>

      <h3>年度会员</h3>

      <p>十二个月数字会员服务</p>

      <div class="price">¥239 <small>/ 年</small></div>

      <button class="buy" onclick="addCart('年度会员',239)">立即购买</button>

    </div>

  </div>

  <div class="empty" id="empty">没有找到相关商品</div>

  <section class="service">

    <h3>💬 服务说明</h3>

    <p>

      商品详情请以实际介绍为准。<br>

      如有疑问，请通过商城公布的官方客服渠道咨询。<br>

      请勿向陌生人提供账号密码或验证码。

    </p>

  </section>

  <footer class="footer">

    © 2026 星云商城 NEBULA STORE<br>

    数字商品展示平台

  </footer>

</div>

<nav class="bottom">

  ✦ 星云商城　|　精选数字商品　|　欢迎光临

</nav>

<script>

let cartCount = 0;

let cartItems = [];

function addCart(name, price) {

  cartCount++;

  cartItems.push({name, price});

  document.getElementById("cartCount").textContent = cartCount;

  alert(

    "已加入购物车！\n\n商品：" + name +

    "\n价格：¥" + price +

    "\n\n当前为演示页面，暂未接入真实支付。"

  );

}

document.getElementById("searchInput").addEventListener("input", function() {

  const keyword = this.value.trim().toLowerCase();

  const cards = document.querySelectorAll(".card");

  let visible = 0;

  cards.forEach(function(card) {

    const name = card.dataset.name.toLowerCase();

    const show = name.includes(keyword);

    card.style.display = show ? "block" : "none";

    if (show) visible++;

  });

  document.getElementById("empty").style.display =

    visible === 0 ? "block" : "none";

});

</script>

</body>






</html>

