<ДОБРО ПОЖАЛОВАТЬ>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <title>AI Мультфильмы по тексту</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <h1>🎬 AI Мультфильмы по тексту</h1>
    <p>Вставьте свой текст, и мы бесплатно создадим мультфильм с помощью искусственного интеллекта!</p>

    <textarea id="userText" placeholder="Введите ваш текст..." rows="6"></textarea>
    <button onclick="createCartoon()">Создать мультфильм</button>

    <div id="result">
      <!-- Здесь будет результат -->
    </div>

    <p><a href="https://www.donationalerts.com/" target="_blank">💖 Поддержать проект</a></p>
  </div>

  <script>
    function createCartoon() {
      const text = document.getElementById("userText").value;
      if (!text.trim()) {
        alert("Пожалуйста, введите текст.");
        return;
      }

      // Пока что просто имитируем генерацию
      document.getElementById("result").innerHTML = `
        <p>⏳ Генерация мультфильма по вашему тексту...</p>
        <p>В будущем здесь появится видео, созданное ИИ.</p>
      `;
    }
  </script>
</body>
</html>
