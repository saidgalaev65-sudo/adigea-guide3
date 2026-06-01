<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>Путеводитель по Адыгее | Горные приключения</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
            background-color: #faf8f5;
            color: #1e2a2e;
            line-height: 1.5;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        header {
            background: linear-gradient(135deg, #1b4d2e, #2c5e3a);
            color: white;
            padding: 2rem 0;
            text-align: center;
        }
        h1 {
            font-size: 2.8rem;
            letter-spacing: 1px;
            margin-bottom: 0.5rem;
        }
        .subhead {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        nav {
            background: #2c3e2b;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        .nav-links {
            display: flex;
            justify-content: center;
            gap: 2rem;
            padding: 0.8rem 0;
            flex-wrap: wrap;
        }
        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: 0.3s;
        }
        .nav-links a:hover {
            color: #ffdd99;
            transform: translateY(-2px);
        }
        .hero {
            background: url('https://images.pexels.com/photos/1474110/mountains-fog-clouds-forest-1474110.jpg?auto=compress&cs=tinysrgb&w=1600') center/cover no-repeat;
            height: 60vh;
            min-height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
        }
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.4);
        }
        .hero-text {
            position: relative;
            color: white;
            text-align: center;
            padding: 1rem;
        }
        .hero-text h2 {
            font-size: 2.5rem;
            text-shadow: 2px 2px 8px rgba(0,0,0,0.5);
        }
        .section-title {
            font-size: 2rem;
            margin: 2rem 0 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 3px solid #4c8b5e;
            display: inline-block;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.8rem;
            margin: 2rem 0;
        }
        .card {
            background: white;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 8px 20px rgba(0,0,0,0.1);
            transition: transform 0.2s;
        }
        .card:hover {
            transform: translateY(-6px);
        }
        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .card-content {
            padding: 1.2rem;
        }
        .card-content h3 {
            margin-bottom: 0.5rem;
            color: #1f5437;
        }
        .text-block {
            background: #ffffffd9;
            padding: 1.5rem;
            margin: 1.5rem 0;
            border-radius: 24px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
        }
        .text-block p {
            margin-top: 0.8rem;
        }
        .list-block ul {
            margin: 1rem 0 1rem 2rem;
        }
        .list-block li {
            margin: 0.5rem 0;
        }
        .agu-links {
            background: #eaf7ed;
            padding: 1.5rem;
            border-radius: 28px;
            text-align: center;
            margin: 2rem 0;
        }
        .agu-links a {
            margin: 0 1rem;
            display: inline-block;
            padding: 10px 18px;
            background: #2c5e3a;
            color: white;
            text-decoration: none;
            border-radius: 40px;
            transition: 0.2s;
        }
        .agu-links a:hover {
            background: #164a27;
        }
        .author {
            background: #e2e6df;
            padding: 1.5rem;
            border-radius: 30px;
            text-align: center;
            margin: 2rem 0;
            font-style: normal;
        }
        footer {
            text-align: center;
            padding: 2rem;
            background: #1e2f2c;
            color: #ccc;
            margin-top: 2rem;
        }
        @media (max-width: 700px) {
            h1 { font-size: 2rem; }
            .hero-text h2 { font-size: 1.6rem; }
            .nav-links { gap: 1rem; }
        }
    </style>
</head>
<body>

<header>
    <div class="container">
        <h1>🌄 Адыгея — жемчужина Кавказа</h1>
        <p class="subhead">Горы, водопады, древние дольмены и гостеприимство</p>
    </div>
</header>

<nav>
    <div class="container nav-links">
        <a href="#about">О регионе</a>
        <a href="#gallery">Фотогалерея</a>
        <a href="#tips">Советы</a>
        <a href="#agu">АГУ</a>
    </div>
</nav>

<div class="hero">
    <div class="hero-text">
        <h2>Дыши свободой в сердце Кавказских гор</h2>
        <p>Лаго-Наки, Хаджохская теснина, плато и водопады</p>
    </div>
</div>

