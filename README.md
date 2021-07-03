- 👋 Hi, I’m @wWiseZ
   Estudante de DS 

<!---
wWiseZ/wWiseZ is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<html>
 <head>
 <title>Cadastro Html</title>
 <meta http-equiv="Content-Type" content="text/html" charset="utf-8">
 <link rel="stylesheet" href="style.css">
 </head>
 <style type="text/css">
 
 *{
 heigth:100%;
 }
 
 
 @keyframes colors{
  0%{
  background-position: 0% 50%;
  
  }
  50%{
   background-position: 50% 100%;
  }
  100%{
  background-position: 0% 50%;
  }
 }

 
 body{
  background: linear-gradient(-45deg,DarkOrange,Gold,blue,RoyalBlue);
  background-attachment: fixed;
  background-size: 300% 300%;
  animation: colors 10s ease infinite;
  animation-delay:0s;
  }
  
  .imagem{

  width: 500px;
  heigth: 500px;
  }
  
  
  .titulo{
  width: 800px;
  background-color: Rgb(0,0,0,0.6);
  margin: auto;
  color: DarkOrange;
  padding: 10px, 0px,10px, 0px;
  text-alingt: center;
  border-radius: 15px, 15px, 0px, 0px;
  box-shadow: inset 0 0 1en black, 0 0 1en DarkOrange;

  
  }
 
 lable{
  display: inline-block
  width: 95px;
 }
 
 form{
 background-color: rgb(0,0,0,0.6);
 max-width: 400px;
 width: 60%;
 padding: 10%;
 position: absolute;
 left: 50%;
 top: 59%;
 transform: translate(-50%,-50%);
 border-radius: 50px;
  width: 500px;
  heigth: 500px;

 }

 form input[type=text],
 form input[type=password],
 form input[type=email]{
 width: 100%;
 heigth:45px ;
 border:1px solid #ccc  ;
 padding-left:10px 0 ;
 margin:10px ; 
 }
 form h1{
 font-weight: 600;
 margin-bottom: 2rem;
 position: relative;
 
 }
 

 
 
 form input[type=submit]{
 width: 100%;
 heigth:40px ;
 cursor:pointer ;
 background:orange ;
 color: white;
 border:0 ;
 border-radius: 20px;
 transition:1s ; 
 }
  
  
 form input[type=reset]{
 width: 100%;
 heigth:40px ;
 cursor:pointer ;
 background:orange ;
 color: white;
 border:0 ;
 border-radius: 20px;
 transition:1s ; 
 
 
 }
 
 
 </style>
 
 <body>
 

 
 <div Class="titulo">
 <center> <h1>BEM VINDO AO NOSSO CADASTRO</h1> </center>
 </div>
 
 
 
 <div class="imagem">
 <img src="https://img.icons8.com/ios/452/crunchyroll.png">
 </div>
 
 
 <form>
 
 <font color="DarkOrange">
 <h1> Cadastro Crunchyroll</h1>
 <br>
 <br>
 <p><label for="nasc"></label> Data de Nascimento <input type="Date" name="nasc" id="nasc" >
 <p><label for="name"></label><input name="nome" id="name" type="text" placeholder="Digite seu nome ">
 <p> <label for="email"> </label><input name="email" id="email" type="email" placeholder="Digite o Email">
 <p> <label for="senha"></label><input name="senha" id="senha" type="password" placeholder="Digite sua Senha">
 <p> <label for="senha"></label><input name="senha" id="name" type="password" placeholder="Confirme sua Senha">
 <p> <label for="apelido"> </label><input name="apelido" id="apelido" type="text" placeholder=" Escolha Um Apelido">
 <p><label for="genero">Escolha Um desses Gêneros de Animes </label>
 <br>
 <br>
 <p><label for="genero">Shounen</label><input name="genero" type="radio"> 
 <p><label for="genero"> Isekai<input name="genero" type="radio">
 <p><label for="genero"> Shoujou<input name="genero"  type="radio">
 <p><label for="genero"> Seinen<input name="genero" type="radio">
 <p><label for="genero"> Vida Escolar<input name="genero" type="radio">
 <p> <label for="imagem"> Foto </label><input name="imagem" id="imagem" type="file">
 <br>
 <br>
 <br>
 <input type="submit">
 <br>
 <br>
 <input type="reset">
 <br>
 <br>
 <font color="white">
 <h6>Criado Por Marquinhos </h6>
 <h6> Um oferecimento </h6>
 <h5> Crunchyroll </h5>
 </font>
 
 </form>
 </div>
 </div>
 
 
 
 

 </body>
 </html>
