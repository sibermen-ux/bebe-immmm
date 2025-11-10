hayatımmmm
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KOCANDAN SANA UFAK BİR HEDİYE  💖🌸💋🫶</title>
<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background: linear-gradient(135deg, #ffb3c6, #d1c0ff, #a0e9ff);
        overflow-x: hidden;
        color: #fff;
    }

    h1 {
        text-align: center;
        padding: 20px;
        font-size: 2.5em;
        text-shadow: 2px 2px 5px #000;
    }

    .container {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        padding: 20px;
        gap: 20px;
    }

    .card {
        background: rgba(255, 255, 255, 0.1);
        border-radius: 20px;
        padding: 20px;
        width: 250px;
        min-height: 100px;
        box-shadow: 0 8px 15px rgba(0,0,0,0.2);
        position: relative;
        overflow: hidden;
        transition: transform 0.3s, box-shadow 0.3s;
        backdrop-filter: blur(10px);
    }

    .card:hover {
        transform: scale(1.05);
        box-shadow: 0 12px 20px rgba(0,0,0,0.3);
    }

    .heart {
        color: #ff4d6d;
        font-size: 1.2em;
        margin-right: 5px;
    }

    .emoji {
        position: absolute;
        font-size: 1.5em;
        pointer-events: none;
        animation: floatUp linear infinite;
    }

    @keyframes floatUp {
        0% { transform: translateY(0) rotate(0deg); opacity: 1; }
        100% { transform: translateY(-600px) rotate(360deg); opacity: 0; }
    }
</style>
</head>
<body>

<h1>💖 Aşkın Uçuşan Şiirleri 🌸💋🫶</h1>

<div class="container" id="poemsContainer">
    <div class="card"><p><span class="heart">❤️</span>Seninle her an bir şiir... 🌸💋🫶</p></div>
    <div class="card"><p><span class="heart">💖</span>Kalbim sadece senin melodinle çarpıyor. 🌹🫶</p></div>
    <div class="card"><p><span class="heart">💌</span>Gözlerin bir yıldız, ruhum onun ışığında. 🌟🫶</p></div>
</div>

<script>
    const emojis = ['❤️','💋','🌸','🌹','💌','🫶'];
    function createEmoji() {
        const emoji = document.createElement('div');
        emoji.className = 'emoji';
        emoji.textContent = emojis[Math.floor(Math.random() * emojis.length)];
        emoji.style.left = Math.random() * window.innerWidth + 'px';
        emoji.style.animationDuration = (5 + Math.random() * 5) + 's';
        document.body.appendChild(emoji);
        setTimeout(() => emoji.remove(), 10000);
    }

    setInterval(createEmoji, 500);
</script>

</body>
</html>
