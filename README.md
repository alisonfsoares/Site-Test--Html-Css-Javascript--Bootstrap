# Site-Test--Html-Css-Javascript--Bootstrap

<!DOCTYPE html>
<body style="background-color:#F2F2F2;">

<html>

<head>
<title>Biblioteca Central</title>
</head>

<style>

img {
    border-radius: 8px;
    height: auto
}
div {
    border: 1px solid black;
    margin-top: 100px;
    margin-bottom: 100px;
    margin-right: 150px;
    margin-left: 80px;
    background-color: lightblue;
}
ul   {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
    position: fixed;
    top: 0;
    width: 100%;
}

li {
    float: left;
}

li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 28px;
    text-decoration: none;
}

li a:hover {
    background-color: grey;
    font-family: verdana
}
h1 {
    color: black;
    font-family: verdana;
    font-size: 200%;

}
h3 {
    color: black;
    font-family: verdana;
    font-size: 100%;

}
p  {
    color: black;
    font-family: verdana;
    font-size: 100%;
}
.active {
    background-color: grey;
}
</style>


<body>
<center><img src="biblioteca.jpg"  style="width:1180px;height:240px;border:0">
<hr>
<ul>
  <li><a href="#inicio"> Inicio </a></li>
  <li><a href="#Lançamentos"> Lançamentos </a></li>
  <li><a href="#cotegorias"> Categorias </a></li>
  <li><a href="#contato"> Contato (31) 9 9407-6743 </a></li>
  <li style="float:right"><a class="active" href="#help">Seja um colaborador</a></li>
</ul>



<h1  style="text-align:center;"><strong>Escolha seu livro e baixe gratuitamente!</strong></h1>
<h3 style="text-align:center;">
Um dos maiores sites brasileiros com livros gratuitos em domínio público ou livros<br>
autorizados para distribuição gratuita pelos próprios autores -
com Dezenas de Milhares de Assinantes!</h3>
<img src="gato.gif"  style="width:620px;height:320px;border:0">

<hr>

</center>
<h1><center>Destaques da Semana</center></h1>
<div class="livraria">
<h3>Steve Jobs - Livro por Walter Isaacson</h3>
<p>Conheça a história do homem que pôs o futuro nas palmas das suas mãos. <br>A biografia autorizada de Steve Jobs, a única escrita em colaboração com o próprio.</p>
</div> 

<div class="livraria">
<h3>O X da questão: A trajetória do maior empreendedor do Brasil - Livro por Eike Batista</h2>
<p>Em 'O X da questão', o empreendedor brasileiro Eike Batista narra suas aventuras desde os maiores sucessos até as experiências que não deram certo e os erros cometidos.</p>
</div>

<div class="livraria">
<h3>Bill Gates - Magnata</h3>
<p>William Henry Gates III mais conhecido como Bill Gates, é um magnata, filantropo e autor norte-americano, que ficou conhecido por fundar junto com Paul Allen a Microsoft, a maior e mais conhecida empresa.</p>
</div>

<center>
<button type="button"
onclick="document.getElementById('demo').innerHTML = Date()">
Clique aqui para ter acesso a data e a hora neste exato momento.</button>
<p id="demo"></p>
</center>
</body>


</html>
