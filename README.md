❤️ El AMOR DE DIOS Y MI FAMILIA ♨️♾️
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Felipe Botina | Tech API</title>

<style>

*{
    box-sizing:border-box;
}

body{
    margin:0;
    font-family:Inter,Segoe UI,Arial,sans-serif;
    background:#070b14;
    color:#e5e7eb;
}

/* =========================
   APP
========================= */

.app{
    max-width:1100px;
    min-height:100vh;
    margin:auto;
    display:flex;
    background:#0b1120;
}

/* =========================
   SIDEBAR
========================= */

.sidebar{
    width:230px;
    background:#090e1a;
    border-right:1px solid #1e293b;
    padding:25px 15px;
    position:sticky;
    top:0;
    height:100vh;
}

.logo{
    font-size:20px;
    font-weight:800;
    color:#38bdf8;
    margin-bottom:35px;
}

.logo span{
    color:#64748b;
    font-size:11px;
    display:block;
    margin-top:5px;
}

.menu button{
    width:100%;
    padding:13px;
    margin-bottom:8px;
    background:transparent;
    border:0;
    color:#94a3b8;
    text-align:left;
    border-radius:10px;
    cursor:pointer;
    font-size:14px;
}

.menu button:hover,
.menu button.active{
    background:#111c31;
    color:#38bdf8;
}

/* =========================
   MAIN
========================= */

.main{
    flex:1;
    padding:25px;
}

/* =========================
   TOP BAR
========================= */

.topbar{
    display:flex;
    justify-content:space-between;
    align-items:center;
    border-bottom:1px solid #1e293b;
    padding-bottom:18px;
    margin-bottom:25px;
}

.endpoint{
    color:#64748b;
    font-size:13px;
}

.status{
    color:#22c55e;
    font-size:13px;
}

.status::before{
    content:"●";
    margin-right:7px;
}

/* =========================
   PROFILE
========================= */

