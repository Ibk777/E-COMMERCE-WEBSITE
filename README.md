<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jimmy Visuals</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; background: #0f172a; color: white; }
    header { background: #020617; padding: 15px; text-align: center; }
    header h1 { margin: 0; color: gold; }
    .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; padding: 20px; }
    .card { background: #1e293b; padding: 15px; border-radius: 10px; text-align: center; }
    .card img { width: 100%; border-radius: 10px; }
    button { background: gold; border: none; padding: 10px; margin-top: 10px; cursor: pointer; }
    footer { text-align: center; padding: 10px; background: #020617; }
  </style>
</head>
<body>

<header>
  <h1>JIMMY VISUALS</h1>
  <p>Premium Visual Products & Media Assets</p>
</header>

<section class="products">
  <div class="card">
    <img src="https://via.placeholder.com/300" alt="Product">
    <h3>Video Editing Pack</h3>
    <p>$25</p>
    <button onclick="addToCart('Video Editing Pack')">Add to Cart</button>
  </div>

  <div class="card">
    <img src="https://via.placeholder.com/300" alt="Product">
    <h3>Livestream Overlay Kit</h3>
    <p>$30</p>
    <button onclick="addToCart('Livestream Overlay Kit')">Add to Cart</button>
  </div>

  <div class="card">
    <img src="https://via.placeholder.com/300" alt="Product">
    <h3>Social Media Templates</h3>
    <p>$15</p>
    <button onclick="addToCart('Social Media Templates')">Add to Cart</button>
  </div>
</section>

<footer>
  <p>© 2026 Jimmy Visuals. All rights reserved.</p>
</footer>

<script>
  function addToCart(product) {
    alert(product + " added to cart!");
  }
</script>

</body>
</html>
