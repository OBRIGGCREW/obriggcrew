ØB-Rigg-Crew/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    ├── hero.jpg
    ├── crew.jpg
    └── logo.png
<!DOCTYPE html>
<html lang="no">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ØB Rigg & Crew</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#f7f9fb;
color:#222;
}

header{
height:100vh;
background:
linear-gradient(rgba(0,0,0,.65),rgba(0,0,0,.65)),
url("https://images.unsplash.com/photo-1504307651254-35680f356dfd?auto=format&fit=crop&w=1600&q=80");
background-size:cover;
background-position:center;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
}

.hero{
max-width:800px;
color:white;
}

.hero h1{
font-size:60px;
margin-bottom:20px;
}

.hero p{
font-size:22px;
margin-bottom:35px;
}

.buttons{
display:flex;
gap:20px;
justify-content:center;
flex-wrap:wrap;
}

.btn{
background:#0d6efd;
padding:16px 32px;
border-radius:50px;
text-decoration:none;
font-weight:600;
color:white;
transition:.3s;
}

.btn:hover{
background:#0b5ed7;
transform:translateY(-3px);
}

.btn2{
background:white;
color:#111;
}

section{
padding:90px 10%;
}

.title{
text-align:center;
font-size:40px;
margin-bottom:50px;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:white;
padding:35px;
border-radius:18px;
box-shadow:0 10px 25px rgba(0,0,0,.08);
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
}

.card h3{
margin-bottom:15px;
color:#0d6efd;
}

.about{
display:grid;
grid-template-columns:1fr 1fr;
gap:60px;
align-items:center;
}

.about img{
width:100%;
border-radius:20px;
}

.checklist{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:18px;
margin-top:35px;
}

.check{
background:white;
padding:20px;
border-radius:12px;
font-weight:600;
box-shadow:0 5px 15px rgba(0,0,0,.08);
}

.contact{
background:#0f172a;
color:white;
}

.contact-grid{
display:grid;
grid-template-columns:1fr 1fr;
gap:50px;
}

form{
display:flex;
flex-direction:column;
gap:15px;
}

input,textarea{
padding:15px;
border:none;
border-radius:10px;
font-size:16px;
}

textarea{
height:150px;
resize:none;
}

button{
padding:15px;
border:none;
background:#0d6efd;
color:white;
font-size:17px;
border-radius:10px;
cursor:pointer;
}

button:hover{
background:#0b5ed7;
}

footer{
background:#09111f;
color:white;
text-align:center;
padding:30px;
}

@media(max-width:900px){

.hero h1{
font-size:42px;
}

.about,
.contact-grid{
grid-template-columns:1fr;
}

}

</style>

</head>

<body>

<header>

<div class="hero">

<h1>ØB Rigg & Crew</h1>

<p>Ekstra muskler når bedriften din trenger det.</p>

<div class="buttons">

<a href="#kontakt" class="btn">Kontakt oss</a>

<a href="#tjenester" class="btn btn2">Våre tjenester</a>

</div>

</div>

</header>

<section id="tjenester">

<h2 class="title">Våre tjenester</h2>

<div class="cards">

<div class="card">
<h3>Bemanning</h3>
<p>Ekstra arbeidskraft når bedriften trenger flere hender.</p>
</div>

<div class="card">
<h3>Rigg og nedrigg</h3>
<p>Montering, demontering og praktisk hjelp før og etter oppdrag.</p>
</div>

<div class="card">
<h3>Lager og logistikk</h3>
<p>Pakking, flytting, sortering og effektiv lagerhjelp.</p>
</div>

<div class="card">
<h3>Generelt arbeid</h3>
<p>Vi hjelper til med fysisk arbeid der det trengs.</p>
</div>

</div>

</section>

<section>

<h2 class="title">Hvorfor velge oss?</h2>

<div class="checklist">

<div class="check">✔ Rask responstid</div>

<div class="check">✔ Fleksibel bemanning</div>

<div class="check">✔ Pålitelige medarbeidere</div>

<div class="check">✔ Profesjonell service</div>

<div class="check">✔ Konkurransedyktige priser</div>

<div class="check">✔ Tilpasset deres behov</div>

</div>

</section>

<section>

<div class="about">

<div>

<h2 style="font-size:40px;margin-bottom:20px;">
Om ØB Rigg & Crew
</h2>

<p style="line-height:1.9;font-size:18px;">

ØB Rigg & Crew hjelper bedrifter som trenger ekstra arbeidskraft til små og store oppdrag. Vi leverer motiverte medarbeidere som møter opp, jobber effektivt og bidrar til at prosjektet blir gjennomført på en trygg og profesjonell måte.

</p>

</div>

<img src="https://images.unsplash.com/photo-1541888946425-d81bb19240f5?auto=format&fit=crop&w=900&q=80">

</div>

</section>

<section id="kontakt" class="contact">

<h2 class="title">Kontakt oss</h2>

<div class="contact-grid">

<div>

<h3>Har du behov for ekstra bemanning?</h3>

<br>

<p>Ta kontakt med oss, så finner vi en løsning som passer din bedrift.</p>

<br><br>

<p>📞 Telefon: +47 XX XX XX XX</p>

<br>

<p>✉️ post@obriggcrew.no</p>

<br>

<p>📍 Norge</p>

</div>

<form>

<input type="text" placeholder="Navn">

<input type="text" placeholder="Bedrift">

<input type="email" placeholder="E-post">

<input type="tel" placeholder="Telefon">

<textarea placeholder="Hva trenger dere hjelp med?"></textarea>

<button>Send forespørsel</button>

</form>

</div>

</section>

<footer>

<h3>ØB Rigg & Crew</h3>

<p>Ekstra arbeidskraft når du trenger det.</p>

<br>

<p>© 2026 ØB Rigg & Crew. Alle rettigheter reservert.</p>

</footer>

</body>
</html>