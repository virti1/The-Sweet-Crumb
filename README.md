# The-Sweet-Crumb-website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The Sweet Crumb - Jain Bakery</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to bottom right, #f8d4f0, #e1c6f3);
      color: #4a004a;
    }
    header {
      background-color: #d4a5f8;
      color: white;
      text-align: center;
      padding: 2rem;
    }
    header h1 {
      margin: 0;
      font-size: 3rem;
    }
    nav {
      background-color: #f4b4e1;
      padding: 1rem;
      text-align: center;
    }
    nav a {
      color: #4a004a;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 2rem;
    }
    .product-section {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      justify-content: center;
    }
    .product-card {
      background-color: #ffffffdd;
      border-radius: 1rem;
      padding: 1rem;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      max-width: 300px;
      text-align: center;
      flex: 1 1 280px;
    }
    .product-card img {
      width: 100%;
      border-radius: 1rem;
      margin-bottom: 1rem;
    }
    .product-card h3 {
      margin-bottom: 0.5rem;
    }
    .contact-box {
      background-color: #f4d9f8;
      padding: 2rem;
      border-radius: 1rem;
      text-align: center;
      margin-top: 2rem;
    }
    footer {
      background-color: #d4a5f8;
      text-align: center;
      padding: 1rem;
      color: white;
      margin-top: 2rem;
    }
    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
      nav a {
        display: block;
        margin: 0.5rem 0;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>The Sweet Crumb</h1>
    <p>Delicious Eggless Jain Bakery Treats</p>
  </header>
  <nav>
    <a href="#donuts">Donuts</a>
    <a href="#bombolinis">Bombolinis</a>
    <a href="#bread">Bread & Pav</a>
    <a href="#contact">Contact</a>
  </nav>
  <section id="donuts">
    <h2>Our Donuts - Rs. 40 each</h2>
    <div class="product-section">
      <div class="product-card">
        <img src="https://source.unsplash.com/300x200/?dark-chocolate-donut" alt="Dark Chocolate Donut">
        <h3>Dark Chocolate Donut</h3>
        <p>Rich and decadent</p>
      </div>
      <div class="product-card">
        <img src="https://source.unsplash.com/300x200/?milk-chocolate-donut" alt="Milk Chocolate Donut">
        <h3>Milk Chocolate Donut</h3>
        <p>Smooth and creamy</p>
      </div>
      <div class="product-card">
        <img src="https://source.unsplash.com/300x200/?chocolate-donut" alt="Mixed Chocolate Donut">
        <h3>Mixed Chocolate Donut</h3>
        <p>Perfect blend of chocolates</p>
      </div>
    </div>
  </section>
  <section id="bombolinis">
    <h2>Our Bombolinis - Rs. 100 each</h2>
    <div class="product-section">
      <div class="product-card">
        <img src="https://source.unsplash.com/300x200/?white-chocolate-donut" alt="White Chocolate Bombolini">
        <h3>White Chocolate Bombolini</h3>
        <p>Delightfully sweet</p>
      </div>
      <div class="product-card">
        <img src="https://source.unsplash.com/300x200/?dark-chocolate-bomboloni" alt="Dark Chocolate Bombolini">
        <h3>Dark Chocolate Bombolini</h3>
        <p>Bold and rich flavor</p>
      </div>
      <div class="product-card">
        <img src="https://source.unsplash.com/300x200/?milk-chocolate-bomboloni" alt="Milk Chocolate Bombolini">
        <h3>Milk Chocolate Bombolini</h3>
        <p>Classic indulgence</p>
      </div>
    </div>
  </section>
  <section id="bread">
    <h2>Bread & Pav</h2>
    <div class="contact-box">
      <p>For pricing and orders of our Jain eggless bread and pav, please contact us directly at:</p>
      <h3>9104011468</h3>
    </div>
  </section>
  <section id="contact">
    <h2>Order Guidelines</h2>
    <p style="text-align: center; max-width: 600px; margin: auto;">
      Kindly place your orders at least <strong>5 hours</strong> in advance to ensure timely preparation and delivery of fresh items.
    </p>
  </section>
  <footer>
    <p>&copy; 2025 The Sweet Crumb. All Rights Reserved.</p>
  </footer>
</body>
</html>
