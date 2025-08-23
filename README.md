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
      font-weight: bold;
      font-size: 20px;
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
  </style>
</head>
<body>

  <nav>
    <!-- Website Name -->
    <div class="logo">MyWebsite</div>

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
