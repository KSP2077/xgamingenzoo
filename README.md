<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>xgamingenzoo</title>

    <!-- CSS -->
    <style>
        body {
            margin: 0;
            background-color: #64CDE8;
            font-family: Arial, sans-serif;
            text-align: center;
        }

        header {
            background-color: #003344;
            padding: 20px;
            color: white;
            font-size: 30px;
        }

        .container {
            margin-top: 80px;
        }

        p {
            font-size: 18px;
            color: #003344;
        }

        button {
            display: block;
            margin: 20px auto;
            padding: 15px 30px;
            font-size: 18px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            width: 220px;
        }

        .youtube {
            background-color: red;
            color: white;
        }

        .instagram {
            background-color: #E1306C;
            color: white;
        }

        .twitch {
            background-color: #9146FF;
            color: white;
        }

        button:hover {
            opacity: 0.8;
        }
    </style>
</head>

<body>

    <header>
        xgamingenzoo
    </header>

    <div class="container">
        <p>Chaîne gaming 🔥<br>YouTube • Instagram • Twitch</p>

        <button class="youtube" onclick="openYoutube()">YouTube</button>
        <button class="instagram" onclick="openInstagram()">Instagram</button>
        <button class="twitch" onclick="openTwitch()">Twitch</button>
    </div>

    <!-- JavaScript -->
    <script>
        function openYoutube() {
            window.open("https://www.youtube.com/@gamingenzoo");
        }

        function openInstagram() {
            window.open("https://www.instagram.com/xgamingenzoo/");
        }

        function openTwitch() {
            window.open("https://www.twitch.tv/gamingenzoo");
        }
    </script>

</body>
</html>
