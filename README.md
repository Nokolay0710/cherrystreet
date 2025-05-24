<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RoboTech - Сайт в разработке</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f0f4f8;
            line-height: 1.6;
            color: #2d3748;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 2rem;
        }

        header {
            text-align: center;
            padding: 3rem 0;
            background-color: #2b6cb0;
            color: white;
            margin-bottom: 2rem;
            border-radius: 0 0 15px 15px;
        }

        .robot-icon {
            font-size: 4rem;
            margin-bottom: 1rem;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .content-section {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 2px 15px rgba(0,0,0,0.1);
            margin-bottom: 2rem;
        }

        .highlight {
            color: #2b6cb0;
            font-weight: bold;
        }

        footer {
            text-align: center;
            padding: 2rem;
            color: #718096;
            margin-top: 3rem;
        }

        @media (max-width: 600px) {
            .container {
                padding: 1rem;
            }
            
            h1 {
                font-size: 2rem;
            }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <i class="fas fa-robot robot-icon"></i>
            <h1>RoboTech</h1>
            <p>Искусственный интеллект нового поколения</p>
        </div>
    </header>

    <div class="container">
        <div class="content-section">
            <h2>🚀 Наш сайт скоро заработает!</h2>
            <p>Мы работаем над созданием уникальной платформы для управления умными роботами следующего поколения.</p>
            <p class="highlight">Ожидайте революционных изменений в сфере человеко-машинного взаимодействия!</p>
        </div>

        <div class="content-section">
            <h3>🤖 Наши технологии</h3>
            <p>Разрабатываем автономных роботов с:</p>
            <ul>
                <li>Нейросетевым управлением</li>
                <li>Компьютерным зрением</li>
                <li>Системой тактильного отклика</li>
                <li>Адаптивными алгоритмами обучения</li>
            </ul>
        </div>

        <div class="content-section">
            <h3>🌍 Применение роботов</h3>
            <p>Наши разработки будут использоваться в:</p>
            <div style="columns: 2; margin: 1rem 0;">
                <p>• Медицинской диагностике<br>
                • Промышленном производстве<br>
                • Космических исследованиях<br>
                • Образовательных целях</p>
            </div>
        </div>
    </div>

    <footer>
        <div class="container">
            <p>© 2024 RoboTech. Все права защищены</p>
            <p>Контакты: info@robotech.ai | +7 (495) 123-45-67</p>
            <p style="margin-top: 1rem;">Сайт находится в стадии активной разработки</p>
        </div>
    </footer>
</body>
</html>
