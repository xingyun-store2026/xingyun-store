<!DOCTYPE html>

<html lang="zh-CN">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width,initial-scale=1">

<meta name="theme-color" content="#101018">

<title>蟹老板卡商｜精选数字好物</title>

<style>

*{box-sizing:border-box}

body{margin:0;background:#101018;color:#faf7f0;font-family:-apple-system,BlinkMacSystemFont,"PingFang SC","Microsoft YaHei",sans-serif}

a{text-decoration:none;color:inherit}

.wrap{width:min(1080px,calc(100% - 34px));margin:auto}

header{position:sticky;top:0;background:#101018ed;border-bottom:1px solid #ffffff18;z-index:5}

.nav{height:74px;display:flex;align-items:center;justify-content:space-between}

.brand{display:flex;align-items:center;gap:11px;font-weight:850;font-size:20px}

.avatar{width:44px;height:44px;object-fit:cover;border-radius:50%;border:2px solid #e8c17d}

.brand small{display:block;color:#e8c17d;font-size:9px;letter-spacing:2px;margin-top:3px}

.links{display:flex;gap:25px;color:#c3bfca;font-size:13px}

.cart{background:#24232c;border:1px solid #5a4931;color:#f1d69f;padding:10px 14px;border-radius:30px}

.hero{padding:65px 0 45px;display:grid;grid-template-columns:1.1fr .9fr;gap:35px;align-items:center}

.eyebrow{color:#e8c17d;letter-spacing:3px;font-size:11px}

h1{font-size:clamp(40px,6vw,66px);line-height:1.13;margin:18px 0;letter-spacing:-2px}

.gold{background:linear-gradient(90deg,#fff0c8,#d5a75b);background-clip:text;color:transparent}

.lead{color:#b9b4c0;line-height:1.95;max-width:530px}

.btn{display:inline-block;padding:13px 19px;border-radius:10px;border:0;font-weight:750;cursor:pointer}

.primary{background:linear-gradient(110deg,#f1d18f,#bd8c45);color:#21180d}

.ghost{background:#24232c;border:1px solid #4b4650;color:#eee8dc;margin-left:8px}

.showcase{min-height:320px;border:1px solid #6b5738;border-radius:24px;background:linear-gradient(145deg,#302a2a,#17171f 70%,#352719);display:grid;place-items:center;position:relative;overflow:hidden}

.showcase:before,.showcase:after{content:"";position:absolute;width:290px;height:290px;border:1px solid #d7b16b55;border-radius:50%;transform:scaleY(.4) rotate(-25deg)}

.showcase:after{width:350px;height:350px;transform:scaleY(.4) rotate(30deg)}

.heroimg{width:175px;height:175px;object-fit:cover;border-radius:50%;border:4px solid #e8c17d;box-shadow:0 0 0 12px #e5bd7718;z-index:1}

.showlabel{position:absolute;bottom:22px;color:#e8c17d;font-size:10px;letter-spacing:4px}

.notice{background:#211e1b;border:1px solid #55442e;border-radius:12px;padding:15px 18px;color:#c9c1b4;font-size:13px}

.notice b{color:#e8c17d;margin-right:10px}

section{padding:42px 0}

.head{display:flex;justify-content:space-between;align-items:end;margin-bottom:20px}

.kicker{color:#e8c17d;font-size:10px;letter-spacing:3px}

h2{font-size:28px;margin:8px 0 0}

.muted{color:#aaa6b2;font-size:12px}

.tools{display:flex;gap:9px;flex-wrap:wrap;margin-bottom:18px}

.search{flex:1;min-width:180px;background:#1b1a23;border:1px solid #393642;border-radius:10px;padding:12px;color:white}

.filter{background:#1b1a23;border:1px solid #393642;border-radius:9px;padding:10px 13px;color:#c7c1cc}

.filter.active{border-color:#e8c17d;color:#e8c17d}

.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:15px}

.card{padding:19px;background:linear-gradient(150deg,#25232c,#181820);border:1px solid #393642;border-radius:16px;transition:.2s}

.card:hover{transform:translateY(-4px);border-color:#9a7848}

.ico{width:46px;height:46px;border-radius:13px;background:#65502f55;display:grid;place-items:center;font-size:23px}

.tag{color:#e8c17d;font-size:11px;display:block;margin-top:13px}

.card h3{margin:8px 0}

.desc{font-size:12px;color:#aaa6b2;line-height:1.8;min-height:43px}

.price{font-size:27px;font-weight:850;color:#f0d49b;margin:16px 0}

.price small{font-size:11px;color:#aaa6b2;font-weight:400}

.actions{display:flex;gap:8px}

.actions button{flex:1;padding:10px 4px;border-radius:9px;font-size:12px}

.detail{background:#302e38;border:1px solid #514d58;color:#eee}

.add{background:linear-gradient(110deg,#f1d18f,#bd8c45);border:0;color:#21180d;font-weight:800}

.empty{display:none;text-align:center;padding:30px;color:#aaa6b2}

.features{display:grid;grid-template-columns:repeat(3,1fr);gap:13px}

.feature{background:#1b1a23;border:1px solid #393642;border-radius:14px;padding:19px}

.feature b{display:block;margin:9px 0}

.feature p,.contact p{font-size:12px;line-height:1.8;color:#aaa6b2;margin:0}

.contact{padding:25px;border:1px solid #665238;border-radius:16px;background:linear-gradient(110deg,#30271d,#1d1c22);display:flex;justify-content:space-between;align-items:center;gap:18px}

.contact h2{margin:0 0 8px}

footer{border-top:1px solid #ffffff15;padding:25px 0 35px;color:#85818e;font-size:11px;line-height:2}

dialog{width:min(90%,420px);background:#211f28;color:white;border:1px solid #80633c;border-radius:16px;padding:22px}

dialog p{color:#bbb6c2;line-height:1.8;font-size:13px}

.toast{position:fixed;bottom:24px;left:50%;transform:translate(-50%,20px);opacity:0;background:#f5e5c5;color:#251b0d;padding:12px 17px;border-radius:10px;transition:.2s;z-index:9}

.toast.show{opacity:1;transform:translate(-50%,0)}

@media(max-width:740px){

.links{display:none}.hero{grid-template-columns:1fr;padding:44px 0 32px}

.showcase{min-height:245px}.heroimg{width:145px;height:145px}

.grid{grid-template-columns:repeat(2,1fr)}.features{grid-template-columns:1fr}

.head{display:block}.muted{display:block;margin-top:8px}

.contact{align-items:flex-start;flex-direction:column}

}

@media(max-width:380px){.grid{grid-template-columns:1fr}}

</style>

</head>

<body>

<header>

<div class="wrap nav">

<a class="brand" href="#">

<img class="avatar" src="avatar.jpg" alt="蟹老板卡商头像">

<span>蟹老板卡商<small>CRAB BOSS · DIGITAL GOODS</small></span>

</a>

<nav class="links">

<a href="#products">精选商品</a>

<a href="#service">服务优势</a>

<a href="#contact">客服咨询</a>

</nav>

<button class="cart" id="cart">购物袋 <b id="count">0</b></button>

</div>

</header>

<main class="wrap">

<div class="hero">

<div>

<div class="eyebrow">✦ WELCOME TO CRAB BOSS</div>

<h1>好物严选<br><span class="gold">品质数字生活</span></h1>

<p class="lead">欢迎来到蟹老板卡商。精选数字卡券与会员权益，商品信息清晰呈现，为你带来简洁、安心、顺畅的选购体验。</p>

<p>

<a class="btn primary" href="#products">立即逛逛 →</a>

<a class="btn ghost" href="#contact">联系咨询</a>

</p>

</div>

<div class="showcase">

<img class="heroimg" src="avatar.jpg" alt="蟹老板卡商头像">

<div class="showlabel">CRAB BOSS · OFFICIAL STORE</div>

</div>

</div>

<div class="notice"><b>店铺公告</b>欢迎光临蟹老板卡商。商品内容、使用范围及售后规则请以每件商品的正式说明为准。</div>

<section id="products">

<div class="head">

<div><div class="kicker">CURATED DIGITAL GOODS</div><h2>人气精选</h2></div>

<span class="muted">精选好物 · 明码标示</span>

</div>

<div class="tools">

<input class="search" id="search" placeholder="搜索商品名称…">

<button class="filter active" data-filter="全部">全部商品</button>

<button class="filter" data-filter="卡券">数字卡券</button>

<button class="filter" data-filter="会员">会员权益</button>

</div>

<div class="grid" id="grid">

<article class="card" data-name="数字礼品卡" data-cat="卡券">

<div class="ico">🎁</div><span class="tag">数字卡券</span>

<h3>数字礼品卡</h3><p class="desc">数字礼品卡展示位，请按实际面值与适用范围修改。</p>

<div class="price">¥29 <small>起 / 张</small></div>

<div class="actions">

<button class="detail" data-info="数字礼品卡|请填写真实发行方、面值、适用地区、有效期及兑换规则。">商品详情</button>

<button class="add" data-add="数字礼品卡">加入购物袋</button>

</div></article>

<article class="card" data-name="会员权益卡" data-cat="会员">

<div class="ico">👑</div><span class="tag">会员权益</span>

<h3>会员权益卡</h3><p class="desc">会员权益展示位，具体权益以正式商品说明为准。</p>

<div class="price">¥49 <small>起 / 份</small></div>

<div class="actions">

<button class="detail" data-info="会员权益卡|请填写真实服务方、会员期限、权益内容及使用条件。">商品详情</button>

<button class="add" data-add="会员权益卡">加入购物袋</button>

</div></article>

<article class="card" data-name="游戏点卡" data-cat="卡券">

<div class="ico">🎮</div><span class="tag">数字卡券</span>

<h3>游戏点卡</h3><p class="desc">游戏点卡展示位，请按实际商品填写平台与区服。</p>

<div class="price">¥30 <small>起 / 张</small></div>

<div class="actions">

<button class="detail" data-info="游戏点卡|请确认卡券来源正规，并明确平台、区服、面值和兑换方式。">商品详情</button>

<button class="add" data-add="游戏点卡">加入购物袋</button>

</div></article>

<article class="card" data-name="软件授权卡" data-cat="会员">

<div class="ico">💻</div><span class="tag">会员权益</span>

<h3>软件授权卡</h3><p class="desc">正版软件授权展示位，按授权许可范围销售。</p>

<div class="price">¥59 <small>起 / 份</small></div>

<div class="actions">

<button class="detail" data-info="软件授权卡|请确认软件授权真实有效，并说明设备数、期限和适用地区。">商品详情</button>

<button class="add" data-add="软件授权卡">加入购物袋</button>

</div></article>

<article class="card" data-name="影音会员卡" data-cat="会员">

<div class="ico">▶️</div><span class="tag">会员权益</span>

<h3>影音会员卡</h3><p class="desc">影音会员商品展示位，具体平台和权益以实际为准。</p>

<div class="price">¥39 <small>起 / 份</small></div>

<div class="actions">

<button class="detail" data-info="影音会员卡|请填写平台、会员期限及官方允许的转让方式。">商品详情</button>

<button class="add" data-add="影音会员卡">加入购物袋</button>

</div></article>

<article class="card" data-name="充值卡券" data-cat="卡券">

<div class="ico">💳</div><span class="tag">数字卡券</span>

<h3>充值卡券</h3><p class="desc">其他正规数字充值卡券展示位，可按品类扩展。</p>

<div class="price">¥20 <small>起 / 张</small></div>

<div class="actions">

<button class="detail" data-info="充值卡券|请填写发行方、充值范围、面值、有效期与售后政策。">商品详情</button>

<button class="add" data-add="充值卡券">加入购物袋</button>

</div></article>

</div>

<div class="empty" id="empty">没有找到相关商品。</div>

</section>

<section id="service">

<div class="head"><div><div class="kicker">THE CRAB BOSS STANDARD</div><h2>用心做好每一份服务</h2></div></div>

<div class="features">

<div class="feature">✦<b>商品信息清楚</b><p>价格、权益、适用范围和使用条件清晰展示。</p></div>

<div class="feature">◇<b>手机浏览顺畅</b><p>针对手机与电脑屏幕自适应，浏览体验一致。</p></div>

<div class="feature">盾<b>重视交易安全</b><p>请通过正规渠道购买，不索取银行卡密码或短信验证码。</p></div>

</div>

</section>

<section id="contact">

<div class="contact">

<div><h2>有疑问？找蟹老板</h2><p>商品咨询、购买须知与售后问题，请通过店铺正式公布的客服渠道联系。</p></div>

<button class="btn primary" id="contactBtn">客服咨询说明</button>

</div>

</section>

</main>

<footer><div class="wrap">© 2026 蟹老板卡商 · CRAB BOSS<br>数字商品展示页面 · 商品以实际说明为准</div></footer>

<dialog id="modal">

<button id="close" class="filter">关闭</button>

<h3 id="mt"></h3><p id="md"></p>

</dialog>

<div class="toast" id="toast"></div>

<script>

let count=0,cat='全部';

const $=s=>document.querySelector(s);

function toast(t){

let e=$('#toast');e.textContent=t;e.classList.add('show');

setTimeout(()=>e.classList.remove('show'),2200)

}

function update(){

let q=$('#search').value.trim().toLowerCase(),n=0;

document.querySelectorAll('.card').forEach(c=>{

let ok=(cat==='全部'||c.dataset.cat===cat)&&c.innerText.toLowerCase().includes(q);

c.hidden=!ok;if(ok)n++

});

$('#empty').style.display=n?'none':'block'

}

$('#search').addEventListener('input',update);

document.querySelectorAll('[data-filter]').forEach(b=>b.onclick=()=>{

cat=b.dataset.filter;

document.querySelectorAll('[data-filter]').forEach(x=>x.classList.toggle('active',x===b));

update()

});

document.querySelectorAll('[data-info]').forEach(b=>b.onclick=()=>{

let [t,d]=b.dataset.info.split('|');

$('#mt').textContent=t;$('#md').textContent=d;$('#modal').showModal()

});

$('#close').onclick=()=>$('#modal').close();

document.querySelectorAll('[data-add]').forEach(b=>b.onclick=()=>{

$('#count').textContent=++count;toast('已加入购物袋（演示功能）')

});

$('#cart').onclick=()=>toast('购物袋 '+count+' 件；暂未接入真实支付。');

$('#contactBtn').onclick=()=>toast('请在正式上线前填写真实客服联系方式。');

</script>

</body>

</html>
