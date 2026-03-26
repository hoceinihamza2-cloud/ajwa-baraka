<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>عجوة البركة</title>

<style>
body {
    font-family: Arial;
    margin: 0;
    background: #fff8f0;
}

/* HEADER */
.header {
    background: #8b4513;
    color: white;
    padding: 15px;
    text-align: center;
    font-size: 22px;
}

/* PRODUCT */
.product {
    max-width: 500px;
    margin: auto;
    padding: 15px;
}

.product img {
    width: 100%;
    border-radius: 10px;
}

.price {
    color: #8b4513;
    font-size: 22px;
    font-weight: bold;
    margin: 10px 0;
}

/* FORM */
.form {
    background: white;
    padding: 15px;
    border-radius: 10px;
    margin-top: 20px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

input, select {
    width: 100%;
    padding: 10px;
    margin-top: 10px;
    border-radius: 8px;
    border: 1px solid #ccc;
}

/* BUTTON */
button {
    width: 100%;
    padding: 12px;
    background: #25d366;
    color: white;
    border: none;
    border-radius: 10px;
    margin-top: 15px;
    font-size: 16px;
}

/* FOOTER */
footer {
    text-align: center;
    padding: 20px;
    color: #8b4513;
}
</style>
</head>

<body>

<div class="header">
🌾 عجوة البركة 🍯
</div>

<div class="product">
    
    <h2>باقة المدينة المباركة</h2>
    
    <img src="https://i.imgur.com/YourAjwaImage.jpg">

    <p>
    عجوة المدينة + عسل الحبة السوداء + ماء زمزم  
    منتجات أصلية 100% بجودة عالية
    </p>

    <div class="price">السعر: 4900 دج</div>

    <div class="form">
        <h3>اطلب الآن</h3>

        <input type="text" placeholder="الاسم الكامل">
        <input type="tel" placeholder="📞 رقم الهاتف">
        <input type="text" placeholder="🏠 العنوان">

        <select>
            <option>اختر الولاية</option>
            <option>الجزائر</option>
            <option>البليدة</option>
            <option>وهران</option>
        </select>

        <button onclick="sendWhatsApp()">تأكيد الطلب</button>
    </div>
</div>

<footer>
📞 0699091938
</footer>

<script>
function sendWhatsApp(){
    var url = "https://wa.me/213699091938?text=مرحبا اريد طلب باقة المدينة";
    window.open(url, '_blank');
}
</script>

</body>
</html>
