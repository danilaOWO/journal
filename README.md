# journal
This is my first project/

<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой проект на GitHub</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #0d1117, #161b22);
            color: #c9d1d9;
            line-height: 1.6;
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        .header {
            text-align: center;
            margin-bottom: 60px;
        }

        .header h1 {
            font-size: 3rem;
            background: linear-gradient(45deg, #58a6ff, #bc8cff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 10px;
        }

        .header p {
            font-size: 1.2rem;
            color: #8b949e;
        }

        .content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
            align-items: center;
        }

        .gif-container {
            background: #161b22;
            border-radius: 15px;
            padding: 20px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
            border: 1px solid #30363d;
        }

        .gif-container img {
            width: 100%;
            border-radius: 10px;
            display: block;
        }

        .description {
            background: #161b22;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
            border: 1px solid #30363d;
        }

        .description h2 {
            color: #58a6ff;
            margin-bottom: 20px;
            font-size: 2rem;
        }

        .description p {
            margin-bottom: 20px;
            font-size: 1.1rem;
        }

        .features {
            margin: 30px 0;
        }

        .features h3 {
            color: #bc8cff;
            margin-bottom: 15px;
        }

        .features ul {
            list-style: none;
            padding-left: 0;
        }

        .features li {
            padding: 8px 0;
            padding-left: 25px;
            position: relative;
        }

        .features li:before {
            content: "✓";
            color: #3fb950;
            position: absolute;
            left: 0;
            font-weight: bold;
        }

        .buttons {
            display: flex;
            gap: 15px;
            margin-top: 30px;
        }

        .btn {
            padding: 12px 30px;
            border: none;
            border-radius: 8px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            text-decoration: none;
            transition: all 0.3s ease;
            display: inline-block;
        }

        .btn-primary {
            background: #238636;
            color: white;
        }

        .btn-primary:hover {
            background: #2ea043;
            transform: translateY(-2px);
        }

        .btn-secondary {
            background: #21262d;
            color: #c9d1d9;
            border: 1px solid #30363d;
        }

        .btn-secondary:hover {
            background: #30363d;
            transform: translateY(-2px);
        }

        .tech-stack {
            margin-top: 30px;
        }

        .tech-stack h3 {
            color: #bc8cff;
            margin-bottom: 15px;
        }

        .tech-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .tech-tag {
            background: #13233a;
            color: #58a6ff;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.9rem;
            border: 1px solid #30363d;
        }

        @media (max-width: 768px) {
            .content {
                grid-template-columns: 1fr;
            }
            
            .header h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Awesome Project</h1>
            <p>Инновационное решение для разработчиков</p>
        </div>

        <div class="content">
            <div class="gif-container">
                <!-- Замените src на ссылку на вашу GIF -->
                <img src="https://media.giphy.com/media/coxQHKASG60HrHtvkt/giphy.gif" alt="Демонстрация проекта">
            </div>

            <div class="description">
                <h2>О проекте</h2>
                <p>Это современный инструмент для разработчиков, который упрощает процесс создания приложений и ускоряет рабочий процесс.</p>
                
                <div class="features">
                    <h3>Основные возможности</h3>
                    <ul>
                        <li>Быстрая и простая настройка</li>
                        <li>Поддержка современных технологий</li>
                        <li>Гибкая конфигурация</li>
                        <li>Отличная документация</li>
                        <li>Активное сообщество</li>
                    </ul>
                </div>

                <div class="tech-stack">
                    <h3>Технологии</h3>
                    <div class="tech-tags">
                        <span class="tech-tag">JavaScript</span>
                        <span class="tech-tag">React</span>
                        <span class="tech-tag">Node.js</span>
                        <span class="tech-tag">Python</span>
                        <span class="tech-tag">Docker</span>
                    </div>
                </div>

                <div class="buttons">
                    <a href="https://github.com/yourusername/yourproject" class="btn btn-primary">
                        📁 Посмотреть код
                    </a>
                    <a href="https://github.com/yourusername/yourproject/issues" class="btn btn-secondary">
                        🐛 Сообщить о проблеме
                    </a>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
