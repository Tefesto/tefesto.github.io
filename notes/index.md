<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <title>Мій сайт</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
    }
    nav {
      text-align: center;
      margin-bottom: 20px;
    }
    nav a {
      color: #333;
      text-decoration: none;
      margin: 0 10px;
      font-weight: bold;
    }
    nav a::before {
      content: "[";
    }
    nav a::after {
      content: "]";
    }
    nav a:hover {
      color: darkred;
    }
  </style>
</head>
<body>
  <nav>
    <a href="index.html">Головна</a>
    <a href="about.html">Про мене</a>
    <a href="projects.html">Проєкти</a>
    <a href="contacts.html">Контакти</a>
  </nav>

  <h1>Вітаю на моєму сайті!</h1>
  <p>Це приклад з однорядковим меню.</p>
</body>
</html>
