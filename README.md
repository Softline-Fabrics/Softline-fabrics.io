<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Softline Unstiched fabrics</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display&family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Open Sans', sans-serif;
      background-color: #fff8f2;
      color: #333;
    }

    header {
      background: linear-gradient(to right, #8e44ad, #c0392b);
      color: white;
      padding: 60px 20px;
      text-align: center;
    }

    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 3rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    section {
      padding: 50px 20px;
      text-align: center;
    }

    .about {
      background-color: #fff;
    }

    .about h2 {
      font-size: 2rem;
      margin-bottom: 15px;
    }

    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      background-color: #fefefe;
    }

    .product h1{
      background-color: #fff;
      border-radius: 16px;
      box-shadow: 0 6px 16px rgba(0,0,0,0.1);
      margin: 20px;
      width: 280px;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .product:hover {
      transform: scale(1.05);
      box-shadow: 0 12px 24px rgba(0,0,0,0.15);
    }

    .product h2 {
      width: 100%;
      border-top-left-radius: 16px;
      border-top-right-radius: 16px;
    }

    .product h3 {
      font-family: 'Playfair Display', serif;
      margin: 15px 0 5px;
    }

    .product p {
      margin-bottom: 10px;
      color: #555;
    }

    .buy-btn {
      display: inline-block;
      margin-bottom: 15px;
      background-color: #27ae60;
      color: white;
      padding: 10px 20px;
      border-radius: 25px;
      text-decoration: none;
      transition: background 0.3s;
    }

    .buy-btn:hover {
      background-color: #219150;
    }

    footer {
      background-color: #222;
      color: #fff;
      padding: 30px 20px;
      text-align: center;
    }

    footer p {
      margin: 5px 0;
      font-size: 0.95rem;
    }

    /* WhatsApp Floating Button */
    .whatsapp-float {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: white;
      border-radius: 50%;
      padding: 15px;
      text-align: center;
      font-size: 24px;
      z-index: 100;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      transition: transform 0.3s;
    }

    .whatsapp-float:hover {
      transform: scale(1.1);
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2.2rem;
      }

      .product {
        width: 90%;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Softline Unstiched fabrics</h1>
    <p>Premium Unstitched Fabrics for Every Occasion</p>
  </header>

  <section class="about">
    <h2>About Us</h2>
    <p>Discover elegance in every thread. We offer exclusive unstitched suits that blend tradition with style, perfect for festivals, weddings, and everyday fashion.</p>
  </section>

  <section class="gallery">
    <div class="product">
      <img src="cotton.jpg" alt="Cotton Suit">
      <h3>Elegant Cotton Suit</h3>
      <p>Rs1,299</p>
      <a class="buy-btn" href="https://wa.me/91YOURNUMBER?text=Hi, I'm interested in the Elegant Cotton Suit" target="_blank">Buy Now</a>
    </div>
    <div class="product">
      <img src="wash&wear.jpg" alt="Silk Suit">
      <h3>Festive Silk Set</h3>
      <p>Rs1,999</p>
      <a class="buy-btn" href="https://wa.me/91YOURNUMBER?text=Hi, I'm interested in the Festive Silk Set" target="_blank">Buy Now</a>
    </div>
    <div class="product">
      <img src="lenon.jpg" alt="Linen Suit">
      <h3>Printed Linen Fabric</h3>
      <p>Rs1,499</p>
      <a class="buy-btn" href="https://wa.me/91YOURNUMBER?text=Hi, I'm interested in the Printed Linen Fabric" target="_blank">Buy Now</a>
    </div>
  </section>

  <footer>
    <p>📞 +92-3319188629 | ✉️ softlineunstiched@gmail.com</p>
    <p>📸 Follow us on Instagram: <strong>@Softline.Unstichedfabrics</strong></p>
  </footer>

  <!-- WhatsApp Floating Button -->
  <a href="https://wa.me/=923319188629text=Hi, I'm interested in your unstitched fabrics!" class="whatsapp-float" target="_blank" title="Chat on WhatsApp">💬</a>
</body>
</html>
