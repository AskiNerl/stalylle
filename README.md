<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Style - Онлайн магазин</title>
  <!-- Подключение AOS -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }
    body {
      background: #f4f4f4;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #111;
      color: white;
      padding: 1.5rem;
      text-align: center;
    }
    header h1 {
      font-size: 2.5rem;
    }
    header p {
      font-size: 1.2rem;
      color: #ddd;
    }
    .main-section {
      padding: 2rem;
      text-align: center;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
      margin-top: 30px;
    }
    .product-card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      transition: transform 0.3s ease;
    }
    .product-card img {
      width: 100%;
      height: 250px; /* Устанавливаем одинаковую высоту для всех картинок */
      object-fit: cover; /* Сохраняем пропорции изображения */
    }
    .product-card:hover {
      transform: translateY(-10px);
    }
    .product-info {
      padding: 1rem;
    }
    .product-info h3 {
      font-size: 1.4rem;
      margin-bottom: 0.5rem;
    }
    .product-info p {
      color: #666;
      margin-bottom: 0.5rem;
    }
    .product-info .price {
      font-size: 1.6rem;
      font-weight: bold;
      color: #0c9cde;
    }
    .footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
    .contact-section {
      background: #0c9cde;
      color: white;
      padding: 3rem 1rem;
      text-align: center;
    }
    .contact-section h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }
    .contact-section ul {
      list-style: none;
      padding: 0;
    }
    .contact-section li {
      margin: 1rem 0;
    }
    .contact-section a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .contact-section a:hover {
      text-decoration: underline;
    }

    /* Стили для кнопок */
    .product-info button {
      background-color: #0c9cde;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
      transition: background-color 0.3s ease, transform 0.3s ease;
    }

    .product-info button:hover {
      background-color: #0277bd;
      transform: translateY(-3px);
    }

    .product-info button:active {
      background-color: #01579b;
      transform: translateY(1px);
    }

    .product-info button:focus {
      outline: none;
      box-shadow: 0 0 5px rgba(12, 156, 222, 0.5);
    }
  </style>
  <header data-aos="fade-down" data-aos-duration="1000">
    <img src="photo_2025-04-12_18-09-22.jpg" alt="Style logo" style="width: 80px; height: auto; margin-bottom: 10px;">
  </header>  
</head>
<body>
  <header data-aos="fade-down" data-aos-duration="1000">
    <h1>Style</h1>
    <p>Магазин модної та стильної одягу</p>
  </header>

  <section class="main-section">
    <h2 data-aos="fade-up" data-aos-duration="1000">Наші Продукти</h2>
    <div class="products">
      <!-- Продукт 1 -->
      <div class="product-card" data-aos="zoom-in" data-aos-duration="1000" data-aos-delay="100">
        <img src="photo_2025-04-12_18-06-48.jpg" alt="Кофта">
        <div class="product-info">
          <h3>Стильна кофта</h3>
          <p>М'яка та комфортна кофта для кожного сезону.</p>
          <p class="price">₴550</p>
          <button onclick="window.location.href='https://t.me/Vledik2109'">Замовити</button>
        </div>
      </div>

      <!-- Продукт 2 -->
      <div class="product-card" data-aos="zoom-in" data-aos-duration="1000" data-aos-delay="200">
        <img src="photo_2025-04-12_18-06-41.jpg" alt="Світлі кроси">
        <div class="product-info">
          <h3>Світлі кроси</h3>
          <p>Яскравий кольор  для будь-якого настрою.</p>
          <p class="price">₴1250</p>
          <button onclick="window.location.href='https://t.me/Vledik2109'">Замовити</button>
        </div>
      </div>

      <!-- Продукт 3 -->
      <div class="product-card" data-aos="zoom-in" data-aos-duration="1000" data-aos-delay="400">
        <img src="photo_2024-10-31_18-56-33.jpg" alt="Чорні кроси ">
        <div class="product-info">
          <h3>Чорні кроси</h3>
          <p>Легкі та стильні для літа.</p>
          <p class="price">₴1350</p>
          <button onclick="window.location.href='https://t.me/Vledik2109'">Замовити</button>
        </div>
      </div>

      <!-- Продукт 4 -->
      <div class="product-card" data-aos="zoom-in" data-aos-duration="1000" data-aos-delay="500">
        <img src="photo_2024-11-15_17-33-26.jpg" alt="Чоловічі труси" >
        <div class="product-info">
          <h3>Елегантні  труси </h3>
          <p>Для особливих випадків та вечірок.</p>
          <p class="price">₴200</p>
          <button onclick="window.location.href='https://t.me/Vledik2109'">Замовити</button>
        </div>
      </div>

      <!-- Продукт 5 -->
      <div class="product-card" data-aos="zoom-in" data-aos-duration="1000" data-aos-delay="600">
        <img src="photo_2024-12-08_17-00-44.jpg" alt="Крабики для волосся">
        <div class="product-info">
          <h3>Модні крабики</h3>
          <p>Крабики для активного та повсякденного життя.</p>
          <p class="price">₴50</p>
          <button onclick="window.location.href='https://t.me/Vledik2109'">Замовити</button>
        </div>
      </div>

      <!-- Продукт 6 -->
      <div class="product-card" data-aos="zoom-in" data-aos-duration="1000" data-aos-delay="700">
        <img src="photo_2024-11-15_19-43-36.jpg" alt="Сірі капці">
        <div class="product-info">
          <h3>Сірі капці  </h3>
          <p>Комфортні та дуже пухнасті.</p>
          <p class="price">₴800</p>
          <button onclick="window.location.href='https://t.me/Vledik2109'">Замовити</button>
        </div>
      </div>
    </div>
  </section>

  <section class="contact-section">
    <h2>Контакти та Технічна Підтримка</h2>
    <ul>
      <li>📱 Телефон: +380954827975</li>
      <li>📩 Email: <a href="mailto:vladikkxom@gmail.com">vladikkxom@gmail.com</a></li>
      <li>💬 Telegram: <a href="https://t.me/Vledik2109">@vled</a></li>
    </ul>
    <h3>Для замовлення зв'яжіться з нами в Telegram</h3>
  </section>

  <footer data-aos="fade-up" data-aos-duration="1000" class="footer">
    <p>&copy; 2025 Style. All rights reserved.</p>
  </footer>

  <!-- Подключаем скрипт для AOS -->
  <script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
  <script>
    // Инициализация AOS
    AOS.init();
  </script>
</body>
</html>
