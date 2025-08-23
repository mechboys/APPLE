
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MyWebsite</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 50px;
      background-color: #fff;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    nav .logo {
      display: flex;
      align-items: center;
      gap: 8px; /* space between logo & text */
      font-weight: bold;
      font-size: 20px;
    }
    nav img {
      height: 18px; /* smaller apple logo */
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
    header {
      background: #f5f5f7;
      padding: 40px 50px;
    }
    header h1 {
      font-size: 36px;
      margin: 0 0 10px 0;
    }
    header p {
      font-size: 18px;
      margin: 0;
      color: #555;
    }
  </style>
</head>
<body>

  <nav>
    <!-- Logo + Website Name -->
    <div class="logo">
      <img src="https://upload.wikimedia.org/wikipedia/commons/f/fa/Apple_logo_black.svg" alt="Apple Logo">
      MyWebsite
    </div>

    <!-- Navigation Links -->
    <div>
      <a href="index.html">Home</a>
      <a href="semesters.html">Semesters</a>
      <a href="#">Contact</a>
    </div>
  </nav>

  <header>
    <h1>Welcome to MyWebsite</h1>
    <p>Designed like Apple’s minimal style</p>
  </header>

</body>
</html>
