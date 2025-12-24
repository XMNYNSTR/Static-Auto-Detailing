<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Static Auto Detailing</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background: #111;
      color: white;
      padding: 25px;
      text-align: center;
    }
    section {
      padding: 20px;
      max-width: 800px;
      margin: auto;
    }
    h2 {
      border-bottom: 2px solid #ddd;
      padding-bottom: 5px;
    }
    .contact a {
      color: #007bff;
      text-decoration: none;
      font-weight: bold;
    }
    .price {
      font-size: 18px;
      font-weight: bold;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 10px;
      margin-top: 15px;
    }
    .placeholder {
      background: #ddd;
      height: 120px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 14px;
      color: #666;
    }
    footer {
      text-align: center;
      padding: 15px;
      background: #111;
      color: white;
      margin-top: 30px;
    }
  </style>
</head>
<body>

<header>
  <h1>Static Auto Detailing</h1>
  <p>Professional Interior & Exterior Detailing</p>
</header>

<section>
  <h2>About</h2>
  <p><strong>Owner:</strong> Nestor Perez</p>
</section>

<section>
  <h2>Pricing</h2>
  <p class="price">$285 – $300</p>
  <p>Full Interior & Exterior Detail</p>
</section>

<section>
  <h2>Results Gallery</h2>
  <p>Photos coming soon</p>
  <div class="gallery">
    <div class="placeholder">Photo 1</div>
    <div class="placeholder">Photo 2</div>
    <div class="placeholder">Photo 3</div>
  </div>
</section>

<section class="contact">
  <h2>Contact</h2>
  <p>📞 <a href="tel:14793471161">479-347-1161</a></p>
  <p>✉️ <a href="mailto:Ybnestor@gmail.com">Ybnestor@gmail.com</a></p>
</section>

<footer>
  <p>© 2025 Static Auto Detailing</p>
</footer>

</body>
</html>
