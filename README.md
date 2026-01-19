<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Gamingenzoo</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            min-height: 100vh;
            background-color: #64CDE8;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            font-family: Arial, sans-serif;
            padding: 20px;
        }

        h1 {
            font-size: clamp(32px, 8vw, 48px);
            margin-bottom: 30px;
            text-align: center;
            color: black;
        }

        button {
            width: 100%;
            max-width: 320px;
            padding: 18px;
            margin: 10px 0;
            font-size: 18px;
            border: none;
            border-radius: 16px;
            cursor: pointer;
            color: white;
            box-shadow: 0 6px 12px rgba(0,0,0,0.25);
            transition: 0.2s;
        }

        button:hover {
            transform: scale(1.05);
        }

        button:active {
            transform: scale(0.97);
        }

        /* Couleurs plateformes */
        .youtube {
            background-color: #FF0000;
        }

        .instagram {
            background-color: #9900FF;
        }

        .twitch {
            background-color: #C600FF;
        }
    </style>
</head>
<body>

    <h1>Gamingenzoo</h1>

    <button class="instagram"
        onclick="openLink('https://www.instagram.com/xgamingenzoo/')">
        📸 Instagram
    </button>

    <button class="youtube"
        onclick="openLink('https://www.youtube.com/@gamingenzoo')">
        ▶️ YouTube
    </button>

    <button class="twitch"
        onclick="openLink('https://www.twitch.tv/gamingenzoo')">
        🎮 Twitch
    </button>

    <script>
        function openLink(url) {
            window.open(url, "_blank");
        }
    </script>

</body>
</html>



