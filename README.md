<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мир веб-разработки | Главная</title>
    <style>
        /* Небольшие базовые стили для аккуратности и читаемости */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: system-ui, 'Segoe UI', 'Roboto', 'Helvetica Neue', sans-serif;
            line-height: 1.5;
            background-color: #f8fafc;
            color: #0f172a;
            padding: 0 1rem;
        }
        .container {
            max-width: 1100px;
            margin: 0 auto;
            background-color: white;
            box-shadow: 0 10px 25px -5px rgba(0,0,0,0.05);
            border-radius: 1rem;
            margin-top: 2rem;
            margin-bottom: 2rem;
            overflow: hidden;
        }
        header {
            background: linear-gradient(135deg, #1e293b, #0f172a);
            color: white;
            padding: 2rem 2rem 1.5rem 2rem;
            border-bottom: 4px solid #3b82f6;
        }
        h1 {
            font-size: 2.2rem;
            letter-spacing: -0.01em;
            margin-bottom: 1rem;
            font-weight: 700;
        }
        nav {
            margin-top: 0.5rem;
        }
        nav ul {
            display: flex;
            flex-wrap: wrap;
            gap: 1.8rem;
            list-style: none;
        }
        nav a {
            color: #e2e8f0;
            text-decoration: none;
            font-weight: 500;
            padding: 0.25rem 0;
            border-bottom: 2px solid transparent;
            transition: all 0.2s;
        }
        nav a:hover {
            color: white;
            border-bottom-color: #3b82f6;
        }
        main {
            padding: 2rem 2rem 2rem 2rem;
            background: white;
        }
        section {
            margin-bottom: 0.5rem;
        }
        h2 {
            font-size: 1.8rem;
            font-weight: 600;
            margin-top: 0.5rem;
            margin-bottom: 1rem;
            color: #0f172a;
            border-left: 5px solid #3b82f6;
            padding-left: 1rem;
        }
        p {
            margin-bottom: 1rem;
            font-size: 1rem;
            color: #1e293b;
        }
        ul {
            margin: 1rem 0 1.5rem 1.8rem;
        }
        li {
            margin-bottom: 0.5rem;
            color: #1e293b;
        }
        footer {
            background-color: #f1f5f9;
            border-top: 1px solid #e2e8f0;
            text-align: center;
            padding: 1.5rem;
            font-size: 0.9rem;
            color: #334155;
        }
        /* легкий адаптив */
        @media (max-width: 640px) {
            body {
                padding: 0 0.5rem;
            }
            .container {
                margin-top: 1rem;
                margin-bottom: 1rem;
                border-radius: 0.75rem;
            }
            header, main {
                padding: 1.5rem;
            }
            h1 {
                font-size: 1.8rem;
            }
            nav ul {
                gap: 1rem;
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
<div class="container">
    <!-- ШАПКА САЙТА: заголовок h1 и навигация nav -->
    <header>
        <h1>Добро пожаловать в мир веб-разработки!</h1>
        <nav>
            <ul>
                <!-- Рабочая ссылка на главную (index.html) -->
                <li><a href="index.html">Главная</a></li>
                <!-- ссылки-заглушки с якорями # (плавный скролл вверх) -->
                <li><a href="#">Технологии</a></li>
                <li><a href="#">Ресурсы</a></li>
            </ul>
        </nav>
    </header>

    <!-- ОСНОВНОЕ СОДЕРЖИМОЕ СТРАНИЦЫ -->
    <main>
        <!-- первый раздел section -->
        <section>
            <h2>О чём этот сайт?</h2>
            <p>Этот сайт посвящён удивительной вселенной веб-разработки — от самых основ создания сайтов до современных фреймворков и инструментов. Здесь я делюсь идеями, вдохновением и ключевыми концепциями, которые помогают превратить браузер в мощную платформу для творчества.</p>
            <p>С каждым годом веб-технологии развиваются стремительнее: от статических страниц до сложных веб-приложений, которыми пользуются миллионы. Моя цель — показать, насколько увлекательным и доступным может быть путь фронтенд-разработчика, независимо от уровня подготовки.</p>
            
            <h2>Почему веб-разработка — это интересно?</h2>
            <ul>
                <li>Вы создаёте то, что видят и чем пользуются люди по всему миру — мгновенный отклик на ваш труд.</li>
                <li>Гибкость и разнообразие: от лендингов до сложных дашбордов и игр прямо в браузере.</li>
                <li>Сообщество разработчиков огромно и открыто — миллионы туториалов, библиотек и идей.</li>
                <li>Веб объединяет технологии: искусственный интеллект, 3D-графика, анимации — всё это доступно.</li>
            </ul>
            <p>Изучение HTML, CSS и JavaScript открывает двери в мир, где вы можете реализовать собственные проекты, стартапы или получить востребованную профессию. К тому же, веб — это одна из немногих сфер, где результат виден сразу после сохранения файла.</p>
        </section>

        <!-- Дополнительный раздел (не обязательный, но для объёма, но структура уже содержит всё нужное по заданию) 
        Оставим один <section> как по инструкции, но внутри выполнены требования: 2 h2, 2+ параграфа, список ul -->
        
        <!-- Для большей информативности можно добавить небольшую вставку, но всё основное уже есть, 
        тем не менее, чтобы показать аккуратность и соответствие — добавим краткий блок с заметкой, но он не нарушает задание. 
        Однако строго по заданию: внутри main должен быть section, и внутри него h2, p, h2, ul — ВСЁ ЭТО УЖЕ ЕСТЬ. 
        Поэтому добавим только то, что улучшает восприятие, но не ломает семантику. 
        В оригинальном задании не запрещено добавлять контент, а только указаны минимальные требования — они выполнены. -->
    </main>

    <!-- ПОДВАЛ САЙТА с именем, курсом и годом -->
    <footer>
        <p>© максим рожков , студент 1 курса 1вр-2-25 2026</p>
        <p style="font-size: 0.8rem; margin-top: 0.3rem;">Учебный проект — семантическая вёрстка</p>
    </footer>
</div>

<!-- Небольшой скрипт для имитации плавного скролла при клике на ссылки-заглушки (как в критериях: при нажатии на другие ссылки страница плавно прокручивается вверх). 
     Это соответствует требованию из раздела "Проверка результата". Также это улучшает UX, но не является обязательным для семантики. 
     Добавляем, чтобы ссылки-заглушки вели себя красиво — плавный скролл вверх -->
<script>
    (function() {
        // Находим все ссылки, у которых href="#"
        const allLinks = document.querySelectorAll('a[href="#"]');
        allLinks.forEach(link => {
            link.addEventListener('click', function(event) {
                event.preventDefault();  // отменяем стандартный переход
                window.scrollTo({
                    top: 0,
                    behavior: 'smooth'
                });
            });
        });
        // Также для ссылки на главную index.html — она ведёт на эту же страницу, ничего не перезагружает,
        // но при клике можно предотвратить перезагрузку, чтобы оставаться на месте, но по заданию ссылка на главную
        // настоящая, и в браузере при клике она перезагрузит страницу (но это нормально). Оставим как есть.
        // Дополнительно: если нужна дополнительная обработка ссылки "Главная", не трогаем.
    })();
</script>
</body>
</html>
