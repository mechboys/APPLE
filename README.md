<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MyWebsite</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      color: #1d1d1f;
      background: #fff;
    }

    /* Navigation Bar */
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 50px;
      background-color: #fff;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav .logo {
      display: flex;
      align-items: center;
      gap: 8px;
      font-weight: bold;
      font-size: 20px;
    }
    nav img {
      height: 18px;
      width: auto;
    }
    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: black;
      font-size: 16px;
    }
    nav a:hover {
      color: gray;
    }

    /* Hero Section */
    header {
      text-align: center;
      padding: 80px 20px;
      background: #f5f5f7;
    }
    header h1 {
      font-size: 48px;
      margin: 0;
    }
    header p {
      font-size: 20px;
      margin-top: 10px;
      color: #555;
    }

    /* Product Sections */
    .section {
      padding: 60px 20px;
      text-align: center;
      border-bottom: 1px solid #e5e5e5;
    }
    .section h2 {
      font-size: 40px;
      margin-bottom: 15px;
    }
    .section p {
      font-size: 18px;
      color: #666;
      margin-bottom: 20px;
    }
    .section img {
      max-width: 80%;
      height: auto;
      border-radius: 12px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }
    .link {
      display: inline-block;
      margin-top: 15px;
      text-decoration: none;
      font-size: 18px;
      color: #0071e3;
    }
    .link:hover {
      text-decoration: underline;
    }

    /* Footer */
    footer {
      padding: 30px;
      text-align: center;
      background: #f5f5f7;
      color: #555;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav>
    <div class="logo">
      <img src="https://upload.wikimedia.org/wikipedia/commons/f/fa/Apple_logo_black.svg" alt="Apple Logo">
      MyWebsite
    </div>
    <div>
      <a href="index.html">Home</a>
      <a href="semesters.html">Semesters</a>
      <a href="#">Contact</a>
    </div>
  </nav>

  <!-- Hero Section -->
  <header>
    <h1>Welcome to MyWebsite</h1>
    <p>Inspired by Apple’s minimal design</p>
  </header>

  <!-- Product Sections -->
  <div class="section">
    <h2>Latest Product</h2>
    <p>Experience innovation like never before.</p>
    <img src="https://www.apple.com/newsroom/images/product/iphone/standard/Apple_iPhone-14-Pro_hero_220907_inline.jpg.large.jpg" alt="Product">
    <br>
    <a href="#" class="link">Learn more &gt;</a>
  </div>

  <div class="section">
    <h2>Powerful Performance</h2>
    <p>Engineered for speed, designed for you.</p>
    <img src="https://www.apple.com/v/macbook-air-m2/a/images/overview/hero_endframe__ea0qze85eyi6_large.jpg" alt="MacBook">
    <br>
    <a href="#" class="link">Explore &gt;</a>
  </div>

  <div class="section">
    <h2>Stay Connected</h2>
    <p>Smart technology that keeps you closer to what matters.</p>
    <img src="https://www.apple.com/v/watch/home/ah/images/overview/hero_watch__f05go333pz2u_large.jpg" alt="Watch">
    <br>
    <a href="#" class="link">Shop now &gt;</a>
  </div>

  <!-- Footer -->
  <footer>
    © 2025 MyWebsite | Inspired by Apple
  </footer>

</body>
</html>
