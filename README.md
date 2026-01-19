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
        .container {
            position: relative;
            width: 500px;
            max-width: 90%;
        }
        /* Image de fond */
        .bg-image {
            width: 100%;
            border-radius: 12px;
        }
        /* Texte sur l'image */
        .title {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: white;
            font-size: clamp(24px, 4vw, 36px);
            font-weight: bold;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.7);
            text-align: center;
        }
        /* Boutons sous l'image */
        .btn {
            width: 100%;
            max-width: 300px;
            padding: 15px;
            margin: 10px 0;
            font-size: 18px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            color: white;
            transition: 0.2s;
        }
        /* Couleurs plateformes */
        .instagram { background-color: #9900FF; }
        .youtube { background-color: #FF0000; }
        .twitch { background-color: #C600FF; }
        .btn:hover { transform: scale(1.05); }
        @media (max-width: 600px) {
            .title { font-size: clamp(20px, 5vw, 28px); }
            .btn { font-size: 16px; }
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="kksspp.jpg" alt="Fond" class="bg-image">
        <div class="title">Gamingenzoo</div>
    </div>
    <button class="btn instagram" onclick="openLink('https://www.instagram.com/x





