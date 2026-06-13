# vector.github.io
A website for Vector's Creations

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Vector Domain</title>

<style>
body{
    margin:0;
    font-family:Arial;
    background:linear-gradient(135deg,#000,#111,#1a1a1a);
    color:white;
}

header{
    text-align:center;
    padding:25px;
    border-bottom:1px solid rgba(255,215,0,0.2);
}

.logo{
    font-size:3rem;
    font-weight:bold;
    color:#FFD700;
}

.subtitle{ color:#d4af37; }

.container{
    text-align:center;
    padding:60px 20px;
}

.glass-btn{
    display:inline-block;
    margin:10px;
    padding:15px 30px;
    border-radius:18px;
    background:rgba(255,255,255,0.08);
    border:1px solid rgba(255,255,255,0.2);
    color:#FFD700;
    text-decoration:none;
    backdrop-filter:blur(15px);
    transition:0.3s;
}

.glass-btn:hover{
    transform:translateY(-5px);
    background:rgba(255,215,0,0.15);
}
</style>
body{
    margin:0;
    font-family:Arial;
    color:white;
    text-align:center;
    min-height:100vh;

    /* 🌅 Sunset background */
    background: linear-gradient(120deg,
        #000000,
        #1a0a0a,
        #3b1c0f,
        #ff4d00,
        #ffb347
    );
    background-size: 400% 400%;
    animation: sunset 12s ease infinite;
}

@keyframes sunset{
    0%{background-position:0% 50%;}
    50%{background-position:100% 50%;}
    100%{background-position:0% 50%;}
}

.glass{
    background:rgba(255,255,255,0.07);
    border:1px solid rgba(255,215,0,0.2);
    backdrop-filter:blur(15px);
    border-radius:20px;
    padding:30px;
    display:inline-block;
}

.btn{
    display:inline-block;
    margin-top:20px;
    padding:15px 30px;
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
</head>

<body>

<header>
    <div class="logo">Vector Domain</div>
    <div class="subtitle">Minecraft Mods & Texture Packs</div>
</header>

<div class="container">

<h1 style="color:#FFD700;">Welcome</h1>
<p>Choose a page below</p>

<!-- LINKS TO OTHER PAGES -->
<a class="glass-btn" href="mods.html">Mods</a>
<a class="glass-btn" href="textures.html">Texture Packs</a>
<a class="glass-btn" href="downloads.html">Downloads</a>
<a class="glass-btn" href="discord.html">Discord</a>
<a class="glass-btn" href="patreon.html">Patreon</a>
<div style="margin-top:60px; padding:30px; border:1px solid rgba(255,215,0,0.2); border-radius:20px; background:rgba(255,255,255,0.05);">

    <h2 style="color:#FFD700; font-size:2rem;">⭐ Support Me</h2>

    <p style="color:#ccc; margin-top:10px;">
        Join my Patreon to support development of Minecraft mods, texture packs, and future projects.
    </p>

    <a class="glass-btn" 
       href="https://www.patreon.com/c/vectorr_11/membership" 
       target="_blank"
       style="margin-top:20px;">
        Join Patreon
    </a>

</div>
</div>

</body>
</html>


