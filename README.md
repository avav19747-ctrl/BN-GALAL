<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>متجر الأحذية</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f5f5f5;
      color: #111;
    }

    header {
      background: #111;
      color: white;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      font-size: 28px;
    }

    .hero {
      padding: 35px 20px;
      text-align: center;
      background: white;
    }

    .hero h2 {
      font-size: 30px;
      margin-bottom: 10px;
    }

    .hero p {
      color: #666;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      padding: 25px;
      max-width: 1100px;
      margin: auto;
    }

    .product {
      background: white;
      border-radius: 15px;
      padding: 15px;
      box-shadow: 0 3px 12px #0001;
      text-align: center;
    }

    .product img {
      width: 100%;
      height: 220px;
      object-fit: cover;
      border-radius: 12px;
      background: #eee;
    }

    .product h3 {
      margin: 12px 0 7px;
    }

    .price {
      font-size: 20px;
      font-weight: bold;
      margin-bottom: 12px;
    }

    button {
      border: none;
      background: #111;
      color: white;
      padding: 12px 22px;
      border-radius: 8px;
      cursor: pointer;
    }

    button:hover {
      background: #333;
    }

    footer {
      text-align: center;
      padding: 25px;
      margin-top: 30px;
      background: #111;
      color: white;
    }
  </style>
</head>

<body>

<header>
  <h1>متجر الأحذية 👟</h1>
</header>

<section class="hero">
  <h2>اختار حذائك المفضل</h2>
  <p>أحدث الأحذية بأسعار مناسبة</p>
</section>

<section class="products">

  <div class="product">
    <img src="https://via.placeholder.com/500x500?text=Shoe+1">
    <h3>حذاء رياضي 1</h3>
    <div class="price">120 د.ل</div>
    <button>أضف للسلة</button>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/500x500?text=Shoe+2">
    <h3>حذاء رياضي 2</h3>
    <div class="price">150 د.ل</div>
    <button>أضف للسلة</button>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/500x500?text=Shoe+3">
    <h3>حذاء رياضي 3</h3>
    <div class="price">180 د.ل</div>
    <button>أضف للسلة</button>
  </div>

</section>

<footer>
  © 2026 متجر الأحذية
</footer>

</body>
</html>
