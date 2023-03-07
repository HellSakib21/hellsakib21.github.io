
<html>
  <head>
    <meta charset="UTF-8">
    <title>Shopping Website</title>
    <link rel="stylesheet" type="text/css" href="style.css">
  </head>
  <body>
    <header>
      <h1>Shopping Website</h1>
    </header>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Products</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
    <main>
      <h2>Our Products</h2>
      <div class="product-grid">
        <div class="product-card">
          <img src="product1.jpg" alt="Product 1">
          <h3>Product 1</h3>
          <p>$10.99</p>
          <button class="add-to-cart-btn" onclick="addToCart('Product 1', 10.99)">Add to Cart</button>
        </div>
        <div class="product-card">
          <img src="product2.jpg" alt="Product 2">
          <h3>Product 2</h3>
          <p>$19.99</p>
          <button class="add-to-cart-btn" onclick="addToCart('Product 2', 19.99)">Add to Cart</button>
        </div>
        <div class="product-card">
          <img src="product3.jpg" alt="Product 3">
          <h3>Product 3</h3>
          <p>$29.99</p>
          <button class="add-to-cart-btn" onclick="addToCart('Product 3', 29.99)">Add to Cart</button>
        </div>
      </div>
    </main>
    <footer>
      <p>&copy; 2023 Shopping Website</p>
    </footer>
    <script src="app.js"></script>
  </body>
</html>
