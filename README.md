# vector.github.io
A website for Vector's Creations

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ved Mods</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background: linear-gradient(135deg,#000000,#111111,#1a1a1a);
    min-height:100vh;
    color:white;
}

header{
    padding:25px;
    text-align:center;
    border-bottom:1px solid rgba(255,215,0,0.2);
}

.logo{
    font-size:3rem;
    font-weight:bold;
    color:#FFD700;
    text-shadow:0 0 15px rgba(255,215,0,0.5);
}

.subtitle{
    color:#d4af37;
    margin-top:10px;
}

.container{
    max-width:1200px;
    margin:auto;
    padding:50px 20px;
}

.hero{
    text-align:center;
    margin-bottom:50px;
}

.hero h1{
    font-size:3rem;
    color:#FFD700;
}

.hero p{
    margin-top:15px;
    color:#ccc;
}

.buttons{
    margin-top:35px;
    display:flex;
    justify-content:center;
    gap:20px;
    flex-wrap:wrap;
}

/* Glass Buttons */
.glass-btn{
    padding:15px 35px;
    border-radius:20px;
    border:1px solid rgba(255,255,255,0.15);
    background:rgba(255,255,255,0.08);
    backdrop-filter:blur(15px);
    -webkit-backdrop-filter:blur(15px);
    color:#FFD700;
    text-decoration:none;
    font-weight:bold;
    transition:0.3s;
    box-shadow:
        0 8px 32px rgba(0,0,0,0.4),
        inset 0 1px 1px rgba(255,255,255,0.2);
}

.glass-btn:hover{
    transform:translateY(-4px);
    background:rgba(255,215,0,0.15);
    box-shadow:
        0 0 25px rgba(255,215,0,0.4);
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:25px;
}

.card{
    background:rgba(255,255,255,0.05);
    backdrop-filter:blur(15px);
    border:1px solid rgba(255,215,0,0.15);
    border-radius:20px;
    padding:25px;
}

.card h2{
    color:#FFD700;
    margin-bottom:10px;
}

.card p{
    color:#ddd;
}

footer{
    text-align:center;
    padding:30px;
    margin-top:50px;
    color:#888;
}
</style>
</head>
<body>

<header>
    <div class="logo">VED MODS</div>
    <div class="subtitle">Minecraft Mods & Texture Packs</div>
</header>

<div class="container">

    <div class="hero">
        <h1>Premium Minecraft Creations</h1>
        <p>Download mods, texture packs, and custom projects.</p>

        <div class="buttons">
            <a href="#" class="glass-btn">Mods</a>
            <a href="#" class="glass-btn">Texture Packs</a>
            <a href="#" class="glass-btn">Downloads</a>
            <a href="#" class="glass-btn">Discord</a>
        </div>
    </div>

    <div class="cards">
        <div class="card">
            <h2>Latest Mod</h2>
            <p>Showcase your newest Minecraft mod here.</p>
        </div>

        <div class="card">
            <h2>Featured Pack</h2>
            <p>Highlight your best texture pack.</p>
        </div>

        <div class="card">
            <h2>Updates</h2>
            <p>Post changelogs and announcements.</p>
        </div>
    </div>

</div>

<footer>
    © 2026 Ved Mods
</footer>

</body>
</html>
