<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MyWebsite</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #fff;
      color: #111;
    }

    /* Navigation */
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 80px;
      background-color: #fff;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
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
      transition: color 0.3s;
    }
    nav a:hover {
      color: gray;
    }

    /* Full-width header */
    header {
      background: #f5f5f7;
      padding: 80px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 42px;
      margin: 0 0 15px 0;
      font-weight: 600;
    }
    header p {
      font-size: 18px;
      margin: 0;
      color: #555;
    }

    /* Main content sections */
    .container {
      max-width: 1200px;
      margin: auto;
      padding: 60px 20px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
    }
    .card {
      background: #f5f5f7;
      padding: 40px;
      border-radius: 12px;
      text-align: center;
      transition: transform 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card h2 {
      margin-bottom: 15px;
      font-size: 24px;
    }
    .card p {
      color: #666;
      font-size: 16px;
    }

    footer {
      text-align: center;
      padding: 30px;
      font-size: 14px;
      color: #777;
      background: #f5f5f7;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <nav>
    <div class="logo">
      <img src="https://upload.wikimedia.org/wikipedia/commons/f/fa/Apple_logo_black.svg" alt="Apple Logo">
      MyWebsite
    </div>
    <div>
      <a href="index.html">Home</a>
      <a href="college.html">College</a>
      <a href="semesters.html">Results</a>
    </div>
  </nav>

  <header>
    <h1>Welcome to MyWebsite</h1>
    <p>Inspired by Apple’s minimal and clean design</p>
  </header>

  <main class="container">
    <div class="grid">
      <div class="card">
        <h2>Feature One</h2>
        <p>A clean and simple design to highlight important content.</p>
      </div>
      <div class="card">
        <h2>Feature Two</h2>
        <p>Responsive layout that looks great on any device.</p>
      </div>
      <div class="card">
        <h2>Feature Three</h2>
        <p>Minimalist style with wide spacing like Apple’s website.</p>
      </div>
    </div>
  </main>

  <footer>
    © 2025 MyWebsite. All rights reserved.
  </footer>

</body>
</html>
