
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My First Website</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }
    nav {
      background: #333;
      color: #fff;
      padding: 10px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 10px;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      background: linear-gradient(to right, #4facfe, #00f2fe);
      color: white;
      padding: 50px 20px;
      text-align: center;
    }
    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <nav>
    <div><strong>My Website</strong></div>
    <div>
      <a href="index.html">Home</a>
      <a href="semesters.html">Semesters</a>
      <a href="#">Contact</a>
    </div>
  </nav>

  <!-- Hero section -->
  <section class="hero">
    <h1>Welcome to My First Website</h1>
    <p>Select your semester from the top menu 🚀</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 My Website | Built with ❤️ using HTML & CSS</p>
  </footer>
</body>
</html>
