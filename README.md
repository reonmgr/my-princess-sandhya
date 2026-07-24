<!DOCTYPE html>
<html>
<head>
<title>My Princess Sandhya ❤️</title>
<s#intro {
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

#intro button {
margin-top:20px;
.petal {
  position: fixed;
  top: -10px;
  font-size: 25px;
  animation: fall linear infinite;
  z-index: 5;
}

@keyframes fall {
  to {
    transform: translateY(110vh) rotate(360deg);
  }
}

.secret {
  background: #ffe0ed;
  border-radius: 20px;
  padding: 20px;
  margin: 25px auto;
  max-width: 500px;
}}tyle>
<body>

<div id="intro">
  <div class="intro-heart">❤️</div>
  <h1>For My Princess Sandhya 💖</h1>
  <button onclick="openLove()">Open My Heart 💌</button>
</div>
<div id="petals"></div>
<div class="container" id="main" style="display:none;">

<h1>For My Princess Sandhya 💖</h1>

<div class="heart">❤️</div>

<div class="card">
<h2>A little surprise for you</h2>
<p>
I made this just to remind you that you are special to me.
No matter the distance between us, my heart always chooses you.
</p>
</div>

<div class="card">
<h2>Why I Love You 🌹</h2>
<p>
Your smile ❤️<br>
Your kindness ❤️<br>
Your beautiful heart ❤️<br>
The way you make my days better ❤️<br>
The memories we create together ❤️<br>
Simply because you are Sandhya ❤️
</p>
</div>

<div class="card">
<h2>My Promise 💌</h2>
<p>
My Princess Sandhya,<br><br>
I will always try to make you feel loved, valued, and special.
Thank you for being a beautiful part of my life.
<br><br>
Forever yours,<br>
Roshan ❤️
</p>
</div>
<div class="secret">
<h2>💌 A Secret For You</h2>
<button onclick="showSecret()">Tap Here ❤️</button>
<p id="secretText" style="display:none;">
Sandhya, even on ordinary days, you are my favorite thought.
I hope you always remember how special you are to me. ❤️
</p>
</div>

<script>
function showSecret(){
document.getElementById("secretText").style.display="block";
}
</script>
</div>

<script>
function openLove(){
 document.getElementById("intro").style.display="none";
 document.getElementById("main").style.display="block";
}
</script>
<script>
for(let i=0;i<25;i++){
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
