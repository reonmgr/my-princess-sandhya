<!DOCTYPE html>
<html>
<head>
<title>My Princess Sandhya ❤️</title>

<style>
body {
margin:0;
font-family:Georgia, serif;
background:linear-gradient(#ffd1e3,#fff5fa);
text-align:center;
color:#8b1e4a;
overflow-x:hidden;
}

#intro {
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
background:linear-gradient(#ffb6d9,#fff0f6);
}

.intro-heart {
font-size:90px;
animation:beat 1s infinite;
}

@keyframes beat {
50% {transform:scale(1.2);}
}

.container {
padding:30px 20px;
}

h1 {
font-size:38px;
}

.card, .secret {
background:white;
border-radius:25px;
padding:25px;
margin:25px auto;
max-width:500px;
box-shadow:0 5px 20px rgba(0,0,0,0.1);
}

button {
background:#ff5c9a;
color:white;
border:none;
padding:15px 25px;
border-radius:30px;
font-size:18px;
cursor:pointer;
}

.heart {
font-size:60px;
animation:beat 1s infinite;
}

.petal {
position:fixed;
top:-10px;
font-size:25px;
animation:fall linear infinite;
z-index:5;
}

@keyframes fall {
to {
transform:translateY(110vh) rotate(360deg);
}
}

#secretText {
display:none;
}

</style>

</head>

<body>

<div id="intro">

<div class="intro-heart">❤️</div>

<h1>For My Princess Sandhya 💖</h1>

<p>A little surprise from Roshan</p>

<button onclick="openLove()">
Open My Heart 💌
</button>

</div>


<div class="container" id="main" style="display:none;">

<h1>My Princess Sandhya 💖</h1>

<div class="heart">❤️</div>


<div class="card">

<h2>A message for you 🌹</h2>

<p>
Sandhya, I made this little place just for you.
<br><br>
No matter how far apart we are, you are always close to my heart.
You make my life happier just by being in it.
</p>

</div>



<div class="card">

<h2>Reasons why I love you ❤️</h2>

<p>
Your beautiful smile ❤️<br><br>
Your caring heart ❤️<br><br>
The way you make me happy ❤️<br><br>
Our memories together ❤️<br><br>
Your kindness and love ❤️<br><br>
Simply because you are you, Sandhya ❤️
</p>

</div>



<div class="secret">

<h2>💌 A Secret Message</h2>

<button onclick="showSecret()">
Tap Here ❤️
</button>

<p id="secretText">
Sandhya, whenever you feel like you are not enough,
remember that you are someone very special to me.
I am lucky to have you.
❤️
</p>

</div>



<div class="card">

<h2>My Promise 💖</h2>

<p>
My Princess Sandhya,
<br><br>
Thank you for being a beautiful part of my life.
I will always try to make you feel loved, respected, and special.
<br><br>
No matter the distance, my heart chooses you.
<br><br>
Forever yours,
<br>
Roshan ❤️
</p>

</div>


</div>



<script>

function openLove(){
document.getElementById("intro").style.display="none";
document.getElementById("main").style.display="block";
}


function showSecret(){
document.getElementById("secretText").style.display="block";
}


for(let i=0;i<30;i++){

let petal=document.createElement("div");

petal.className="petal";

petal.innerHTML="🌸";

petal.style.left=Math.random()*100+"vw";

petal.style.animationDuration=(3+Math.random()*5)+"s";

petal.style.opacity=Math.random();

document.body.appendChild(petal);

}

</script>


</body>
</html>
