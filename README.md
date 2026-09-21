<!doctype html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta
    name="viewport"
    content="width=device-width, initial-scale=1.0"
  >
  <title>Фотографии ремонта</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      min-height: 100vh;
      padding: 24px;
      font-family: Arial, sans-serif;
      color: #1f2937;
      background: #f3f4f6;
    }

    .container {
      width: 100%;
      max-width: 700px;
      margin: 40px auto;
      padding: 32px;
      background: white;
      border-radius: 18px;
      box-shadow: 0 10px 35px rgba(0, 0, 0, 0.08);
    }

    h1 {
      margin-top: 0;
      color: #111827;
    }

    p {
      line-height: 1.6;
    }

    .status {
      margin-top: 24px;
      padding: 16px;
      color: #166534;
      background: #dcfce7;
      border: 1px solid #86efac;
      border-radius: 10px;
    }

    button {
      margin-top: 20px;
      padding: 13px 20px;
      border: 0;
      border-radius: 10px;
      color: white;
      background: #2563eb;
      font-size: 16px;
      cursor: pointer;
    }

    button:hover {
      background: #1d4ed8;
    }
  </style>
</head>

<body>
  <main class="container">
    <h1>Фотографии ремонта</h1>

    <p>
      Здесь будет приложение для загрузки и хранения
      фотографий выполненных ремонтных работ.
    </p>

    <p>
      В дальнейшем на этой странице появятся номер гаража,
      выбор фотографий, комментарий и история ремонтов.
    </p>

    <button id="checkButton" type="button">
      Проверить работу сайта
    </button>

    <div class="status" id="status">
      Страница успешно загружена.
    </div>
  </main>

  <script>
    const button = document.getElementById("checkButton");
    const status = document.getElementById("status");

    button.addEventListener("click", function () {
      status.textContent =
        "JavaScript работает. Сайт готов к дальнейшей настройке.";
    });
  </script>
</body>
</html>
