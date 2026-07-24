<!DOCTYPE html>
<html>
<head>
<title>My Princess Sandhya ❤️</title>

<style>
body {
  margin: 0;
  font-family: Georgia, serif;
  background: linear-gradient(#ffd6e7,#fff5fa);
  text-align: center;
  color: #8b1e4a;
  overflow-x: hidden;
}

#intro {
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: #ffd1e3;
}

.intro-heart {
  font-size: 90px;
  animation: beat 1s infinite;
}

@keyframes beat {
  50% {
    transform: scale(1.2);
  }
}

.container {
  padding: 30px 20px;
}

.card {
  background: white;
  max-width: 500px;
  margin: 25px auto;
  padding: 25px;
  border-radius: 25px;
}

button {
  background: #ff5c9a;
  color: white;
  border: none;
  padding: 15px 25px;
  border-radius: 30px;
  font-size: 18px;
}

.heart {
  font-size: 60px;
  animation: beat 1s infinite;
}

.petal {
  position: fixed;
  top: -20px;
  animation: fall linear infinite;
}

@keyframes fall {
  to {
    transform: translateY(100vh);
  }
}

#secret {
  display: none;
}
</style>

</head>

<body>

<div id="intro">

<div class="intro-heart">❤️</div>

<h1>For My Princess Sandhya 💖</h1>

<p>A surprise from Roshan</p>

<button onclick="openPage()">Open My Heart 💌</button>

</div>


<div class="container" id="main" style="display:none;">

<h1>My Princess Sandhya 💖</h1>

<div class="heart">❤️</div>


<div class="card">
<h2>For You 🌹</h2>

<p>
Baby, I made this little page just for you.
<br><br>
Even with distance between us, you are always close to my heart.
</p>

</div>


<div class="card">

<h2>Why I Love You ❤️</h2>

<p>
Your smile ❤️<br><br>
Your kindness ❤️<br><br>
Your beautiful heart ❤️<br><br>
The memories we share ❤️<br><br>
The happiness you bring to my life ❤️
</p>

</div>


<div class="card">

<h2>Secret Message 💌</h2>

<button onclick="showSecret()">Tap Here ❤️</button>

<p id="secret">
You are my special person, Sandhya.
Never forget how much you mean to me. ❤️
</p>

</div>


<div class="card">

<h2>My Promise 💖</h2>

<p>
My dear budi Sandhya,
<br><br>
Thank you for being a beautiful part of my life.
I will always try to make you feel loved and special.
<br><br>
Forever yours,
<br>
Roshan ❤️
</p>

</div>


</div>


<script>

function openPage(){
document.getElementById("intro").style.display="none";
document.getElementById("main").style.display="block";
}

function showSecret(){
document.getElementById("secret").style.display="block";
}


for(let i=0;i<20;i++){

let p=document.createElement("div");

p.className="petal";

p.innerHTML="🌸";

p.style.left=Math.random()*100+"vw";

p.style.animationDuration=(3+Math.random()*5)+"s";

document.body.appendChild(p);

}

</script>


</body>
</html>
