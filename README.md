<!DOCTYPE html>
<html lang="fr">

<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Prof Marwan Rouissi | Mathématiques 2BAC</title>

    <link rel="stylesheet" href="style.css">

</head>
<style>

    /* ======================================= */
/* RESET */
/* ======================================= */

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

/* ======================================= */
/* BODY */
/* ======================================= */

body{

    font-family:Arial, Helvetica, sans-serif;

    background:#f5f5f5;

    color:#222;

}

/* ======================================= */
/* HEADER */
/* ======================================= */

header{

    background:linear-gradient(90deg,#b30000,#ff0000);

    display:flex;

    align-items:center;

    justify-content:center;

    padding:20px 40px;

    box-shadow:0 5px 15px rgba(0,0,0,.3);

}

.logo img{

    width:100px;

    height:100px;

    border-radius:50%;

    border:4px solid white;

    margin-right:25px;

}

.title{

    text-align:center;

}

.title h1{

    color:white;

    font-size:48px;

    letter-spacing:3px;

    text-transform:uppercase;

}

.title p{

    color:white;

    margin-top:10px;

    font-size:22px;

}

/* ======================================= */
/* MENU */
/* ======================================= */

nav{

    background:white;

    padding:18px;

    box-shadow:0 3px 10px rgba(0,0,0,.2);

}

nav ul{

    list-style:none;

    display:flex;

    justify-content:center;

    gap:40px;

}

nav a{

    text-decoration:none;

    color:#b30000;

    font-size:20px;

    font-weight:bold;

    transition:.3s;

}

nav a:hover{

    color:black;

    border-bottom:3px solid red;

    padding-bottom:8px;

}

/* ======================================= */
/* HERO */
/* ======================================= */

section:first-of-type{

    width:90%;

    margin:50px auto;

    text-align:center;

    background:white;

    padding:70px;

    border-radius:20px;

    box-shadow:0 10px 30px rgba(0,0,0,.2);

}

section:first-of-type h2{

    color:#b30000;

    font-size:45px;

    margin-bottom:25px;

}

section:first-of-type p{

    font-size:22px;

    line-height:40px;

    color:#555;

}

/* ======================================= */
/* BUTTON */
/* ======================================= */

.btn{

    display:inline-block;

    margin-top:35px;

    background:#b30000;

    color:white;

    text-decoration:none;

    padding:18px 40px;

    border-radius:10px;

    font-size:20px;

    transition:.3s;

}

.btn:hover{

    background:black;

    transform:scale(1.05);

}
/* ======================================= */
/* SECTIONS */
/* ======================================= */

section{

    width:90%;

    margin:40px auto;

}

/* ======================================= */
/* TITRES DES SECTIONS */
/* ======================================= */

section h2{

    color:#b30000;

    text-align:center;

    font-size:36px;

    margin-bottom:30px;

}

/* ======================================= */
/* CARDS */
/* ======================================= */

.services{

    display:flex;

    justify-content:space-between;

    flex-wrap:wrap;

    gap:25px;

}

.card{

    background:white;

    width:31%;

    border-radius:20px;

    padding:30px;

    box-shadow:0 8px 20px rgba(0,0,0,.15);

    transition:.4s;

    cursor:pointer;

}

.card:hover{

    transform:translateY(-12px);

    box-shadow:0 15px 30px rgba(0,0,0,.3);

}

.card h2{

    color:#c00000;

    margin-bottom:20px;

}

.card p{

    font-size:18px;

    line-height:30px;

}

/* ======================================= */
/* LISTES */
/* ======================================= */

section ul{

    background:white;

    border-radius:20px;

    padding:30px;

    box-shadow:0 8px 20px rgba(0,0,0,.15);

}

section li{

    font-size:20px;

    padding:15px;

    border-bottom:1px solid #ddd;

    transition:.3s;

}

section li:hover{

    background:#ffecec;

    color:#b30000;

    padding-left:25px;

}

/* ======================================= */
/* CONTACT */
/* ======================================= */

.contact{

    background:white;

    border-radius:20px;

    padding:40px;

    box-shadow:0 8px 20px rgba(0,0,0,.15);

}

.contact p{

    font-size:20px;

    margin:15px 0;

}

/* ======================================= */
/* FOOTER */
/* ======================================= */

footer{

    background:#b30000;

    color:white;

    text-align:center;

    padding:30px;

    margin-top:60px;

    font-size:18px;

}

footer p{

    letter-spacing:1px;

}

/* ======================================= */
/* RESPONSIVE */
/* ======================================= */

@media(max-width:900px){

header{

flex-direction:column;

}

.logo{

margin-bottom:20px;

}

nav ul{

flex-direction:column;

gap:20px;

}

.services{

flex-direction:column;

}

.card{

width:100%;

}

section:first-of-type{

padding:40px;

}

section:first-of-type h2{

font-size:35px;

}

}

/* ======================================= */
/* HERO IMAGE */
/* ======================================= */

.hero{

    background:linear-gradient(rgba(179,0,0,.75),rgba(179,0,0,.75)),
    url("Image/background.jpg");

    background-size:cover;

    background-position:center;

    background-repeat:no-repeat;

    color:white;

    min-height:500px;

    display:flex;

    flex-direction:column;

    justify-content:center;

    align-items:center;

    border-radius:20px;

}

.hero h2{

    color:white;

    font-size:55px;

}

.hero p{

    color:white;

    width:70%;

    text-align:center;

    font-size:23px;

}

/* ======================================= */
/* ANIMATION */
/* ======================================= */

@keyframes fadeIn{

0%{

opacity:0;

transform:translateY(40px);

}

100%{

opacity:1;

transform:translateY(0);

}

}

.hero{

animation:fadeIn 1.5s;

}

.card{

animation:fadeIn 1.5s;

}

/* ======================================= */
/* BUTTON EFFECT */
/* ======================================= */

.btn{

box-shadow:0 8px 20px rgba(0,0,0,.4);

}

.btn:hover{

box-shadow:0 15px 35px rgba(0,0,0,.6);

}

/* ======================================= */
/* SCROLL BAR */
/* ======================================= */

::-webkit-scrollbar{

width:12px;

}

::-webkit-scrollbar-track{

background:white;

}

::-webkit-scrollbar-thumb{

background:#b30000;

border-radius:20px;

}

::-webkit-scrollbar-thumb:hover{

background:#800000;

}

/* ======================================= */
/* LOGO EFFECT */
/* ======================================= */

.logo img{

transition:.5s;

}

.logo img:hover{

transform:rotate(360deg) scale(1.1);

}

/* ======================================= */
/* NAVBAR STICKY */
/* ======================================= */

nav{

position:sticky;

top:0;

z-index:999;

}

/* ======================================= */
/* TITLE EFFECT */
/* ======================================= */

.title h1{

text-shadow:3px 3px 10px rgba(0,0,0,.4);

}

/* ======================================= */
/* SECTION EFFECT */
/* ======================================= */

section{

animation:fadeIn 1s;

}

/* ======================================= */
/* FOOTER EFFECT */
/* ======================================= */

footer{

box-shadow:0 -5px 20px rgba(0,0,0,.3);

}

/* ======================================= */
/* IMAGE HOVER */
/* ======================================= */

img{

transition:.4s;

}

img:hover{

transform:scale(1.03);

}
/* ======================================= */
/* PREMIUM CARDS */
/* ======================================= */

.card{

    overflow:hidden;

    position:relative;

}

.card::before{

    content:"";

    position:absolute;

    top:0;

    left:-100%;

    width:100%;

    height:5px;

    background:#ff0000;

    transition:.5s;

}

.card:hover::before{

    left:0;

}

/* ======================================= */
/* GLASS EFFECT */
/* ======================================= */

.hero{

    backdrop-filter:blur(8px);

}

/* ======================================= */
/* SECTION TITLE */
/* ======================================= */

section h2{

    position:relative;

    padding-bottom:15px;

}

section h2::after{

    content:"";

    position:absolute;

    left:50%;

    transform:translateX(-50%);

    bottom:0;

    width:120px;

    height:4px;

    background:#c00000;

    border-radius:20px;

}

/* ======================================= */
/* BUTTON */
/* ======================================= */

.btn{

    font-weight:bold;

    letter-spacing:1px;

}

.btn:hover{

    transform:translateY(-5px);

}

/* ======================================= */
/* LIST STYLE */
/* ======================================= */

section ul{

    list-style:none;

}

section li{

    border-left:6px solid #c00000;

    margin:15px 0;

    background:white;

    border-radius:8px;

}

section li:hover{

    background:#fff0f0;

}

/* ======================================= */
/* IMAGE EFFECT */
/* ======================================= */

img{

    max-width:100%;

}

/* ======================================= */
/* FOOTER */
/* ======================================= */

footer{

    font-weight:bold;

    letter-spacing:2px;

}

/* ======================================= */
/* HOVER LINKS */
/* ======================================= */

nav a{

    position:relative;

}

nav a::after{

    content:"";

    position:absolute;

    left:0;

    bottom:-6px;

    width:0;

    height:3px;

    background:#c00000;

    transition:.4s;

}

nav a:hover::after{

    width:100%;

}

/* ======================================= */
/* SMOOTH SCROLL */
/* ======================================= */

html{

    scroll-behavior:smooth;

}

/* ======================================= */
/* SELECTION COLOR */
/* ======================================= */

::selection{

    background:#c00000;

    color:white;

}

/* ===================================== */
/* SCROLL SMOOTH */
/* ===================================== */

html{
    scroll-behavior:smooth;
}

/* ===================================== */
/* SHADOW SUR TOUTES LES CARTES */
/* ===================================== */

.card{

    transition:0.4s;

}

.card:hover{

    transform:translateY(-12px) scale(1.03);

    box-shadow:0 20px 40px rgba(0,0,0,.35);

}

/* ===================================== */
/* HERO */
/* ===================================== */

.hero{

    border:3px solid white;

}

/* ===================================== */
/* TITRES */
/* ===================================== */


h1,h2,h3{

    text-transform:uppercase;

    letter-spacing:2px;
    


}

/* ===================================== */
/* IMAGE */
/* ===================================== */

img{

    transition:0.5s;

}

img:hover{

    transform:scale(1.08);

}

/* ===================================== */
/* BUTTON */
/* ===================================== */

.btn{

    box-shadow:0 10px 25px rgba(255,0,0,.4);

}

.btn:hover{

    background:#8b0000;

    box-shadow:0 15px 35px rgba(255,0,0,.7);

}

/* ===================================== */
/* MENU */
/* ===================================== */

nav{

    position:sticky;

    top:0;

}

nav a{

    transition:0.3s;

}

nav a:hover{

    color:red;

    transform:scale(1.1);

}

/* ===================================== */
/* FOOTER */
/* ===================================== */

footer{

    border-top:5px solid white;

}

/* ===================================== */
/* SCROLLBAR */
/* ===================================== */

::-webkit-scrollbar{

    width:12px;

}

::-webkit-scrollbar-thumb{

    background:red;

    border-radius:10px;

}

::-webkit-scrollbar-track{

    background:white;

}

/* ===================================== */
/* ANIMATION */
/* ===================================== */

@keyframes zoom{

0%{

transform:scale(.8);

opacity:0;

}

100%{

transform:scale(1);

opacity:1;

}

}

.hero{

animation:zoom 1s;

}

.card{

animation:zoom 1.3s;

}
</style>

<body>

    <!-- HEADER -->

    <header>

        <div class="logo">
            <img src="Image/photo.avif" alt="Logo">
        </div>

        <div class="title">
            <h1>PROF MARWAN ROUISSI</h1>
            <p>Mathématiques - 2ème Baccalauréat</p>
        </div>

    </header>

    <!-- MENU -->

    <nav>

        <ul>

            <li><a href="#">Accueil</a></li>

            <li><a href="#">Cours</a></li>

            <li><a href="#">Exercices</a></li>

            <li><a href="#">Examens</a></li>

            <li><a href="#">Vidéos</a></li>

            <li><a href="#">Contact</a></li>

        </ul>

    </nav>

    <!-- HERO -->

    <section>

        <h2>Bienvenue sur mon site</h2>

        <p>
            Ce site est dédié aux élèves de 2ème Baccalauréat.
            Vous trouverez des cours, des exercices corrigés,
            des examens nationaux et des vidéos de mathématiques.
        </p>

    </section>

    <!-- ANALYSE -->

    <section>

        <h2>📘 Semestre N°1 </h2>

        <h3> Les séries </h3>

        <ul>

<li><a href="Image/les limites Série 1.pdf" target="_blank">📘 Limites</a></li>

<li><a href="PDF/le_continuité.pdf" target="_blank">📗 Continuité</a></li>

<li><a href="PDF/Dérivation_et_étude_des_fonctions.pdf" target="_blank">📕 Dérivabilité</a></li>

<li><a href="PDF/fonctions_logarithme_ln_x_ (1).pdf" target="_blank">📙 Fonction logarithmique</a></li>

<li><a href="PDF/PRIMITIVE.pdf" target="_blank">📒 Primitive et calcul Intégrales</a></li>

<li><a href="PDF/Nombres_complexes__Partie_1_.pdf" target="_blank">📔 les nombres complexes</a></li>

</ul>



    </section>

   

    <!-- EXAMENS -->

    <section>

        <h2>📄 Examens Nationaux</h2>

        <ul>

            <li>National 2025</li>

            <li>National 2024</li>

            <li>National 2023</li>

            <li>National 2022</li>

        </ul>

    </section>

    <!-- VIDEOS -->

    <section>

        <h2>🎥 Vidéos</h2>

        <ul>

            <li>Analyse</li>

            <li>Algèbre</li>

            <li>Probabilités</li>

        </ul>

    </section>

    <!-- CONTACT -->

    <section>

        <h2>📞 Contact : +212 774692412</h2>

        <p>Email : prof@email.com</p>

        <p>WhatsApp : +212 774692412</p>

        <p>YouTube : Prof Marwan Rouissi</p>

    </section>

    <!-- FOOTER -->

    <footer>

        <p>© 2026 PROF MARWAN ROUISSI - Tous droits réservés.</p>

    </footer>

</body>

</html>
