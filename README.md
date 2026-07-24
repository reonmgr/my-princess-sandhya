<!DOCTYPE html>
<html>
<head>
<title>My Princess Sandhya ❤️</title>

<style>

body {
margin:0;
font-family:Georgia,serif;
background:linear-gradient(#ffd1e3,#fff5fa);
color:#8b1e4a;
text-align:center;
overflow-x:hidden;
}

#intro {
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
background:linear-gradient(#ffb6d9,#ffeaf3);
}

.intro-heart {
font-size:90px;
animation:beat 1s infinite;
}

@keyframes beat {
50% {transform:scale(1.2);}
}

.container {
padding:20px;
}

.card {
background:white;
max-width:500px;
margin:25px auto;
padding:25px;
border-radius:25px;
box-shadow:0 5px 15px #ddd;
}

button {
background:#ff5c9a;
color:white;
border:0;
padding:15px 25px;
border-radius:30px;
font-size:18px;
}

.heart {
font-size:60px;
animation:beat 1s infinite;
}

.petal {
position:fixed;
top:-20px;
font-size:25px;
animation:fall linear infinite;
z-index:10;
}

@keyframes fall {
to {
transform:translateY(110vh) rotate(360deg);
}
}

#secret {
display:none;
}

.gallery {
display:grid;
grid-template-columns:repeat(3,1fr);
gap:10px;
}

.gallery img {
width:100%;
height:120px;
object-fit:cover;
border-radius:15px;
}

</style>

</head>


<body>


<div id="intro">

<div class="intro-heart">❤️</div>

<h1>For My Princess Sandhya 💖</h1>

<p>A little surprise from Roshan</p>

<button onclick="openPage()">Open My Heart 💌</button>

</div>



<div class="container" id="main" style="display:none;">


<h1>My cutiee Sandhya 💖</h1>

<div class="heart">❤️</div>



<div class="card">

<h2>A message for you 🌹</h2>

<p>
Babyy💗 I made this little world just for you.
<br><br>
No matter how far we are, you are always close to my heart.
Thank you for bringing happiness into my life.
</p>

</div>



<div class="card">

<h2>Our Memories 📸❤️</h2>

<div class="gallery">

<img src="IMG-20260603-WA0000.jpg">
<img src="IMG-20260603-WA0033.jpg">
<img src="IMG-20260603-WA0044.jpg">
<img src="IMG-20260714-WA0043.jpg">
<img src="IMG-20260714-WA0054.jpg">
<img src="IMG-20260714-WA0056.jpg">
<img src="IMG-20260716-WA0013.jpg">
<img src="IMG-20260716-WA0017.jpg">
<img src="IMG-20260603-WA0048.jpg">

</div>

<p>
Every picture carries a memory I treasure ❤️
</p>

</div>



<div class="card">

<h2>Why I Love You ❤️</h2>

<p>
Your smile ❤️<br><br>
Your kindness 🥰<br><br>
Your beautiful heart 💖<br><br>
The way you make ordinary moments special 💝<br><br>
The memories we create together 💘<br><br>
Simply because you are Sandhya ❤️
</p>

</div>




<div class="card">

<h2>Secret Message 💌</h2>

<button onclick="secret()">Tap Here ❤️</button>

<p id="secret">
My dearest budi Sandhya🫶🏻🙆🏻💕
<br><br>
Whenever you doubt yourself, remember that there is someone who feels lucky to have you.
I love you in every universe ❤️♾️
</p>

</div>




<div class="card">

<h2>My Promise 💖</h2>

<p>
Baby🥺💐💗
<br><br>
I will always try to make you feel loved, respected, and special.
Distance may separate us physically, but my heart is always with you.
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


function secret(){
document.getElementById("secret").style.display="block";
}


for(let i=0;i<30;i++){

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
