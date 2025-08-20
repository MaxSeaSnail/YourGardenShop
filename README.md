<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Grow A Garden Shop</title>
  <style>
    body {
      font-family: "Segoe UI", sans-serif;
      background: #eafbea;
      margin: 0;
      padding: 0;
    }

    header {
      background: #2d6a4f;
      color: white;
      padding: 20px;
      text-align: center;
    }

    h1 {
      margin: 0;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin: 20px;
    }

    .product {
      background: white;
      margin: 15px;
      padding: 20px;
      width: 240px;
      border-radius: 12px;
      box-shadow: 0 3px 6px rgba(0,0,0,0.1);
      text-align: center;
      transition: transform 0.2s;
    }

    .product:hover {
      transform: scale(1.03);
    }

    .product img {
      max-width: 100%;
      border-radius: 10px;
    }

    .price {
      font-size: 18px;
      color: #2d6a4f;
      margin: 10px 0;
    }

    button {
      background: #40916c;
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-size: 16px;
    }

    button:hover {
      background: #1b4332;
    }
  </style>
</head>
<body>

  <header>
    <h1>🌱 Grow A Garden Shop</h1>
    <p>Everything you need to grow your dream garden & care for garden pets!</p>
  </header>

  <div class="products">

    <!-- PRODUCT 1 -->
    <div class="product">
      <img src="https://upload.wikimedia.org/wikipedia/commons/5/57/Tomato_je.jpg" alt="Tomato Plant">
      <h2>Tomato Plant</h2>
      <p class="price">$5.99</p>
      <form action="https://www.paypal.com/buy" method="post" target="_blank">
        <input type="hidden" name="item_name" value="Tomato Plant">
        <input type="hidden" name="amount" value="5.99">
        <input type="hidden" name="currency_code" value="USD">
        <button type="submit">Buy Now</button>
      </form>
    </div>

    <!-- PRODUCT 2 -->
    <div class="product">
      <img src="https://upload.wikimedia.org/wikipedia/commons/f/f8/Sunflower_from_Silesia2.jpg" alt="Sunflower Seeds">
      <h2>Sunflower Seeds</h2>
      <p class="price">$2.49</p>
      <form action="https://www.paypal.com/buy" method="post" target="_blank">
        <input type="hidden" name="item_name" value="Sunflower Seeds">
        <input type="hidden" name="amount" value="2.49">
        <input type="hidden" name="currency_code" value="USD">
        <button type="submit">Buy Now</button>
      </form>
    </div>

    <!-- PRODUCT 3 -->
    <div class="product">
      <img src="https://upload.wikimedia.org/wikipedia/commons/2/26/Rabbit_in_montana.jpg" alt="Garden Bunny">
      <h2>Garden Bunny</h2>
      <p class="price">$39.99</p>
      <form action="https://www.paypal.com/buy" method="post" target="_blank">
        <input type="hidden" name="item_name" value="Garden Bunny">
        <input type="hidden" name="amount" value="39.99">
        <input type="hidden" name="currency_code" value="USD">
        <button type="submit">Adopt Now</button>
      </form>
    </div>

    <!-- PRODUCT 4 -->
    <div class="product">
      <img src="https://upload.wikimedia.org/wikipedia/commons/c/c9/Garden_tools.jpg" alt="Garden Tools">
      <h2>Garden Tools Set</h2>
      <p class="price">$24.99</p>
      <form action="https://www.paypal.com/buy" method="post" target="_blank">
        <input type="hidden" name="item_name" value="Garden Tools">
        <input type="hidden" name="amount" value="24.99">
        <input type="hidden" name="currency_code" value="USD">
        <button type="submit">Buy Now</button>
      </form>
    </div>

  </div>

</body>
</html>
