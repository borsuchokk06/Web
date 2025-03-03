<!DOCTYPE html>
<html lang="ru">

<head>
    <meta charset="UTF-8">
    <title>Борсук Арина</title>
    <style>
        body {
            text-align: center;
        }
        
        ol {
            width: 50%;
        }
    </style>
</head>

<body>
    <header>
        <h1>Борсук Арина</h1>
        <ul>
            <li>Мой контактный номер телефона:+375336431681</li>
            <li>Мой ник в телеграмме: @borsuchokk</li>
        </ul>
    </header>
    <main>

        <section>
            <!--Блок "Факты"-->
            <h2>Интересные факты обо мне и мой интерес к web-разработке</h2>
            <p>Я учусь на 2-ом курсе университета на программиста 1 среди 20 мальчиков.Обожаю бегать по утрам,обожаю спорт и все,что с ним связано.<br>Обожаю путешествия и стараюсь это делать регулярно!</p>
            <p>В университете я изучаю С#(Back-End разработка), мне всегда было интересно попробовать себя именно во Frontend!</p>
            <p>У меня нет опыта работы и больших,на данный момент, навыков в программировании.</p>
        </section>
        <section>
            <!--Блок "Навыки"-->
            <h2>Перечень моих навыков:</h2>
            <ol>
                <li>Владение не в совершенстве языком HTML и СSS</li>
                <li>Базовые знания C#</li>
                <li>Умение работать с Windows Forms</li>
            </ol>
        </section>
        <section>
            <!--Блок "Код"-->
            <h2>Пример кода:</h2>
            <p> head meta charset="UTF-8"
                <br>link rel="icon" href="./favicon.ico" type="image/x-icon">
                <br>link rel="stylesheet" href="./styles/style.css"
                <br>link rel="preconnect" href="https://fonts.googleapis.com">
                <br> link rel="preconnect" href="https://fonts.gstatic.com" crossorigin
                <br> link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet"
            </p>
        </section>
        <section>
            <h2>Мои учебные проекты:</h2>
            <p>Курсовая на языке C#, работа с Windows Forms. Название: Видео-аудио салон. Ссылка отсуствует.</p>
        </section>
        <section>
            <h2>Пройденные курсы:</h2>
            <p>отсуствуют.</p>
        </section>
        <section>
            <h2>Уровень владения английским языком:</h2>
            <p>B2</p>
        </section>

    </main>
    <footer>
        <section class="picture">
            <h2>Мое фото:</h2>
            <!--Блок "картинка"-->
            <img src="images/arina.jpg" alt="Борсук Арина" width="300">
        </section>
    </footer>
</body>
<script>
    const tags = document.getElementsByTagName('*');
    const uniqueTags = {};


    for (let i = 0; i < tags.length; i++) {
        const tag = tags[i].tagName;
        uniqueTags[tag] = (uniqueTags[tag] || 0) + 1;
    }


    console.log(Object.keys(uniqueTags).length);
</script>

</html>
