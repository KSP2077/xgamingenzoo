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
            font-size: clamp(32px, 6vw, 48px);
            margin-bottom: 30px;
        }
        .btn {
            width: 100%;
            max-width: 360px;
            padding: 16px;
            margin: 10px 0;
            font-size: 18px;
            border: none;
            border-radius: 14px;
            cursor: pointer;
            color: white;
            box-shadow: 0 6px 12px rgba(0,0,0,0.25);
            transition: 0.2s;
        }
        .btn:hover {
            transform: scale(1.05);
        }
        /* Couleurs */
        .insta1 { background-color: #9900FF; }
        .youtube { background-color: #FF0000; }
        .twitch { background-color: #C600FF; }
        .insta2 { background-color: #7A00CC; }
        .btn:active {
            transform: scale(0.97);
        }
    </style>
</head>
<body>
    <h1>Gamingenzoo</h1>
    <button class="btn insta1"
        onclick="openLink('https://www.instagram.com/xgamingenzoo/')">
        📸 Instagram gamingenzoo
    </button>
    <button class="btn youtube"
        onclick="openLink('https://www.youtube.com/@gamingenzoo')">
        ▶️ YouTube
    </button>
    <button class="btn twitch"
        onclick="openLink('https://www.twitch.tv/gamingenzoo')">
        🎮 Twitch
    </button>
    <button class="btn insta2"
        onclick="openLink('https://www.instagram.com/gamingenzoo_tv/')">
        📸 Instagram gamingenzoo_tv
    </button>
    <script>
        function openLink(url) {
            window.open(url, "_blank");
        }
    </script>

</body>
</html>


