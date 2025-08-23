<!DOCTYPE html>
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
    /* Navbar */
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
    /* Hero section */
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
    /* Content cards */
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }
    .card {
      background: #f4f4f4;
      margin: 10px;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
      width: 280px;
      text-align: center;
    }
    .card h3 {
      margin-top: 0;
    }
    /* Semester section */
    .semester-section {
      padding: 20px;
      text-align: center;
    }
    .semester-links {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin-top: 20px;
    }
    .semester-links a {
      display: inline-block;
      background: #4facfe;
      color: white;
      padding: 12px 20px;
      margin: 8px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.3s ease;
    }
    .semester-links a:hover {
      background: #00c6ff;
    }
    /* Footer */
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
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </div>
  </nav>

  <!-- Hero section -->
  <section class="hero">
    <h1>Welcome to My First Website</h1>
    <p>This page is hosted on GitHub Pages 🚀</p>
  </section>

  <!-- Content cards -->
  <div class="container">
    <div class="card">
      <h3>About Me</h3>
      <p>This is where you can write something about yourself.</p>
    </div>
    <div class="card">
      <h3>Projects</h3>
      <p>Showcase your work, hobbies, or anything you are proud of.</p>
    </div>
    <div class="card">
      <h3>Contact</h3>
      <p>You can add your email or links to social media here.</p>
    </div>
  </div>

  <!-- Semester Section -->
  <section class="semester-section">
    <h2>Semester Notes</h2>
    <p>Click below to access your semester resources:</p>
    <div class="semester-links">
      <a href="LINK1" target="_blank">1st Semester</a>
      <a href="LINK2" target="_blank">2nd Semester</a>
      <a href="LINK3" target="_blank">3rd Semester</a>
      <a href="LINK4" target="_blank">4th Semester</a>
      <a href="LINK5" target="_blank">5th Semester</a>
      <a href="LINK6" target="_blank">6th Semester</a>
      <a href="LINK7" target="_blank">7th Semester</a>
      <a href="LINK8" target="_blank">8th Semester</a>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 My Website | Built with ❤️ using HTML & CSS</p>
  </footer>
</body>
</html>
