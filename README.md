# One1shirtz
premium Egyptian clothing brand
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>One1shirtz - Hoodies</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: sans-serif;
      background-color: #fff;
      color: #000;
    }
    header {
      display: flex;
      align-items: center;
      padding: 20px;
      border-bottom: 1px solid #000;
    }
    header img {
      height: 60px;
      margin-right: 20px;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
      gap: 20px;
    }
    .product-card {
      border: 1px solid #000;
      width: 300px;
      padding: 10px;
      text-align: center;
    }
    .product-card img {
      width: 100%;
      height: auto;
    }
    .product-card h2 {
      margin: 10px 0 5px 0;
      font-size: 1.25rem;
    }
    .product-card p {
      margin: 5px 0;
      font-size: 1rem;
    }
    .out-of-stock {
      color: red;
      font-weight: bold;
      margin-top: 5px;
    }
    .order-btn {
      display: block;
      width: 220px;
      margin: 30px auto;
      padding: 12px;
      text-align: center;
      text-decoration: none;
      background-color: #000;
      color: #fff;
      font-size: 1.2rem;
      border-radius: 5px;
    }
    footer {
      text-align: center;
      padding: 20px;
      border-top: 1px solid #000;
      font-size: 0.9rem;
    }
    a {
      color: #000;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <!-- Make sure logo.png is in the project folder -->
    <img src="logo.png" alt="One1shirtz Logo">
    <h1>One1shirtz</h1>
  </header>

  <!-- Products Section -->
  <section class="products">
    <!-- Product 1 -->
    <div class="product-card">
      <img src="images/hoodie1.jpg" alt="Hoodie 1">
      <h2>Hoodie 1</h2>
      <p>Price: 600 EGP</p>
      <p class="out-of-stock">Out of stock</p>
    </div>

    <!-- Product 2 -->
    <div class="product-card">
      <img src="images/hoodie2.jpg" alt="Hoodie 2">
      <h2>Hoodie 2</h2>
      <p>Price: 600 EGP</p>
      <p class="out-of-stock">Out of stock</p>
    </div>

    <!-- Product 3 -->
    <div class="product-card">
      <img src="images/hoodie3.jpg" alt="Hoodie 3">
      <h2>Hoodie 3</h2>
      <p>Price: 600 EGP</p>
      <p class="out-of-stock">Out of stock</p>
    </div>

    <!-- Product 4 -->
    <div class="product-card">
      <img src="images/hoodie4.jpg" alt="Hoodie 4">
      <h2>Hoodie 4</h2>
      <p>Price: 600 EGP</p>
      <p class="out-of-stock">Out of stock</p>
    </div>

    <!-- Product 5 -->
    <div class="product-card">
      <img src="images/hoodie5.jpg" alt="Hoodie 5">
      <h2>Hoodie 5</h2>
      <p>Price: 600 EGP</p>
      <p class="out-of-stock">Out of stock</p>
    </div>
  </section>

  <!-- Order Now Button -->
  <a href="https://wa.me/0123456789?text=I'm%20interested%20in%20buying%20a%20hoodie%20from%20One1shirtz" class="order-btn">Order Now</a>

  <!-- Footer -->
  <footer>
    <p>One1shirtz © 2025. Cash on delivery.</p>
    <p>Contact us on <a href="https://wa.me/0123456789">WhatsApp</a></p>
  </footer>

</body>
</html>
