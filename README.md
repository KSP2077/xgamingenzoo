<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>

<title>Gamingenzoo</title>

<style>
/* ===== Fond général ===== */
body {
    margin: 0;
    min-height: 100vh;
    background: linear-gradient(135deg, #64CDE8, #3aa6c4);
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: Arial, sans-serif;
}

/* ===== Carte centrale ===== */
.card {
    backdrop-filter: blur(12px);
    background: rgba(255,255,255,0.12);
    border-radius: 25px;
    padding: 35px;
    width: 95%;
    max-width: 420px;
    text-align: center;
    box-shadow: 0 20px 50px rgba(0,0,0,0.35);
}

/* ===== Image ===== */
.card img {
    width: 100%;
    border-radius: 18px;
    margin-bottom: 20px;
}

/* ===== Titre ===== */
h1 {
    color: white;
    margin-bottom: 25px;
    font-size: 32px;
    letter-spacing: 2px;
}

/* ===== Boutons ===== */
.btn {
    display: block;
    width: 100%;
    padding: 14px;
    margin: 10px 0;
    border-radius: 14px;
    border: none;
    font-size: 17px;
    font-weight: bold;
    color: white;
    cursor: pointer;
    transition: 0.25s;
}

/* couleurs */
.insta1 { background: #9900FF; }
.youtube { background: #FF0000; }
.twitch { background: #C600FF; }
.insta2 { background: #7A00CC; }

.btn:hover {
    transform: scale(1.07);
    box-shadow: 0 8px 20px rgba(0,0,0,0.4);
}

.btn:active {
    transform: scale(0.96);
}

/* Responsive mobile */
@media(max-width:500px){
    .card { padding: 20px; }
    h1 { font-size: 26px; }
}
</style>
</head>


<body>

<div class="card">
    <img src="kksspp.jpg" alt="Gamingenzoo">
    <h1>🎮 Gamingenzoo</h1>
    <button class="btn insta1"
        onclick="openLink('https://www.instagram.com/xgamingenzoo/')">
        📸 Instagram xgamingenzoo
    </button>
    <button class="btn youtube"
        onclick="openLink('https://www.youtube.com/@gamingenzoo')">
        ▶️ YouTube
    </button>
    <button class="btn twitch"
        onclick="openLink('https://www.twitch.tv/gamingenzoo')">
        🟣 Twitch
    </button>
    <button class="btn insta2"
        onclick="openLink('https://www.instagram.com/gamingenzoo_tv/')">
        📸 Instagram TV
    </button>
</div>


<script>
function openLink(url){
    window.open(url, "_blank");
}
</script>

</body>
</html>


