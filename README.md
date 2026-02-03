<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Veux-tu être ma Valentine ? 💖</title>

<style>
body {
background: linear-gradient(135deg, #ff9a9e, #fad0c4);
font-family: 'Arial', sans-serif;
text-align: center;
height: 100vh;
margin: 0;
display: flex;
justify-content: center;
align-items: center;
}

.card {
background: white;
padding: 30px;
border-radius: 20px;
box-shadow: 0 15px 30px rgba(0,0,0,0.2);
max-width: 350px;
}

h1 {
color: #ff4d6d;
}

img {
width: 100%;
border-radius: 15px;
margin: 15px 0;
}

.buttons {
margin-top: 20px;
}

button {
padding: 12px 25px;
border: none;
border-radius: 25px;
font-size: 18px;
cursor: pointer;
margin: 10px;
}

#yes {
background: #ff4d6d;
color: white;
}

#no {
background: #ccc;
position: absolute;
}
</style>
</head>

<body>

<div class="card">
<h1>Veux-tu être ma Valentine ? 💘</h1>

<img src=IMG_8582.jpeg

<div class="buttons">
<button id="yes" onclick="yes()">Oui 💖</button>
<button id="no" onmouseover="moveNo()">Non 😢</button>
</div>
</div>

<script>
function yes() {
document.body.innerHTML = `
<div style="text-align:center;">
<h1 style="color:#ff4d6d;">YAAAY 💕</h1>
<p>Je suis trop heureux de t'avoir Cathy OUAIIIIIIIIIS) 🥰</p>
<img src=79184277982__C57F6D94-1573-477E-83D1-36814B9A2CF8.jpeg
</div>
`;
}

function moveNo() {
const no = document.getElementById("no");
const x = Math.random() * (window.innerWidth - 100);
const y = Math.random() * (window.innerHeight - 50);
no.style.left = x + "px";
no.style.top = y + "px";
}
</script>

</body>
</html>
