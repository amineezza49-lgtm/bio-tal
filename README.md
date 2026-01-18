<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BIO TAL - ERECPLUS</title>

<style>
body{
    margin:0;
    font-family: 'Tahoma', sans-serif;
    background:#000;
    color:#fff;
}
.container{
    width:100%;
    max-width:420px;
    margin:auto;
}
.section{
    padding:20px;
}
.green{color:#7BC043;}
.btn{
    display:block;
    background:#7BC043;
    color:#fff;
    text-align:center;
    padding:15px;
    border-radius:30px;
    font-size:20px;
    text-decoration:none;
    margin:15px 0;
}
.price{
    background:#1f8f3a;
    padding:15px;
    border-radius:15px;
    text-align:center;
}
.price del{color:#ff8080;}
.features li{
    margin:10px 0;
}
.card{
    background:#fff;
    color:#000;
    padding:15px;
    border-radius:15px;
    margin:15px 0;
}
.form input, .form button{
    width:100%;
    padding:12px;
    margin:8px 0;
    border-radius:8px;
    border:none;
    font-size:16px;
}
.form button{
    background:#7BC043;
    color:#fff;
}
.badge{
    background:#7BC043;
    color:#fff;
    display:inline-block;
    padding:8px 15px;
    border-radius:20px;
    margin:5px;
}
.timer{
    font-size:22px;
    margin-top:10px;
}
footer{
    background:#7BC043;
    color:#000;
    text-align:center;
    padding:20px;
}
img{
    max-width:100%;
}
</style>
</head>

<body>

<div class="container">

<!-- HERO -->
<div class="section">
    <h2 class="green">منتج صحي طبيعي 💚</h2>
    <h1>دعم الحيوية والطاقة للرجال</h1>
    <p>اكتشف كبسولات BIO TAL الطبيعية</p>
    ⭐⭐⭐⭐⭐
    <img src="https://i.imgur.com/5JQ9Z5M.png" alt="product">
</div>

<!-- OFFER -->
<div class="section price">
    <h3>🔥 عرض خاص اليوم فقط 🔥</h3>
    <p><del>299 درهم</del></p>
    <h2>230 درهم فقط</h2>
    <div class="timer">⏳ الوقت المتبقي: <span id="countdown"></span></div>
</div>

<!-- FEATURES -->
<div class="section">
    <ul class="features">
        <li>✔️ منتج طبيعي 100%</li>
        <li>✔️ نتائج مجربة</li>
        <li>✔️ توصيل لجميع المدن</li>
        <li>✔️ الدفع عند الاستلام</li>
    </ul>
</div>

<!-- WHY -->
<div class="section">
    <h2 class="green">لماذا BIO TAL ؟</h2>
    <div class="badge">1 تطوير الأداء الرجولي</div>
    <div class="badge">2 زيادة الطاقة والنشاط</div>
    <div class="badge">3 مكونات طبيعية فعالة</div>
</div>

<!-- USAGE -->
<div class="section">
    <h2>طريقة الاستعمال</h2>
    <p>1️⃣ كبسولة بعد الفطور</p>
    <p>2️⃣ شرب كمية كافية من الماء</p>
    <p>3️⃣ الاستمرار يومياً</p>
</div>

<!-- FORM -->
<div class="section card">
    <h2 class="green">اطلب الآن</h2>
    <form class="form">
        <input type="text" placeholder="الاسم الكامل" required>
        <input type="tel" placeholder="رقم الهاتف" required>
        <input type="text" placeholder="المدينة" required>
        <button type="submit">تأكيد الطلب</button>
    </form>
</div>

<!-- CTA -->
<a href="#form" class="btn">🟢 أطلب الآن</a>

</div>

<footer>
    حاصل على شهادة ONSSA - HALAL - MMPS<br>
    منتج مضمون ومراقب في المغرب
</footer>

<script>
let time = 15 * 60;
setInterval(() => {
    let minutes = Math.floor(time / 60);
    let seconds = time % 60;
    document.getElementById("countdown").innerHTML =
        minutes + ":" + (seconds < 10 ? "0" : "") + seconds;
    time--;
    if(time < 0) time = 15 * 60;
}, 1000);
</script>

</body>
</html>
