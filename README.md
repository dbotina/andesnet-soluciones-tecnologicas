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