<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Shop</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f9;
      margin: 0;
      padding: 0;
      text-align: center;
    }

    header {
      background: #333;
      color: white;
      padding: 20px;
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
      width: 220px;
      border-radius: 12px;
      box-shadow: 0 3px 6px rgba(0,0,0,0.1);
    }

    .product img {
      max-width: 100%;
      border-radius: 10px;
    }

    .price {
      font-size: 18px;
      color: #333;
      margin: 10px 0;
    }

    button {
      background: #27ae60;
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-size: 16px;
    }

    button:hover {
      background: #219150;
    }
  </style>
</head>
<body>

  <header>
    <h1>🛍️ My Custom Shop</h1>
    <p>Choose your favorite items below</p>
  </header>

  <div class="products">

    <!-- PRODUCT 1 -->
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Your Product">
      <h2>Product Name</h2>
      <p class="price">$19.99</p>
      <form action="https://www.paypal.com/buy" method="post" target="_blank">
        <input type="hidden" name="item_name" value="Product Name">
        <input type="hidden" name="amount" value="19.99">
        <input type="hidden" name="currency_code" value="USD">
        <button type="submit">Buy Now</button>
      </form>
    </div>

    <!-- PRODUCT 2 -->
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Your Product">
      <h2>Another Product</h2>
      <p class="price">$29.99</p>
      <form action="https://www.paypal.com/buy" method="post" target="_blank">
        <input type="hidden" name="item_name" value="Another Product">
        <input type="hidden" name="amount" value="29.99">
        <input type="hidden" name="currency_code" value="USD">
        <button type="submit">Buy Now</button>
      </form>
    </div>

    <!-- PRODUCT 3 -->
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Your Product">
      <h2>Third Product</h2>
      <p class="price">$39.99</p>
      <form action="https://www.paypal.com/buy" method="post" target="_blank">
        <input type="hidden" name="item_name" value="Third Product">
        <input type="hidden" name="amount" value="39.99">
        <input type="hidden" name="currency_code" value="USD">
        <button type="submit">Buy Now</button>
      </form>
    </div>

  </div>

</body>
</html>
