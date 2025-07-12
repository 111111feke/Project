<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Выбор платформы</title>
  <style>
    @font-face {
      font-family: 'Tavrida';
      src: url('Tavrida.ttf') format('truetype'); /* подключи свой файл шрифта */
    }

    body {
      margin: 0;
      padding: 0;
      background-color: #000;
      color: #fff;
      font-family: 'Tavrida', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
    }

    .slider {
      display: flex;
      gap: 2rem;
      overflow-x: auto;
      scroll-snap-type: x mandatory;
      padding: 2rem;
      width: 100%;
      max-width: 1000px;
    }

    .card {
      flex: 0 0 300px;
      background-color: #111;
      border: 1px solid #fff;
      border-radius: 20px;
      padding: 2rem;
      text-align: center;
      scroll-snap-align: center;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: scale(1.05);
      cursor: pointer;
    }

    .card a {
      text-decoration: none;
      color: white;
      font-size: 1.5rem;
      display: block;
      height: 100%;
    }
  </style>
</head>
<body>
  <div class="slider">
    <div class="card">
      <a href="https://myrosmol.ru/" target="_blank">ФГАИС «Молодёжь России»</a>
    </div>
    <div class="card">
      <a href="https://tavrida.art/" target="_blank">Таврида.Арт</a>
    </div>
    <div class="card">
      <a href="https://tvoyhod.online/" target="_blank">Твой Ход</a>
    </div>
  </div>
</body>
</html>
