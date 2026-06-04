<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Mithi ❤️</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    background:linear-gradient(135deg,#ff9a9e,#fad0c4,#fad0c4);
    font-family:Arial,sans-serif;
    overflow-x:hidden;
}

.card{
    width:90%;
    max-width:800px;
    padding:30px;
    border-radius:25px;
    background:rgba(255,255,255,0.2);
    backdrop-filter:blur(15px);
    box-shadow:0 8px 32px rgba(0,0,0,0.2);
    text-align:center;
    color:white;
}

h1{
    margin-bottom:20px;
    font-size:2.2rem;
}

button{
    padding:14px 30px;
    border:none;
    border-radius:50px;
    background:white;
    color:#ff4f81;
    font-size:18px;
    font-weight:bold;
    cursor:pointer;
    transition:0.3s;
}

button:hover{
    transform:scale(1.05);
}

#message{
    display:none;
    margin-top:25px;
    line-height:1.9;
    font-size:18px;
    animation:fadeIn 1.5s;
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

.heart{
    position:fixed;
    color:white;
    animation:float 8s linear infinite;
    opacity:0.7;
}

@keyframes float{
    from{
        transform:translateY(100vh);
    }
    to{
        transform:translateY(-100px);
    }
}
</style>
</head>

<body>

<div class="card">

<h1>🎂 Happy Birthday Mithi 💖</h1>

<p>Someone has a little surprise for you ✨</p>

<br>

<button onclick="showMessage()">
💝 Open Your Surprise
</button>

<div id="message">

<h2>💖 A Special Message For You 💖</h2>

<br>

<p>
Happy Birthday Mithi! 🎂💖
<br><br>

Pata nahi kaise thank you bolu, but sach me meri life ka ek important part banne ke liye thank you.
Har choti-badi baat share karne ke liye, meri bakwaas sunne ke liye,
aur har situation me saath dene ke liye thank you.
<br><br>

Bahut log milte hain zindagi me, lekin har kisi ke saath itna comfort aur trust nahi banta.
Tu sirf meri best friend nahi, balki un logon me se hai jinke saath main bina kisi hesitation ke apni baatein share kar sakta hu.
<br><br>

Chahe hum hase ho, mazaak kiya ho, ya kisi difficult time se guzre ho,
har memory mere liye special hai.
<br><br>

Main bas itna chahta hu ki tu hamesha khush rahe, smile karti rahe aur jo bhi sapne dekhe hain wo sab pure ho.
<br><br>

Thank you for being such an amazing best friend. ❤️
<br><br>

Once again, Happy Birthday Mithi! 🎉✨
</p>

</div>

</div>

<script>
function showMessage(){
document.getElementById("message").style.display="block";
}

for(let i=0;i<25;i++){
let heart=document.createElement("div");
heart.innerHTML="🤍";
heart.className="heart";
heart.style.left=Math.random()*100+"vw";
heart.style.fontSize=(Math.random()*20+15)+"px";
heart.style.animationDuration=(Math.random()*5+5)+"s";
document.body.appendChild(heart);
}
</script>

</body>
</html>
