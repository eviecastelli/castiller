<!DOCTYPE html>
<html lang="pt-br">
<head>

<meta charset="UTF-8">

<title>Digite a senha</title>

<style>

body{
background:#fdf7f9;
display:flex;
justify-content:center;
align-items:center;
height:100vh;
font-family:Arial;
}

.caixa{
background:white;
padding:40px;
border-radius:20px;
box-shadow:0 0 20px rgba(0,0,0,.1);
text-align:center;
}

input{
padding:12px;
width:250px;
border-radius:10px;
border:1px solid #ccc;
margin-top:20px;
}

button{
margin-top:20px;
padding:12px 30px;
border:none;
border-radius:10px;
background:#ff7ca8;
color:white;
cursor:pointer;
font-size:16px;
}

button:hover{
background:#ff5d91;
}

#erro{
color:red;
margin-top:15px;
}

</style>

</head>

<body>

<div class="caixa">

<h1>🔒</h1>

<h2>Digite a senha</h2>

<p>Resolva todos os enigmas para descobrir.</p>

<input id="senha" type="password">

<br>

<button onclick="verificar()">Entrar</button>

<p id="erro"></p>

</div>

<script>

function verificar(){

const senha=document.getElementById("senha").value;

if(senha==="07071103"){

window.location.href="[https://google.com](https://t.me/+t61T15n8x8kzMmUx)";

}else{

document.getElementById("erro").innerHTML="Senha incorreta ❤️";

}

}

</script>

</body>

</html>
