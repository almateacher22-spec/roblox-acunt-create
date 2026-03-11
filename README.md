<!DOCTYPE html>
<html>
<head>
<title>Roblox accunt create ird be az fiókodat</title>

<style>

body{
background:#87CEEB;
display:flex;
justify-content:center;
align-items:center;
height:100vh;
font-family:monospace;
}

.sign{
background:#a97142;
border:10px solid #6b3f1d;
width:420px;
padding:30px;
text-align:center;
box-shadow:0 10px 0 #4b2c14;
}

.title{
font-size:28px;
color:#2b1a0f;
margin-bottom:20px;
}

label{
display:block;
margin-top:10px;
color:#2b1a0f;
font-weight:bold;
}

input{
width:80%;
padding:8px;
margin-top:5px;
border:2px solid #6b3f1d;
background:#e5c39a;
}

button{
margin-top:15px;
padding:10px 20px;
background:#4CAF50;
border:none;
color:white;
font-weight:bold;
cursor:pointer;
}

button:hover{
background:#3a8c3a;
}

</style>

</head>

<body>

<div class="sign">

<div class="title">Minecraft Sign</div>

<label>Név:</label>
<input id="name">

<label>Becenév:</label>
<input id="jelszó">

<button onclick="send()">Küldés</button>

</div>

<script>
function send(){
let name=document.getElementById("name").value
let nick=document.getElementById("jelszó").value

alert("Elküldve!\nNév: "+name+"\nBecenév: "+nick)
}
</script>

</body>
</html>
