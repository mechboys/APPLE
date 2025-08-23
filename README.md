<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      text-align: center;
      background-color: #f4f4f4;
    }
    header {
      background: #333;
      color: #fff;
      padding: 20px;
    }
    header h1 {
      margin: 0;
    }
    section {
      padding: 20px;
    }
    button {
      padding: 10px 20px;
      font-size: 16px;
      background: #007BFF;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background: #0056b3;
    }
    footer {
      background: #333;
      color: #fff;
      padding: 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Website</h1>
  </header>

  <section>
    <p>This is my first website hosted on GitHub Pages 🚀</p>
    <button onclick="sayHello()">Click Me</button>
  </section>

  <footer>
    <p>© 2025 My Website</p>
  </footer>

  <script>
    function sayHello() {
      alert("Hello! Thanks for visiting my site 😊");
    }
  </script>
</body>
</html>
