<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Shrawani Ji ❤️</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:linear-gradient(135deg,#ff9a9e,#fad0c4);
min-height:100vh;
display:flex;
justify-content:center;
align-items:center;
padding:20px;
}

.container{
max-width:900px;
background:white;
padding:40px;
border-radius:20px;
box-shadow:0 10px 30px rgba(0,0,0,0.2);
text-align:center;
animation:fadeIn 2s;
}

h1{
font-size:3rem;
color:#ff3366;
margin-bottom:15px;
}

.nickname{
font-size:1.4rem;
color:#ff6699;
margin-bottom:25px;
}

.message{
font-size:1.2rem;
line-height:1.8;
color:#444;
margin-bottom:30px;
}

.btn{
background:#ff3366;
color:white;
padding:15px 35px;
border:none;
border-radius:50px;
font-size:1.1rem;
cursor:pointer;
transition:0.3s;
}

.btn:hover{
transform:scale(1.08);
background:#ff1a53;
}

.hidden{
display:none;
margin-top:30px;
animation:fadeIn 2s;
}

.proposal{
font-size:1.5rem;
color:#ff3366;
font-weight:bold;
line-height:1.8;
}

footer{
margin-top:40px;
font-size:1rem;
color:#777;
}

.hearts{
position:fixed;
width:100%;
height:100%;
pointer-events:none;
overflow:hidden;
top:0;
left:0;
}

.heart{
position:absolute;
color:red;
font-size:25px;
animation:float 6s linear infinite;
}

@keyframes float{
0%{
transform:translateY(100vh);
opacity:0;
}
100%{
transform:translateY(-100px);
opacity:1;
}
}

@keyframes fadeIn{
from{
opacity:0;
transform:translateY(20px);
}
to{
opacity:1;
transform:translateY(0);
}
}
</style>
</head>

<body>

<div class="hearts" id="hearts"></div>

<div class="container">

<h1>🎂 Happy Birthday Shrawani Ji ❤️</h1>

<div class="nickname">
My Sweet Cherry Ji 🍒
</div>

<div class="message">
Today is the most beautiful day because it is the day you came into this world.<br><br>

Your smile can brighten the darkest day, your kindness inspires everyone around you, and your presence makes life more beautiful.<br><br>

I wish you endless happiness, success, good health, and all the love you deserve. May every dream in your heart come true. ✨
</div>

<button class="btn" onclick="showProposal()">
🎁 Open Your Special Birthday Surprise
</button>

<div class="hidden" id="proposal">

<p class="proposal">
Dear Cherry Ji ❤️<br><br>

You are not just special to me...<br>
You are the reason behind many of my smiles. 😊<br><br>

The more I know you, the more I admire you.<br>
Your kindness, your beauty, and your personality make you truly unforgettable.<br><br>

On your birthday, I want to tell you something from my heart... ❤️<br><br>

🌹 I Like You 🌹<br><br>

Will you give me a chance to be a special part of your life?<br><br>

❤️ Happy Birthday Once Again, Shrawani Ji ❤️
</p>

</div>

<footer>
Made with Love for Cherry Ji ❤️
</footer>

</div>

<script>
function showProposal(){
document.getElementById("proposal").style.display="block";
}

function createHeart(){
const heart=document.createElement("div");
heart.classList.add("heart");
heart.innerHTML="❤️";
heart.style.left=Math.random()*100+"vw";
heart.style.animationDuration=(Math.random()*3+3)+"s";

document.getElementById("hearts").appendChild(heart);

setTimeout(()=>{
heart.remove();
},6000);
}

setInterval(createHeart,300);
</script>

</body>
</html>
