<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Felipe Botina | Portafolio Profesional</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="wrapper">
    <!-- HERO -->
    <div class="hero fade-in">
      <img src="perfil_transparente.png" alt="Foto de perfil profesional">
      <h1>Felipe Botina</h1>
      <h2>Ingeniería en Programación backend y Telecomunicaciones</h2>
      <p>Perfil técnico con experiencia en telecomunicaciones, infraestructura de red y desarrollo backend.</p>
      <div class="buttons">
        <a href="#contacto" class="btn btn-primary">📩 Contactar</a>
        <a href="#experiencia" class="btn btn-secondary">⚡ Experiencia Técnica</a>
      </div>
    </div>

    <!-- STACK -->
    <div class="card">
      <h3>Stack Tecnológico</h3>
      <div class="bar"><div class="fill" data-width="85%">Redes y Telecomunicaciones</div></div>
      <div class="bar"><div class="fill" data-width="80%">Configuración de Equipos</div></div>
      <div class="bar"><div class="fill" data-width="65%">Python 🐍 / Java ♨️</div></div>
      <div class="bar"><div class="fill" data-width="70%">HTML & CSS</div></div>
      <div class="bar"><div class="fill" data-width="60%">Automatización / IoT</div></div>
    </div>

    <!-- CONTACTO -->
    <div class="card" id="contacto">
      <h3>Contacto</h3>
      <form id="contactForm">
        <input type="text" name="nombre" placeholder="Tu nombre" required>
        <input type="email" name="email" placeholder="Tu correo" required>
        <textarea name="mensaje" placeholder="Tu mensaje" required></textarea>
        <button type="submit" class="btn btn-primary">Enviar 🚀</button>
      </form>
    </div>

    <!-- FOOTER -->
    <div class="footer">
      © 2026 Felipe Botina | Portafolio Profesional
    </div>
  </div>
  <a href="https://wa.me/573001234567" class="whatsapp-float">💬</a>
  <script src="script.js"></script>
</body>
</html>

body{margin:0;font-family:'Segoe UI',sans-serif;background:#0f172a;color:#f1f5f9;}
.hero{background:linear-gradient(135deg,#0ea5e9,#38bdf8);padding:80px 20px;border-radius:16px;text-align:center;box-shadow:0 10px 25px rgba(0,0,0,0.3);margin-bottom:40px;color:white;opacity:0;transform:translateY(30px);transition:all 1s ease;}
.hero.fade-in{opacity:1;transform:translateY(0);}
.hero img{width:150px;height:150px;border-radius:50%;object-fit:cover;margin-bottom:20px;border:4px solid #fff;box-shadow:0 5px 15px rgba(0,0,0,0.4);}
.btn{display:inline-block;margin:8px;padding:12px 22px;border-radius:10px;text-decoration:none;font-weight:bold;font-size:14px;transition:0.3s;}
.btn-primary{background:#22c55e;color:white;}
.btn-secondary{background:white;color:#0ea5e9;}
.btn:hover{transform:scale(1.05);box-shadow:0 0 15px rgba(255,255,255,0.6);}
.card{background:#1e293b;padding:30px;border-radius:16px;margin-bottom:30px;box-shadow:0 10px 25px rgba(0,0,0,0.2);}
.card h3{margin-top:0;color:#38bdf8;}
.bar{background:#334155;border-radius:10px;overflow:hidden;margin-bottom:20px;}
.fill{background:linear-gradient(90deg,#38bdf8,#0ea5e9);color:white;padding:6px 10px;font-size:12px;font-weight:bold;width:0;transition:width 2s ease;}
.footer{text-align:center;margin-top:40px;font-size:13px;color:#94a3b8;}
.whatsapp-float{position:fixed;bottom:20px;right:20px;background:#22c55e;color:white;width:55px;height:55px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:24px;text-decoration:none;box-shadow:0 8px 20px rgba(0,0,0,0.3);}
input,textarea{width:100%;padding:10px;margin:8px 0;border:1px solid #475569;border-radius:8px;background:#0f172a;color:#f1f5f9;transition:0.3s;}
input:focus,textarea:focus{border-color:#38bdf8;box-shadow:0 0 10px #0ea5e9;}

// Animar barras al hacer scroll
const fills = document.querySelectorAll('.fill');
window.addEventListener('scroll', () => {
  fills.forEach(fill => {
    const rect = fill.getBoundingClientRect();
    if(rect.top < window.innerHeight){
      fill.style.width = fill.getAttribute('data-width');
    }
  });
});

// Formulario contacto
document.getElementById('contactForm').addEventListener('submit', async (e) => {
  e.preventDefault();
  const data = {
    nombre: e.target.nombre.value,
    email: e.target.email.value,
    mensaje: e.target.mensaje.value
  };
  const res = await fetch('/contacto', {
    method: 'POST',
    headers: {'Content-Type': 'application/json'},
    body: JSON.stringify(data)
  });
  const result = await res.json();
  alert(result.message);
  e.target.reset();
});
