# rami-watch-store
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>rami's watchs - ساعات فاخرة</title>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Cairo', sans-serif;
      margin: 0;
      background-color: #f5f3ef;
      color: #333;
    }
    header {
      background-image: url('https://upload.wikimedia.org/wikipedia/commons/3/3a/Moroccan_mosaic_arch.jpg');
      background-size: cover;
      background-position: center;
      color: white;
      padding: 60px 20px;
      text-align: center;
      box-shadow: inset 0 0 0 2000px rgba(0, 0, 0, 0.4);
    }
    header h1 {
      margin: 0;
      font-size: 3em;
      font-weight: bold;
      letter-spacing: 2px;
    }
    header p {
      font-size: 1.5em;
      margin-top: 10px;
    }
    .section-title {
      text-align: center;
      font-size: 2em;
      margin: 40px 0 20px;
      color: #5c3b24;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
      padding: 0 40px 40px;
    }
    .product {
      background-color: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      text-align: center;
      padding: 20px;
      transition: transform 0.2s;
    }
    .product:hover {
      transform: translateY(-5px);
    }
    .product img {
      width: 100%;
      border-radius: 8px;
    }
    .product h3 {
      margin: 10px 0;
      font-size: 1.3em;
    }
    .product p {
      color: #8B4513;
      font-weight: bold;
    }
    .order-button {
      background-color: #a0522d;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 6px;
      cursor: pointer;
      font-size: 1em;
      margin-top: 10px;
    }
    .info-section {
      padding: 40px;
      background-color: #fffaf2;
      line-height: 1.8;
    }
    .info-section h2 {
      text-align: center;
      color: #5c3b24;
      font-size: 1.8em;
    }
    .order-form {
      padding: 40px;
      background-color: #fcf8f3;
    }
    .order-form h2 {
      text-align: center;
      font-size: 1.8em;
      color: #5c3b24;
    }
    .order-form form {
      max-width: 500px;
      margin: auto;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    .order-form input, .order-form textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 1em;
    }
    .submit-button {
      background-color: #8B4513;
      color: white;
      border: none;
      padding: 12px;
      border-radius: 8px;
      font-size: 1em;
      cursor: pointer;
    }
    footer {
      background-color: #3e2617;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>rami's watchs</h1>
    <p>ساعات راقية بتصاميم مستوحاة من الذوق المغربي</p>
  </header>

  <h2 class="section-title">تشكيلة مختارة</h2>
  <section class="products">
    <div class="product">
      <img src="https://images.unsplash.com/photo-1608455699393-964eab3a39ea" alt="ساعة Rolex">
      <h3>ساعة تقليد رولكس فاخرة</h3>
      <p>299 درهم</p>
      <button class="order-button" onclick="scrollToForm()">اطلب الآن</button>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1616486237264-99c283be94d6" alt="ساعة Casio">
      <h3>ساعة Casio كلاسيكية</h3>
      <p>149 درهم</p>
      <button class="order-button" onclick="scrollToForm()">اطلب الآن</button>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1617715985195-c3fba5e29b1a" alt="ساعة Palet">
      <h3>ساعة Palet أنيقة</h3>
      <p>189 درهم</p>
      <button class="order-button" onclick="scrollToForm()">اطلب الآن</button>
    </div>
  </section>

  <section class="info-section">
    <h2>من نحن</h2>
    <p>
      في Rami Fragrances، نؤمن أن الأناقة تبدأ من التفاصيل. نحن متجر إلكتروني متخصص في بيع الساعات الرجالية الكلاسيكية والفخمة بتصاميم راقية وجودة عالية، نقدم لكم نخبة مختارة من الساعات بتقليد درجة أولى لتجمع بين المظهر الفاخر والسعر المناسب.<br><br>
      نستهدف عشاق الأناقة والمهتمين بالساعات المميزة الذين يقدّرون الذوق الرفيع والتفاصيل الدقيقة. نحرص في Rami Fragrances على توفير تجربة تسوّق استثنائية من خلال:<br>
      <ul>
        <li>جودة المنتجات المختارة بعناية</li>
        <li>سرعة التوصيل إلى مختلف مناطق المملكة</li>
        <li>خدمة ما بعد البيع لضمان رضا العملاء</li>
      </ul>
      نوفر خيار الدفع عند الاستلام لراحتكم، ونسعد بتواصلكم معنا عبر حسابنا على إنستغرام:<br>
      <a href="https://www.instagram.com/ramiselectronic?igsh=Mm45c2N3OHg5NDc3" target="_blank">@ramiselectronic</a><br><br>
      Rami Fragrances — حيث تلتقي الفخامة بالثقة.
    </p>
  </section>

  <section class="info-section">
    <h2>اتصل بنا</h2>
    <p>
      📞 رقم الهاتف: +212714399245<br>
      📧 البريد الإلكتروني: ar3613541@gmail.com<br>
      📱 إنستغرام: <a href="https://www.instagram.com/ramiselectronic?igsh=Mm45c2N3OHg5NDc3" target="_blank">@ramiselectronic</a>
    </p>
  </section>

  <section class="order-form" id="order">
    <h2>نموذج الطلب</h2>
    <form action="https://formsubmit.co/ar3613541@gmail.com" method="POST">
      <input type="text" name="name" placeholder="الاسم الكامل" required>
      <input type="tel" name="phone" placeholder="رقم الهاتف" required>
      <input type="text" name="address" placeholder="المدينة + العنوان" required>
      <textarea name="notes" rows="4" placeholder="ملاحظات (اختياري)"></textarea>
      <input type="hidden" name="_subject" value="طلب جديد من rami's watchs">
      <button class="submit-button" type="submit">تأكيد الطلب - الدفع عند الاستلام</button>
    </form>
  </section>

  <footer>
    &copy; 2025 rami's watchs — تصميم مستوحى من الذوق المغربي وأناقة الساعات المميزة
  </footer>

  <script>
    function scrollToForm() {
      document.getElementById("order").scrollIntoView({ behavior: 'smooth' });
    }
  </script>
</body>
</html>
