<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Vector Domain</title>

<!-- 🎮 Minecraft Pixel Font -->
<link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">

<style>

/* 🌅 Animated sunset background */
body{
    margin:0;
    color:white;
    text-align:center;
    min-height:100vh;

    background: linear-gradient(120deg,
        #000000,
        #1a0a0a,
        #3b1c0f,
        #ff4d00,
        #ffb347
    );

    background-size:400% 400%;
    animation: sunset 12s ease infinite;

    font-family: Arial;
}

@keyframes sunset{
    0%{background-position:0% 50%;}
    50%{background-position:100% 50%;}
    100%{background-position:0% 50%;}
}

/* ⚡ NAVBAR */
.navbar{
    position:sticky;
    top:0;
    width:100%;
    padding:15px 25px;
    display:flex;
    justify-content:space-between;
    align-items:center;

    background:rgba(0,0,0,0.75);
    backdrop-filter:blur(15px);
    border-bottom:1px solid rgba(255,215,0,0.25);

    box-shadow:0 0 25px rgba(255,215,0,0.2);

    font-family:'Press Start 2P', cursive;
}

.logo{
    font-size:12px;
    color:#FFD700;
    text-shadow:0 0 10px rgba(255,215,0,0.8);
}

.nav-links{
    display:flex;
    gap:12px;
    flex-wrap:wrap;
}

.nav-links a{
    font-size:9px;
    color:#FFD700;
    text-decoration:none;
    padding:10px;
    border-radius:8px;
    transition:0.3s;
}

.nav-links a:hover{
    background:rgba(255,215,0,0.12);
    box-shadow:0 0 15px rgba(255,215,0,0.6);
    transform:translateY(-2px);
}

/* 🧊 Glass UI */
.glass{
    margin-top:40px;
    display:inline-block;
    padding:30px;
    border-radius:20px;
    background:rgba(255,255,255,0.07);
    border:1px solid rgba(255,215,0,0.2);
    backdrop-filter:blur(15px);
}

/* ✨ Buttons */
.btn{
    display:inline-block;
    margin:10px;
    padding:15px 25px;
    border-radius:15px;
    background:rgba(255,215,0,0.15);
    border:1px solid rgba(255,215,0,0.3);
    color:#FFD700;
    text-decoration:none;
    transition:0.3s;
}

.btn:hover{
    transform:translateY(-5px);
    background:rgba(255,215,0,0.25);
}

h1{
    color:#FFD700;
}

p{
    color:#ddd;
}

</style>
</head>

<body>

<!-- ⚡ NAVBAR -->
<div class="navbar">
    <div class="logo">VECTOR DOMAIN</div>

    <div class="nav-links">
        <a href="index.html">Home</a>
        <a href="mods.html">Mods</a>
        <a href="textures.html">Textures</a>
        <a href="downloads.html">Downloads</a>
        <a href="support.html">Support</a>
        <a href="discord.html">Discord</a>
    </div>
</div>

<!-- 🏠 MAIN CONTENT -->
<h1>Welcome to Vector Domain</h1>
<p>Minecraft Mods • Texture Packs • Future Projects</p>

<div class="glass">

    <h2>Explore</h2>

    <a class="btn" href="mods.html">Mods</a>
    <a class="btn" href="textures.html">Texture Packs</a>
    <a class="btn" href="downloads.html">Downloads</a>
    <a class="btn" href="support.html">Support Me</a>
    <a class="btn" href="discord.html">Discord</a>

</div>

</body>
</html>
