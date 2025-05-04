# Karinaakxx.github.io.
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Каріна Камінська</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>Привіт, я Каріна Камінська!</h1>
        </header>
        <section class="content">
            <p>Це мій персональний сайт.</p>
            <p>Тут я поділюсь своїми проектами і ідеями!</p>
        </section>
        <footer>
            <p>Контакти: <a href="mailto:karina@example.com">karina@example.com</a></p>
        </footer>
    </div>
</body>
</html>
/* Загальні стилі */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: black;
    color: white;
    text-align: center;
    line-height: 1.6;
}

/* Стилі для контейнера */
.container {
    max-width: 1200px;
    margin: 0 auto;
}

/* Стилі для хедера */
header {
    margin-top: 50px;
    font-size: 2.5em;
    color: white;
}

/* Стилі для контенту */
.content {
    margin-top: 30px;
    font-size: 1.2em;
}

/* Стилі для футера */
footer {
    margin-top: 50px;
    font-size: 1em;
}

footer a {
    color: lightgray;
    text-decoration: none;
}

footer a:hover {
    text-decoration: underline;
}

/* Розмитий фон внизу */
body::after {
    content: "";
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 150px;
    background: rgba(0, 0, 0, 0.5);
    backdrop-filter: blur(10px);
}
