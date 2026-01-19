<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Gamingenzoo</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            background-color: #64CDE8;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            font-family: Arial, sans-serif;
        }
        h1 {
            font-size: 48px;
            margin-bottom: 40px;
        }
        button {
            width: 240px;
            padding: 15px;
            margin: 12px;
            font-size: 20px;
            border: none;
            border-radius: 12px;
            cursor: pointer;
            background-color: white;
            box-shadow: 0 6px 12px rgba(0,0,0,0.25);
            transition: 0.2s;
        }
        button:hover {
            transform: scale(1.08);
            background-color: #f0f0f0;
        }
    </style>
</head>
<body>
    <h1>Gamingenzoo</h1>
    <button onclick="openLink('https://www.instagram.com/xgamingenzoo/')">
        Instagram
    </button>
    <button onclick="openLink('https://www.youtube.com/@gamingenzoo')">
        YouTube
    </button>
    <button onclick="openLink('https://www.twitch.tv/gamingenzoo')">
        Twitch
    </button>
    <script>
        function openLink(url) {
            window.open(url, "_blank");
        }
    </script>

</body>
</html>



