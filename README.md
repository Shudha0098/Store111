<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shudha Accessories Store</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f8f8f8;
      margin: 0;
      padding: 0;
    }
    header {
      background: #111;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      overflow: hidden;
      text-align: center;
      transition: 0.3s;
    }
    .card:hover {
      transform: scale(1.03);
    }
    .card img {
      width: 100%;
      height: 220px;
      object-fit: cover;
    }
    .card h3 {
      margin: 10px 0;
      font-size: 18px;
    }
    .card p {
      font-size: 14px;
      color: #555;
    }
    .price {
      font-size: 16px;
      font-weight: bold;
      margin: 10px 0;
    }
    .btn {
      display: inline-block;
      background: #25d366;
      color: white;
      padding: 10px 15px;
      margin: 10px 0;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
    }
    .btn:hover {
      background: #1ebe57;
    }
  </style>
</head>
<body>
  <header>
    <h1>Shudha Accessories Store</h1>
    <p>Luxury • Casual • Sport • Simple</p>
  </header>

  <div class="container">
    <!-- Example Product 1 -->
    <div class="card">
      <img src="Watch.jpg" alt="Luxury Watch">
      <h3>Luxury Watch</h3>
      <p>Premium stainless steel watch with sapphire glass.</p>
      <div class="price">₹4,999</div>
      <a class="btn" 
         href="https://wa.me/919825298371?text=Hello%2C%20I%20want%20to%20order%20the%20Luxury%20Watch%20priced%20at%20%E2%82%B94%2C999.%20Here%20is%20the%20picture%3A%20Watch1.jpg" 
         target="_blank">Order on WhatsApp</a>
    </div>

    <!-- Example Product 2 -->
    <div class="card">
      <img src="watch2.jpg" alt="Sport Watch">
      <h3>Sport Watch</h3>
      <p>Durable water-resistant watch perfect for athletes.</p>
      <div class="price">₹2,499</div>
      <a class="btn" 
         href="https://wa.me/91XXXXXXXXXX?text=Hello%2C%20I%20want%20to%20order%20the%20Sport%20Watch%20priced%20at%20%E2%82%B92%2C499.%20Here%20is%20the%20picture%3A%20watch2.jpg" 
         target="_blank">Order on WhatsApp</a>
    </div>

    <!-- Add more products the same way -->
  </div>
</body>
</html>
