[index.html](https://github.com/user-attachments/files/24343331/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Prime Gems</title>

  <style>
    body {
      margin: 0;
      font-family: Georgia, serif;
      background-color: #f4f4f4;
      color: #222;
    }

    /* ===== Banner ===== */
    .banner {
      background-image: url("banner.jpg");
      background-size: cover;
      background-position: center;
      height: 320px;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .overlay {
      background: rgba(0, 0, 0, 0.6);
      padding: 30px 60px;
      border-radius: 12px;
      text-align: center;
    }

    .overlay h1 {
      color: #f5d27a;
      font-size: 3em;
      margin: 0;
      letter-spacing: 2px;
    }

    .overlay p {
      color: #ddd;
      margin-top: 10px;
    }

    /* ===== Products ===== */
    .container {
      max-width: 1200px;
      margin: auto;
      padding: 50px 20px;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 30px;
    }

    .product {
      background: white;
      border-radius: 12px;
      padding: 20px;
      text-align: center;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
    }

    .product img {
      width: 100%;
      height: 220px;
      object-fit: cover;
      border-radius: 10px;
    }

    .product h3 {
      margin: 15px 0 5px;
    }

    .price {
      font-weight: bold;
      color: #6a4cff;
      margin: 10px 0;
    }

    .display {
      background: #ddd;
      border: none;
      padding: 10px 18px;
      border-radius: 6px;
      cursor: default;
    }

    /* ===== Footer ===== */
    footer {
      background: #0f0f0f;
      color: white;
      text-align: center;
      padding: 25px;
      font-size: 0.9em;
    }
  </style>
</head>

<body>

  <!-- Banner -->
  <header class="banner">
    <div class="overlay">
      <h1>PRIME GEMS</h1>
      <p>Luxury • Authentic • Hand-Selected Gemstones</p>
    </div>
  </header>

  <!-- Products -->
  <div class="container">
    <div class="products">

      <div class="product">
        <img src="https://images.unsplash.com/photo-1600172454284-934feca24ccd" alt="Amethyst">
        <h3>Amethyst Gem</h3>
        <p class="price">$45.00</p>
        <button class="display">Display Only</button>
      </div>

      <div class="product">
        <img src="https://images.unsplash.com/photo-1602526216433-4aafda43a7a6" alt="Emerald">
        <h3>Mclaren Logo Necklace</h3>
        <p class="price">$120.00</p>
        <button class="display">Display Only</button>
      </div>

      <div class="product">
        <img src="https://images.unsplash.com/photo-1617040619263-41c5a9cbbd62" alt="Ring">
        <h3>Surgical Metal Ring </h3>
        <p class="price">$65.00</p>
        <button class="display">Display Only</button>
      </div>

    </div>
  </div>

  <!-- Footer -->
  <footer>
    © 2025 Prime Gems • Display Website
  </footer>

</body>
</html>
