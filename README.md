
<html lang="ru">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Полезный портал</title>

    <style>
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: Arial, sans-serif;
      }

      body {
        background: linear-gradient(135deg, #0f172a, #1e293b);
        color: white;
        min-height: 100vh;
      }

      header {
        padding: 30px;
        text-align: center;
        background: rgba(5, 144, 95, 0.05);
        backdrop-filter: blur(10px);
        box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
      }

      header h1 {
        font-size: 42px;
        margin-bottom: 10px;
      }

      header p {
        color: #cbd5e1;
      }

      .container {
        width: 90%;
        max-width: 1200px;
        margin: 40px auto;
      }

      .grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 25px;
      }

      .card {
        background: rgba(255, 255, 255, 0.08);
        border-radius: 20px;
        padding: 25px;
        transition: 0.3s;
        box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
      }

      .card:hover {
        transform: translateY(-8px);
        background: rgba(255, 255, 255, 0.12);
      }

      .card h2 {
        margin-bottom: 15px;
        color: #38bdf8;
      }

      .card p {
        color: #d1d5db;
        margin-bottom: 20px;
        line-height: 1.5;
      }

      .btn {
        display: inline-block;
        padding: 12px 20px;
        border-radius: 12px;
        text-decoration: none;
        color: rgb(0, 0, 0);
        background: #2563eb;
        transition: 0.3s;
        font-weight: bold;
      }

      .btn:hover {
        background: #1d4ed8;
        transform: scale(1.05);
      }

      footer {
        text-align: center;
        padding: 25px;
        color: #9d9696b1;
        margin-top: 40px;
      }
    </style>
  </head>

  <body>
    <header>
      <h1>🐷 Полезные сайты для каждого дня</h1>
      <p>Быстрый доступ к популярным сайтам и сервисам</p>
    </header>

    <div class="container">
      <div class="grid">
        <div class="card">
          <h2>🎥 YouTube</h2>
          <p>Смотри видео, музыку, стримы и обучение.</p>
          <a class="btn" href="https://youtube.com" target="_blank">
            Открыть
          </a>
        </div>

        <div class="card">
          <h2>💬 Telegram</h2>
          <p>Общение, каналы и полезные боты.</p>
          <a class="btn" href="https://telegram.org" target="_blank">
            Перейти
          </a>
        </div>

        <div class="card">
          <h2>📚 Википедии</h2>
          <p>Огромная энциклопедия знаний.</p>
          <a
            class="btn"
            href="https://ru.wikipedia.org/?ysclid=mpp5bcqpkf698344273"
            target="_blank"
          >
            Читать
          </a>
        </div>

        <div class="card">
          <h2>🤖 ChatGPT</h2>
          <p>ИИ помощник для учебы, работы и идей.</p>
          <a class="btn" href="https://chatgpt.com" target="_blank">
            Открыть
          </a>
        </div>

        <div class="card">
          <h2>🙅‍♂️ Обход блокировок</h2>
          <p>YouTube,Discord,ChatGPT</p>
          <a
            class="btn"
            href="https://github.com/Flowseal/zapret-discord-youtube/releases?ysclid=mpp5o4jfmk154787496"
            target="_blank"
          >
            Скачать
          </a>
        </div>

        <div class="card">
          <h2>📰 Новости</h2>
          <p>Последние события со всего мира.</p>
          <a
            class="btn"
            href="https://ria.ru/?ysclid=mpp59lqya8219501507"
            target="_blank"
          >
            Смотреть
          </a>
        </div>
      </div>
    </div>

    <footer>
      © 2026 Полезные порталыыы | Сделано при поддержки команды села-дала под
      руководством Сергея и Виталика
    </footer>
  </body>
</html>