<div class="container">
    <div id="about" class="text-block">
        <h2>🏔️ Почему стоит посетить Адыгею?</h2>
        <p>Республика Адыгея — удивительное место, где бурные реки встречаются с заснеженными вершинами. Это идеальное направление для треккинга, рафтинга и культурного отдыха. Здесь живут легенды нартского эпоса, а воздух наполнен ароматами альпийских лугов. Всего за несколько часов из Майкопа можно попасть в мир дикой природы.</p>
    </div>

    <h2 id="gallery" class="section-title">📸 Визуальное путешествие</h2>
    <div class="gallery">
        <div class="card"><img src="https://images.pexels.com/photos/457882/pexels-photo-457882.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Горы Адыгеи"><div class="card-content"><h3>Хребет Уиш</h3><p>Панорама Главного Кавказского хребта</p></div></div>
        <div class="card"><img src="https://images.pexels.com/photos/3722818/pexels-photo-3722818.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Водопад Руфабго"><div class="card-content"><h3>Водопады Руфабго</h3><p>Каскад из 16 водопадов</p></div></div>
        <div class="card"><img src="https://images.pexels.com/photos/1285625/pexels-photo-1285625.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Плато Лаго-Наки"><div class="card-content"><h3>Лаго-Наки</h3><p>Альпийские луга и карстовые озёра</p></div></div>
        <div class="card"><img src="https://images.pexels.com/photos/3601423/pexels-photo-3601423.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Дольмены"><div class="card-content"><h3>Дольмены</h3><p>Древние мегалиты возрастом 4000 лет</p></div></div>
        <div class="card"><img src="https://images.pexels.com/photos/1191710/pexels-photo-1191710.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Хаджохская теснина"><div class="card-content"><h3>Хаджохская теснина</h3><p>Ущелье реки Белой</p></div></div>
        <div class="card"><img src="https://images.pexels.com/photos/3611050/pexels-photo-3611050.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Сыры адыгейские"><div class="card-content"><h3>Адыгейский сыр</h3><p>Гастрономический символ</p></div></div>
    </div>

    <div class="text-block">
        <h2>🍃 Что посмотреть за 3 дня?</h2>
        <p>Идеальный маршрут: 1 день – плато Лаго-Наки, 2 день – водопады Руфабго и Хаджохская теснина, 3 день – поход к дольменам и дегустация национальной кухни. Обязательно попробуйте адыгейский сыр, хычины и шашлык из мраморной говядины.</p>
    </div>

    <div class="list-block text-block">
        <h2>✅ Топ-5 активностей в Адыгее</h2>
        <ul>
            <li><strong>Треккинг на Фишт или Оштен</strong> – восхождения разной сложности.</li>
            <li><strong>Рафтинг по реке Белой</strong> – пороги от 3 до 5 категории.</li>
            <li><strong>Посещение стоянки древнего человека</strong> в пещере.</li>
            <li><strong>Фотосессия на смотровых</strong> плато Утюг и гора Азиш-Тау.</li>
            <li><strong>Этно-ужин в ауле Уляп</strong> с мастер-классом по адыгским танцам.</li>
        </ul>
    </div>

    <div class="text-block">
        <h2>🏞️ Интересный факт</h2>
        <p>Адыгея – один из немногих регионов России, где расположен объект Всемирного наследия ЮНЕСКО «Западный Кавказ». Здесь обитают редкие животные: зубр, кавказский тур и серна.</p>
    </div>

    <div class="text-block">
        <h2>🌤️ Когда ехать?</h2>
        <p>Лучшее время: май–октябрь. Летом комфортно +22..+28, осенью – золотая листва. Зимой приезжают ради снежных видов и катания на сноуборде (курорт «Лаго-Наки»).</p>
    </div>

    <div class="text-block">
        <h2>🚗 Как добраться?</h2>
        <p>Ближайший аэропорт – Краснодар (Пашковский) или Минеральные Воды. Оттуда на такси или автобусе до Майкопа (столица Адыгеи). Далее на личном авто или экскурсионном транспорте.</p>
    </div>

    <div id="agu" class="agu-links">
        <p style="margin-bottom: 1rem; font-weight: bold;">🎓 Официальная информация от Адыгейского государственного университета</p>
        <a href="https://adygnet.ru/" target="_blank">Сайт АГУ</a>
        <a href="https://t.me/adygstateuniversity" target="_blank">Telegram АГУ</a>
        <a href="https://vk.com/adygstateuniversity" target="_blank">ВКонтакте АГУ</a>
    </div>

    <!-- БЛОК АВТОРА — ЭКОНОМИЧЕСКИЙ ФАКУЛЬТЕТ -->
    <div class="author">
        <h3>📌 Об авторе проекта</h3>
        <p><strong>Галаев Саид-Магомед</strong> – студент <strong>экономического факультета</strong> Адыгейского государственного университета.<br>
        Увлекаюсь веб-разработкой, туризмом и создаю удобные путеводители по родной республике.<br>
        📧 said.galaev@edu.adygnet.ru | 🌄 @galaev_adventure<br>
        *Сайт разработан в рамках учебного задания по дисциплине "Веб-технологии".</p>
    </div>
</div>

<footer>
    <p>© 2026 Путеводитель по Адыгее | Все фото – иллюстративные, с бесплатных источников Pexels</p>
    <p style="margin-top: 0.5rem;">#Адыгея #АГУ #Путешествия</p>
</footer>

</body>
</html>
