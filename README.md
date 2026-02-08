<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Gamingenzoo</title>

<style>
/* ===== FOND IMAGE ===== */
body{
    margin:0;
    height:100vh;
    background:url("ksppfpv.jpg") center/cover no-repeat;
    display:flex;
    justify-content:center;
    align-items:center;
    font-family: Arial, sans-serif;
}

/* ===== PANNEAU CENTRAL (comme Frame Tkinter) ===== */
.panel{
    background: rgba(0,0,0,0.75);
    backdrop-filter: blur(8px);
    padding:40px;
    border-radius:20px;
    text-align:center;
    width:90%;
    max-width:400px;
    box-shadow:0 15px 40px rgba(0,0,0,0.6);
}

/* ===== TITRE ===== */
h1{
    color:white;
    margin-bottom:25px;
    font-size:30px;
}

/* ===== BOUTONS ===== */
.btn{
    width:100%;
    padding:14px;
    margin:8px 0;
    border:none;
    border-radius:12px;
    font-size:16px;
    font-weight:bold;
    color:white;
    cursor:pointer;
    transition:0.25s;
}

.btn:hover{
    transform:scale(1.06);
    box-shadow:0 6px 20px rgba(0,0,0,0.5);
}

.btn:active{
    transform:scale(0.96);
}

/* Couleurs */
.insta{background:#9900FF;}
.youtube{background:#FF0000;}
.twitch{background:#C600FF;}
.playlist{background:#ff8800;}
.insta2{background:#7A00CC;}

/* Responsive */
@media(max-width:500px){
    h1{font-size:22px;}
    .panel{padding:25px;}
}
</style>
</head>

<body>

<div class="panel">

    <h1>🎮 Gamingenzoo</h1>

    <button class="btn insta"
        onclick="openLink('https://www.instagram.com/xgamingenzoo/')">
        📸 Instagram gamingenzoo
    </button>

    <button class="btn youtube"
        onclick="openLink('https://www.youtube.com/@gamingenzoo')">
        ▶️ YouTube
    </button>

    <button class="btn twitch"
        onclick="openLink('https://www.twitch.tv/gamingenzoo')">
        🟣 Twitch
    </button>

    <button class="btn playlist"
        onclick="openLink('https://www.youtube.com/@gamingenzoo/playlists')">
        📂 Playlists
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
