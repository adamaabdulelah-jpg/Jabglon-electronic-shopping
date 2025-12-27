# Jabglon-electronic-shopping
Fast Easy security
الهيكل البرمجي المقترح (HTML + CSS + JS)
<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>متجري الإلكتروني</title>
<style>
body{font-family:'Tahoma';margin:0;padding:0;background:#f5f5f5;}
header{background:#222;color:#fff;padding:15px;text-align:center;}
.container{width:90%;margin:auto;}
.product{background:#fff;padding:10px;margin:10px;border-radius:5px;display:inline-block;width:200px;vertical-align:top;}
.product img{width:100%;height:150px;object-fit:cover;border-radius:5px;}
button{background:#007bff;color:#fff;border:none;padding:10px;border-radius:5px;cursor:pointer;}
button:hover{background:#0056b3;}
</style>
</head>
<body>
<header>
<h1>متجري الإلكتروني</h1>
<input type="text" placeholder="ابحث عن منتج...">
<button>بحث</button>
</header>
<div class="container">
<div class="product">
<img src="https://via.placeholder.com/200" alt="منتج">
<h3>اسم المنتج</h3>
<p>السعر: 100 ريال</p>
<p>المدينة: الرياض</p>
<button>تواصل مع البائع</button>
</div>
<div class="product">
<img src="https://via.placeholder.com/200" alt="منتج">
<h3>اسم المنتج</h3>
<p>السعر: 250 ريال</p>
<p>المدينة: جدة</p>
<button>تواصل مع البائع</button>
</div>
</div>
</body>
</html>