.profile{
    display:flex;
    align-items:center;
    gap:20px;
    background:linear-gradient(135deg,#111827,#0f172a);
    border:1px solid #1e293b;
    border-radius:18px;
    padding:25px;
    margin-bottom:25px;
}

.profile foto jpg{
    width:100px;
    height:100px;
    border-radius:16px;
    object-fit:cover;
    border:2px solid #38bdf8;
}

.profile h1{
    margin:0;
    font-size:27px;
}

.profile p{
    margin:7px 0;
    color:#94a3b8;
}

.badge{
    display:inline-block;
    margin-top:8px;
    padding:6px 10px;
    border-radius:6px;
    background:#0c4a6e;
    color:#7dd3fc;
    font-size:11px;
}

/* =========================
   SECTIONS
========================= */

.section{
    display:none;
}

.section.active{
    display:block;
}

.title{
    font-size:21px;
    margin-bottom:18px;
}

/* =========================
   CARDS
========================= */

.grid{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:15px;
}

.card{
    background:#0f172a;
    border:1px solid #1e293b;
    border-radius:14px;
    padding:20px;
    transition:.2s;
}

.card:hover{
    transform:translateY(-3px);
    border-color:#0ea5e9;
}

.card-icon{
    font-size:25px;
    margin-bottom:10px;
}

.card h3{
    margin:5px 0;
}

.card p{
    color:#94a3b8;
    font-size:13px;
    line-height:1.6;
}

/* =========================
   API
========================= */

.api{
    background:#020617;
    border:1px solid #1e293b;
    border-radius:14px;
    padding:18px;
    margin-bottom:18px;
}

.api-header{
    display:flex;
    align-items:center;
    gap:10px;
    margin-bottom:12px;
}

.method{
    background:#166534;
    color:#86efac;
    padding:5px 8px;
    border-radius:5px;
    font-size:11px;
    font-weight:bold;
}

.api-url{
    color:#cbd5e1;
    font-family:monospace;
    font-size:13px;
}

.api p{
    color:#64748b;
    font-size:13px;
    line-height:1.6;
}

/* =========================
   TECHNOLOGIES
========================= */

.tech-list{
    display:flex;
    flex-wrap:wrap;
    gap:10px;
}

.tech{
    padding:11px 15px;
    background:#111827;
    border:1px solid #334155;
    border-radius:9px;
    color:#cbd5e1;
    font-size:13px;
    cursor:pointer;
    transition:.2s;
}

.tech:hover{
    border-color:#38bdf8;
    color:#38bdf8;
    transform:translateY(-2px);
}

/* =========================
   CONTACT
========================= */

.contact{
    display:flex;
    flex-wrap:wrap;
    gap:12px;
}

.contact a{
    text-decoration:none;
    padding:13px 18px;
    border-radius:9px;
    font-weight:bold;
    font-size:13px;
}

.whatsapp{
    background:#22c55e;
    color:white;
}

.linkedin{
    background:#0284c7;
    color:white;
}

/* =========================
   FOOTER
========================= */

.footer{
    margin-top:40px;
    text-align:center;
    color:#475569;
    font-size:11px;
}

/* =========================
   MOBILE
========================= */

@media(max-width:700px){

    .app{
        display:block;
    }

    .sidebar{
        width:100%;
        height:auto;
        position:relative;
        border-right:0;
        border-bottom:1px solid #1e293b;
        padding:15px;
    }

    .logo{
        margin-bottom:12px;
    }

    .menu{
        display:flex;
        overflow-x:auto;
        gap:6px;
        padding-bottom:5px;
    }

    .menu button{
        min-width:max-content;
        width:auto;
        margin:0;
    }

    .main{
        padding:15px;
    }

    .profile{
        flex-direction:column;
        text-align:center;
    }

    .grid{
        grid-template-columns:1fr;
    }

    .topbar{
        font-size:12px;
    }

}

</style>
</head>


<body>

<div class="app">

<!-- =========================
     MENÚ
========================= -->

<aside class="sidebar">

<div class="logo">

FELIPE.API

<span>
TECH PORTFOLIO v1.0
</span>

</div>


<div class="menu">

<button class="active"
onclick="showSection('inicio',this)">
🏠 Inicio
</button>


<button
onclick="showSection('telecom',this)">
📡 Telecom
</button>


<button
onclick="showSection('desarrollo',this)">
💻 Desarrollo
</button>


<button
onclick="showSection('proyectos',this)">
🚀 Proyectos
</button>


<button
onclick="showSection('perfil',this)">
👤 Perfil
</button>


<button
onclick="showSection('contacto',this)">
📲 Contacto
</button>

</div>

</aside>


<!-- =========================
     CONTENIDO
========================= -->

<main class="main">


<div class="topbar">

<div class="endpoint">
API / portfolio / v1
</div>

<div class="status">
SYSTEM ONLINE
</div>

</div>


<!-- =========================
     INICIO
========================= -->

<section id="inicio" class="section active">

<div class="profile">

<img src="perfil.jpg">

<div>

<h1>
Felipe Botina
</h1>

<p>
Tecnólogo en Telecomunicaciones
</p>

<p>
Ingeniería en Programación — En curso
</p>

<span class="badge">
BACKEND + FRONTEND
</span>

</div>

</div>


<h2 class="title">
Dashboard Profesional
</h2>


<div class="grid">


<div class="card">

<div class="card-icon">
📡
</div>

<h3>
Telecomunicaciones
</h3>

<p>
Experiencia técnica en infraestructura
de redes, FTTH, HFC, fibra óptica,
equipos y soporte técnico.
</p>

</div>


<div class="card">

<div class="card-icon">
⚙️
</div>

<h3>
Backend
</h3>

<p>
Desarrollo de lógica de aplicaciones,
servicios, APIs, automatización y
procesamiento de información.
</p>

</div>


<div class="card">

<div class="card-icon">
💻
</div>

<h3>
Frontend
</h3>

<p>
Creación de interfaces web modernas,
responsivas y orientadas a la
experiencia del usuario.
</p>

</div>


<div class="card">

<div class="card-icon">
🚀
</div>

<h3>
Objetivo Profesional
</h3>

<p>
Integrar telecomunicaciones y
desarrollo de software para crear
soluciones tecnológicas.
</p>

</div>


</div>

</section>


<!-- =========================
     TELECOM
========================= -->

<section id="telecom" class="section">

<h2 class="title">
📡 Telecomunicaciones
</h2>


<div class="api">

<div class="api-header">

<span class="method">
TECH
</span>

<span class="api-url">
/telecommunications
</span>

</div>

<p>
Conocimientos y experiencia práctica
en instalación, diagnóstico,
mantenimiento y configuración de
infraestructura de telecomunicaciones.
</p>

</div>


<div class="tech-list">

<span class="tech">
📡 FTTH
</span>

<span class="tech">
📶 HFC
</span>

<span class="tech">
🔦 Fibra Óptica
</span>

<span class="tech">
📦 ONT
</span>

<span class="tech">
🛰️ OLT
</span>

<span class="tech">
🌐 DOCSIS
</span>

<span class="tech">
📡 MTA
</span>

<span class="tech">
📶 WiFi
</span>

<span class="tech">
🌎 Redes IP
</span>

<span class="tech">
📡 Routers
</span>

<span class="tech">
🔧 Diagnóstico
</span>

<span class="tech">
🛠️ Soporte Técnico
</span>

</div>

</section>


<!-- =========================
     DESARROLLO
========================= -->

<section id="desarrollo" class="section">

<h2 class="title">
💻 Desarrollo de Software
</h2>


<div class="api">

<div class="api-header">

<span class="method">
DEV
</span>

<span class="api-url">
/api/development
</span>

</div>

<p>
Formación en programación y desarrollo
de aplicaciones Backend y Frontend.
</p>

</div>


<h3>
⚙️ Lenguajes y herramientas
</h3>


<div class="tech-list">

<span class="tech">
🐍 Python
</span>

<span class="tech">
🟨 JavaScript
</span>

<span class="tech">
☕ Java
</span>

<span class="tech">
🟣 Visual Studio
</span>

<span class="tech">
⚡ C++
</span>

<span class="tech">
🌐 HTML5
</span>

<span class="tech">
🎨 CSS3
</span>

</div>


<br>


<h3>
🔌 Backend
</h3>


<div class="tech-list">

<span class="tech">
🔗 REST API
</span>

<span class="tech">
📦 JSON
</span>

<span class="tech">
🌐 HTTP
</span>

<span class="tech">
⚙️ Automatización
</span>

<span class="tech">
🧠 Lógica de Programación
</span>

</div>


<br>


<h3>
🖥️ Frontend
</h3>


<div class="tech-list">

<span class="tech">
HTML
</span>

<span class="tech">
CSS
</span>

<span class="tech">
JavaScript
</span>

<span class="tech">
Responsive Design
</span>

<span class="tech">
UI
</span>

<span class="tech">
UX
</span>

</div>

</section>


<!-- =========================
     PROYECTOS
========================= -->

<section id="proyectos" class="section">

<h2 class="title">
🚀 Proyectos
</h2>


<div class="grid">


<div class="card">

<div class="card-icon">
🌐
</div>

<h3>
Web Portfolio
</h3>

<p>
Interfaz web profesional desarrollada
con HTML, CSS y JavaScript.
</p>

</div>


<div class="card">

<div class="card-icon">
🔌
</div>

<h3>
API Services
</h3>

<p>
Concepto de servicios Backend para
integración entre aplicaciones.
</p>

</div>


<div class="card">

<div class="card-icon">
📡
</div>

<h3>
Network Solutions
</h3>

<p>
Soluciones orientadas a infraestructura
de telecomunicaciones y redes.
</p>

</div>


<div class="card">

<div class="card-icon">
🤖
</div>

<h3>
Automation
</h3>

<p>
Automatización de tareas mediante
programación y herramientas digitales.
</p>

</div>

</div>

</section>


<!-- =========================
     PERFIL
========================= -->

<section id="perfil" class="section">

<h2 class="title">
👤 Perfil Profesional
</h2>


<div class="api">

<div class="api-header">

<span class="method">
PROFILE
</span>

<span class="api-url">
/api/profile
</span>

</div>


<p>

<strong>
Tecnólogo en Telecomunicaciones
</strong>

<br><br>

<strong>
Ingeniería en Programación — En curso
</strong>

<br><br>

<strong>
Especialización de interés:
Backend + Frontend
</strong>

<br><br>

Perfil técnico orientado a la integración
entre infraestructura de telecomunicaciones
y desarrollo de software.

</p>

</div>

</section>


<!-- =========================
     CONTACTO
========================= -->

<section id="contacto" class="section">

<h2 class="title">
📲 Contacto
</h2>


<div class="card">

<h3>
¿Trabajamos juntos?
</h3>


<p>

Disponible para oportunidades,
proyectos y soluciones relacionadas
con telecomunicaciones y desarrollo
de software.

</p>


<div class="contact">


<a
href="https://wa.me/573046338016"
target="_blank"
class="whatsapp">

💬 WhatsApp

</a>


<a
href="#"
class="linkedin">

💼 LinkedIn

</a>


</div>

</div>

</section>


<div class="footer">

© 2026 Felipe Botina · Tech API Portfolio

</div>


</main>

</div>


<!-- =========================
     JAVASCRIPT
========================= -->

<script>

function showSection(id,button){

const sections =
document.querySelectorAll('.section');

sections.forEach(section => {

section.classList.remove('active');

});


document
.getElementById(id)
.classList.add('active');


const buttons =
document.querySelectorAll('.menu button');

buttons.forEach(btn => {

btn.classList.remove('active');

});


button.classList.add('active');

}

</script>


</body>
</html>
