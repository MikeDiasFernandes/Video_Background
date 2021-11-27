# Video_Background
Página com vídeo background


Pode ser colocado um vídeo nativo da unidade ou linkar á um externo




<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="_javascript/javascript.js"></script>
    <link rel="stylesheet" href="_css/Página_inicial.css">
    <title>Silverpox Pisos</title>

</head>

<body>
 <section class="showcase">
 <header>
<h2 class="logo"> silverpox</h2>
<div class="toggle"></div>
 </header>

 <video src="_media/man_bussiness.mp4" muted loop autoplay></video>
 
 <div class="overlay"></div>

 <div class="text">
     <h2> a Solucão</h2>
     <h3> em restaurações e acabamentos</h3>
     <p> Especializados em análise de estruturas e acabamentos para o seu negócio. Conte com a maior equipe em restaurações de substratos e revestimentos especiais</p>
          <a href="#">saiba mais</a>
 </div>

 <ul class="social">
<li><a href="#"><img src="_imagens/whatsapp.png" height="50px" alt="whatsapp"/></a></li>
<li><a href="#"><img src="_imagens/instagram.png" height="50px" alt="instagram"/></a></li>
<li><a href="#"><img src="_imagens/facebook.png" height="50px" alt=""/></a></li>


 </ul>
 
</section>

<div class="menu">
<ul>
    <li><a href="Quem_somos.html" onclick="Quem_somos()">Quem Somos</a></li>
    <li><a href="#" onclick="Noticias()">Notícias</a></li>
    <li><a href="#" onclick="Obras()">Obras</a></li>
    <li><a href="#" onclick="Parcerias()">Parcerias</a></li>
    <li><a href="#" onclick="Fale_conosco()">Fale Conosco</a></li>

</ul>

</div>

<script>
var menuToggle = document.querySelector('.toggle')
var showcase = document.querySelector('.showcase')

menuToggle.addEventListener('click', () => {
    menuToggle.classList.toggle('active')
    showcase.classList.toggle('active')
})
</script>

</body>

</html>
