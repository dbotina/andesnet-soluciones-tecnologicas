<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AndesNet Soluciones Tecnológicas</title>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
<style>
/* RESET */
* {margin:0; padding:0; box-sizing:border-box; font-family:'Roboto', sans-serif;}
body {background:#0f172a; color:white; scroll-behavior:smooth; overflow-x:hidden;}
a {text-decoration:none; color:white;}
img {max-width:100%; display:block;}

/* HERO PARALLAX */
.hero {
  height:100vh;
  background:url('img/camioneta.png') center/cover no-repeat fixed;
  position:relative;
  display:flex; align-items:center; justify-content:center; text-align:center;
  overflow:hidden;
}
.overlay {background: rgba(0,0,0,0.6); position:absolute; width:100%; height:100%; top:0; left:0;}
.hero-content {position:relative; z-index:2; animation: fadeIn 2s ease;}
.logo {width:180px; margin-bottom:20px; animation: slideDown 2s ease;}
h1 {font-size:48px; color:#38bdf8; letter-spacing:2px; opacity:0; animation: fadeIn 2s 0.5s forwards;}
.subtitle {margin-top:10px; font-size:20px; opacity:0.9; animation: fadeIn 2s 1s forwards;}

/* ANIMACIONES */
@keyframes fadeIn {from {opacity:0;} to {opacity:1;}}
@keyframes slideDown {from {transform:translateY(-50px);opacity:0;} to {transform:translateY(0);opacity:1;}}

/* SECCIONES */
.section {padding:80px 20px; text-align:center; position:relative; background-attachment: fixed; background-size: cover;}
.container {max-width:1000px; margin:auto;}
.card {background:#1e293b; padding:40px; border-radius:20px; margin-top:30px; box-shadow:0 0 30px rgba(0,0,0,0.5); opacity:0; transform:translateY(50px);}
.card.active {opacity:1; transform:translateY(0); transition:all 0.8s ease;}
.card h2 {color:#38bdf8; margin-bottom:20px;}
.card h3 {color:#facc15; margin-bottom:15px;}
.card p {line-height:1.6; margin-bottom:15px;}

/* TOOLTIP */
.tooltip {position:relative; cursor:pointer; color:#38bdf8;}
.tooltip:hover::after {
  content: attr(data-tip);
  position:absolute;
  bottom:100%; left:50%; transform:translateX(-50%);
  background:#111827; color:white; padding:8px 12px; border-radius:10px; white-space:nowrap; font-size:14px;
  opacity:1; transition:0.3s;
}
.tooltip::after {opacity:0; pointer-events:none;}

/* BOTÓN WHATSAPP FLOTANTE */
.whatsapp-fixed {position:fixed; bottom:30px; right:30px; background:#25D366; color:white; padding:15px 20px; border-radius:50px; font-weight:bold; box-shadow:0 0 20px rgba(0,0,0,0.5); transition:0.3s; z-index:10;}
.whatsapp-fixed:hover {transform:scale(1.1);}

/* QR */
.qr-box {margin-top:30px; background:white; padding:25px; display:inline-block; border-radius:20px; box-shadow:0 0 20px rgba(0,0,0,0.3);}
.qr-box img {width:250px; height:250px;}

/* SLIDER Y MINIATURAS */
.slider {position:relative; max-width:800px; margin:50px auto; overflow:hidden; border-radius:20px; box-shadow:0 0 30px rgba(0,0,0,0.5);}
.slides {display:flex; width:400%; animation: slide 16s infinite;}
.slides img {width:100%; border-radius:20px; transition: transform 0.5s ease;}
.slides img:hover {transform: scale(1.05);}
@keyframes slide {
  0% {transform:translateX(0);}
  20% {transform:translateX(0);}
  25% {transform:translateX(-100%);}
  45% {transform:translateX(-100%);}
  50% {transform:translateX(-200%);}
  70% {transform:translateX(-200%);}
  75% {transform:translateX(-300%);}
  95% {transform:translateX(-300%);}
  100% {transform:translateX(0);}
}

/* HOVER SOBRE CAMIONETA */
.hero:hover {filter: brightness(1.1) saturate(1.2); transition:all 0.6s ease;}

/* MODAL */
.modal {display:none; position:fixed; z-index:20; left:0; top:0; width:100%; height:100%; overflow:auto; background:rgba(0,0,0,0.9);}
.modal-content {background:#1e293b; margin:10% auto; padding:30px; border-radius:20px; width:80%; max-width:500px; position:relative; color:white;}
.close {position:absolute; top:15px; right:20px; font-size:28px; font-weight:bold; cursor:pointer; color:#f87171;}

/* FOOTER */
footer {background:#111827; padding:30px; text-align:center; font-size:14px; color:#cbd5e1;}

/* RESPONSIVE */
@media(max-width:768px){
  h1 {font-size:36px;}
  .subtitle {font-size:16px;}
}
</style>
</head>

<body>

<!-- HERO -->
<section class="hero">
<div class="overlay"></div>
<div class="hero-content">
<img src="img/logo.png" alt="AndesNet Logo" class="logo">
<h1>ANDESNET</h1>
<div class="subtitle">
Soluciones Tecnológicas<br>Pasto - Colombia | Infraestructura Digital & Telecomunicaciones
</div>
</div>
</section>

<!-- PERFIL -->
<section class="section" style="background:url('img/fondo_estudio.jpg') center/cover no-repeat fixed;">
<div class="container">
<div class="card" data-scroll>
<h2>Perfil Profesional</h2>
<h3>Felipe Botina</h3>
<p>
🎓 Estudiante de Ingeniería de Sistemas<br>
📡 Técnico en Telecomunicaciones<br>
⚡ Electricidad y Electrónica Básica<br>
🔧 Auxiliar de empalmería<br>
🏭 Mecánica Industrial
</p>
<p>
Experiencia práctica en instalación, aprovisionamiento, mantenimiento y optimización de redes de telecomunicaciones, infraestructura digital y soporte técnico especializado.
</p>
<a href="https://wa.me/573046338016?text=Hola%20Felipe%20Botina%20vi%20tu%20página%20web%20AndesNet%20y%20deseo%20información" 
target="_blank" class="whatsapp-fixed">📲 WhatsApp</a>
</div>
</div>
</section>

<!-- SERVICIOS CON MODAL -->
<section class="section" style="background:#111827;">
<div class="container">
<div class="card" data-scroll>
<h2>Servicios Especializados</h2>
<ul style="list-style:none; padding-left:0;">
<li>✔ <span class="tooltip modal-btn" data-tip="Instalación de HFC y fibra óptica FTTH" data-modal="modal1">Redes HFC / FTTH</span></li>
<li>✔ <span class="tooltip modal-btn" data-tip="Configuración y aprovisionamiento de equipos MTA y ONT" data-modal="modal2">Equipos MTA / ONT</span></li>
<li>✔ <span class="tooltip modal-btn" data-tip="Optimización de WiFi 2.4GHz y 5GHz" data-modal="modal3">WiFi Optimizado</span></li>
<li>✔ <span class="tooltip modal-btn" data-tip="Soporte de infraestructura interna de servidores" data-modal="modal4">Infraestructura de servidores</span></li>
<li>✔ <span class="tooltip modal-btn" data-tip="Auxiliar de empalmería y soporte técnico en campo" data-modal="modal5">Auxiliar de empalmería</span></li>
</ul>
</div>
</div>
</section>

<!-- SLIDER DE PROYECTOS Y VIDEOS -->
<section class="section" style="background:#0f172a;">
<div class="container">
<h2 style="color:#38bdf8;">Proyectos y Equipos</h2>
<div class="slider">
<div class="slides">
<img src="img/logo.png" alt="Logo AndesNet">
<img src="img/camioneta.png" alt="Camioneta AndesNet">
<img src="img/deco1.png" alt="Equipo MTA">
<img src="img/deco2.png" alt="Equipo ONT">
<video src="img/video1.mp4" autoplay muted loop></video>
<video src="img/video2.mp4" autoplay muted loop></video>
</div>
</div>
</div>
</section>

<!-- CÓDIGO QR -->
<section class="section">
<div class="container">
<h2 style="color:#38bdf8;">Código QR Oficial</h2>
<div class="qr-box">
<img src="https://api.qrserver.com/v1/create-qr-code/?size=250x250&data=https://dbotina.github.io/andesnet-soluciones-tecnologicas/" alt="QR AndesNet">
<p style="color:black; font-weight:bold; margin-top:10px;">
Escanea para visitar nuestra página oficial
</p>
</div>
</div>
</section>

<footer>
© 2026 AndesNet Soluciones Tecnológicas | Pasto - Colombia
</footer>

<!-- MODALS -->
<div id="modal1" class="modal">
<div class="modal-content">
<span class="close">&times;</span>
<h3>Redes HFC / FTTH</h3>
<p>Instalación, mantenimiento y optimización de redes HFC y fibra óptica FTTH.</p>
</div>
</div>

<div id="modal2" class="modal">
<div class="modal-content">
<span class="close">&times;</span>
<h3>Equipos MTA / ONT</h3>
<p>Configuración, aprovisionamiento y soporte de equipos de usuario final.</p>
</div>
</div>

<div id="modal3" class="modal">
<div class="modal-content">
<span class="close">&times;</span>
<h3>WiFi Optimizado</h3>
<p>Optimización de redes WiFi 2.4GHz y 5GHz para rendimiento estable y velocidad máxima.</p>
</div>
</div>

<div id="modal4" class="modal">
<div class="modal-content">
<span class="close">&times;</span>
<h3>Infraestructura de servidores</h3>
<p>Gestión y soporte de infraestructura de servidores y redes internas.</p>
</div>
</div>

<div id="modal5" class="modal">
<div class="modal-content">
<span class="close">&times;</span>
<h3>Auxiliar de empalmería</h3>
<p>Soporte en empalmería y tareas de campo en redes de telecomunicaciones.</p>
</div>
</div>

<script>
// Animación scroll
const cards = document.querySelectorAll('[data-scroll]');
window.addEventListener('scroll', () => {
  const triggerBottom = window.innerHeight * 0.85;
  cards.forEach(card => {
    const cardTop = card.getBoundingClientRect().top;
    if(cardTop < triggerBottom){
      card.classList.add('active');
    }
  });
});

// MODAL
const modalBtns = document.querySelectorAll('.modal-btn');
modalBtns.forEach(btn => {
  btn.addEventListener('click', () => {
    const modal = document.getElementById(btn.dataset.modal);
    modal.style.display = "block";
  });
});
const closeBtns = document.querySelectorAll('.close');
closeBtns.forEach(btn => {
  btn.addEventListener('click', () => {
    btn.parentElement.parentElement.style.display = "none";
  });
});
window.addEventListener('click', e => {
  if(e.target.classList.contains('modal')) e.target.style.display = "none";
});
</script>
</body>
</html>
