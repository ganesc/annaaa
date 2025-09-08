<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>🌟 Lampop – Magical Lamp ✨</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #fffaf0, #ffe6f0);
      color: #333;
      text-align: center;
    }
    header {
      background: linear-gradient(90deg, #ffb347, #ff6f61);
      padding: 25px;
      border-bottom: 4px solid #ff6f61;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      color: #fff;
      animation: glow 2s infinite alternate;
    }
    @keyframes glow {
      from { text-shadow: 0 0 10px #fff; }
      to { text-shadow: 0 0 25px #ffe66d, 0 0 35px #ff6f61; }
    }
    header p {
      margin: 8px 0 0;
      font-size: 1.1rem;
      color: #fff;
    }
    .product {
      margin: 40px auto;
      max-width: 550px;
      background: #fff;
      padding: 25px;
      border-radius: 20px;
      box-shadow: 0 8px 25px rgba(0,0,0,0.1);
      transition: 0.3s;
    }
    .product:hover {
      transform: scale(1.02);
    }
    .product img {
      width: 100%;
      border-radius: 15px;
    }
    .product h2 {
      font-size: 2rem;
      margin: 15px 0 10px;
      color: #ff6f61;
    }
    .product p {
      font-size: 1rem;
      margin: 12px 0;
      line-height: 1.6;
    }
    .price {
      font-size: 1.6rem;
      font-weight: bold;
      margin: 20px 0;
      color: #222;
    }
    .buy-btn {
      display: inline-block;
      background: linear-gradient(90deg, #ff6f61, #ff3b2e);
      color: #fff;
      padding: 14px 30px;
      border-radius: 35px;
      text-decoration: none;
      font-size: 1.2rem;
      transition: 0.3s;
      animation: bounce 2s infinite;
    }
    .buy-btn:hover {
      background: linear-gradient(90deg, #ff3b2e, #ff6f61);
    }
    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-5px); }
    }
    footer {
      margin-top: 50px;
      padding: 20px;
      font-size: 0.95rem;
      background: linear-gradient(90deg, #ffb347, #ff6f61);
      color: #fff;
    }
  </style>
</head>
<body>
  <header>
    <h1>🌟 Lampop – Magical Lamp ✨</h1>
    <p>Light up your home with love 💖, joy 😊, and style 🌸</p>
  </header>

  <section class="product">
    <img src="https://images.unsplash.com/photo-1603898037225-2a5f56a59d15?auto=format&fit=crop&w=800&q=80" alt="Lampop Magical Lamp" />
    <h2>✨ Magical Lamp for Kids & Family 🏡</h2>
    <p>
      🌈 Transform your nights into a fairy tale! <br>
      🎉 Perfect for kids, parents & gifts 🎁 <br>
      💡 Soft glow that makes evenings magical ✨ <br>
      🌸 Adds beauty, warmth & happiness to every home 🏠
    </p>
    <div class="price">Only ₹499 🔥</div>
    <a class="buy-btn" href="https://wa.me/918888888888?text=Hi%20I%20want%20to%20order%20Lampop%20Lamp%20✨">🛒 Buy Now</a>
  </section>

  <footer>
    © 2025 Lampop | Made with ❤️ to brighten lives ✨
  </footer>
</body>
</html>
