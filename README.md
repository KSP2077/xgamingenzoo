<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>xgamingenzoo</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

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
            font-size: 32px;
        }

        .container {
            margin-top: 60px;
            padding: 20px;
        }

        p {
            font-size: 20px;
            color: #003344;
        }

        .buttons {
            margin-top: 40px;
        }

        button {
            width: 260px;
            max-width: 90%;
            padding: 16px;
            margin: 15px auto;
            display: block;
            font-size: 18px;
            border: none;
            border-radius: 12px;
            cursor: pointer;
        }

        .youtube { background-color: red; color: white; }
        .instagram { background-color: #E1306C; color: white; }
        .twitch { background-color: #9146FF; color: white; }

        button:hover {
            opacity: 0.85;
        }

        /* 📱 Téléphone */
        @media (max-width: 600px) {
            header {
                font-size: 24px;
            }

            p {
                font-size: 16px;
            }

            button {
                font-size: 16px;
                padding: 14px;
            }
        }
    </style>
</head>

<body>

<header>xgamingenzoo</header>

<div class="container">
    <p>Chaîne gaming 🔥<br>YouTube • Instagram • Twitch</p>

    <div class="buttons">
        <button class="youtube" onclick="openYoutube()">YouTube</button>
        <button class="instagram" onclick="openInstagram()">Instagram</button>
        <button class="twitch" onclick="openTwitch()">Twitch</button>
    </div>
</div>

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

