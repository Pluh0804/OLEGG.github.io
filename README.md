# OLEGG.github.io 
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ты пришёл не туда</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #222;
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            text-align: center;
        }
        h1 {
            font-size: 3em;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px #000;
        }
        .meme-img {
            max-width: 300px;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
            transition: transform 0.3s;
        }
        .meme-img:hover {
            transform: scale(1.05);
        }
        .footer {
            margin-top: 30px;
            opacity: 0.7;
        }
    </style>
</head>
<body>
    <h1>Ты пришёл не туда...</h1>
    <img 
        class="meme-img" 
        src="https://i.kym-cdn.com/entries/icons/original/000/026/489/crying.jpg" 
        alt="Грустный Шрек"
        title="Почему ты здесь?">
    <div class="footer">Попробуйте Google: <a href="https://google.com" style="color: #4CAF50;">спасение тут</a></div>

    <script>
        // Небольшая "пасхалка" при клике на картинку
        document.querySelector('.meme-img').addEventListener('click', function() {
            alert('🚀 А может, это мы пришли не туда?..');
        });
    </script>
</body>
</html>
