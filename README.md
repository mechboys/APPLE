
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Website</title>
  <style>
    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      background: #fff;
      color: #111;
    }

    /* Navbar */
    nav {
      background: #fff;
      padding: 15px 50px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #ddd;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      text-decoration: none;
      color: #111;
      margin-left: 25px;
      font-size: 14px;
      transition: opacity 0.3s;
    }
    nav a:hover {
      opacity: 0.6;
    }

    /* Hero Section */
    .hero {
      text-align: center;
      padding: 100px 20px;
    }
    .hero h1 {
      font-size: 3rem;
      margin-bottom: 15px;
      font-weight: 600;
    }
    .hero p {
      font-size: 1.2rem;
      color: #555;
      margin-bottom: 30px;
    }
    .hero a {
      display: inline-block;
      background: #0071e3;
      color: white;
      padding: 12px 24px;
      border-radius: 25px;
      font-size: 16px;
      text-decoration: none;
      transition: background 0.3s;
    }
    .hero a:hover {
      background: #005bb5;
    }

    /* Feature Section */
    .feature {
      display: grid;
      grid-template-columns: 1fr 1fr;
      align-items: center;
      padding: 80px 10%;
      gap: 40px;
    }
    .feature img {
      width: 100%;
      border-radius: 20px;
    }
    .feature h2 {
      font-size: 2rem;
      margin-bottom: 20px;
    }
    .feature p {
      font-size: 1.1rem;
      color: #444;
    }

    /* Footer */
    footer {
      background: #f5f5f7;
      padding: 20px;
      text-align: center;
      font-size: 14px;
      color: #666;
    }

    @media (max-width: 768px) {
      .feature {
        grid-template-columns: 1fr;
        text-align: center;
      }
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav>
    <div><strong>MyWebsite</strong></div>
    <div>
      <a href="index.html">Home</a>
      <a href="semesters.html">Semesters</a>
      <a href="#">Contact</a>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <h1>Welcome to My Website</h1>
    <p>Simple. Clean. Inspired by Apple.</p>
    <a href="semesters.html">Explore Semesters</a>
  </section>

  <!-- Feature Section -->
  <section class="feature">
    <div>
      <h2>Modern Design</h2>
      <p>
        This website is built with a minimal and elegant style, 
        focusing on clarity and simplicity — just like Apple’s design philosophy.
      </p>
    </div>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fa/Apple_logo_black.svg" alt="Apple Style">
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 MyWebsite | Designed in Apple Style</p>
  </footer>

</body>
</html>
