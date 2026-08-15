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
    <div class="hero">
      <img src="perfil_transparente.png" alt="Foto de perfil profesional">
      <h1>Felipe Botina</h1>
      <h2>Ingeniería en Programación backend y Telecomunicaciones</h2>
      <p>Perfil técnico con experiencia en campo en el sector de telecomunicaciones, enfocado en infraestructura de red, configuración de equipos y crecimiento profesional en desarrollo tecnológico.</p>
      <div class="buttons">
        <a href="#contacto" class="btn btn-whatsapp">Contactar</a>
        <a href="#experiencia" class="btn btn-outline">Experiencia Técnica</a>
      </div>
    </div>

    <div class="card" id="experiencia">
      <h3>Experiencia Técnica</h3>
      <p>Instalación, validación y soporte de infraestructura de red, aplicando diagnóstico técnico y optimización de parámetros en campo.</p>
    </div>

    <div class="card">
      <h3>Formación</h3>
      <ul>
        <li>Ingeniería en Programación y Telecomunicaciones (En curso)</li>
        <li>Tecnólogo en Telecomunicaciones 💳</li>
        <li>Técnico Mecánico Industrial</li>
        <li>Técnico en Electricidad</li>
        <li>Electrónica Básica</li>
      </ul>
    </div>

    <div class="card">
      <h3>Stack Tecnológico</h3>
      <div class="bar"><div class="fill" style="width:85%;">Redes y Telecomunicaciones 85%</div></div>
      <div class="bar"><div class="fill" style="width:80%;">Configuración de Equipos 80%</div></div>
      <div class="bar"><div class="fill" style="width:65%;">Python🐍 / Java♨️ (Fundamentos)</div></div>
      <div class="bar"><div class="fill" style="width:70%;">HTML & CSS 70%</div></div>
      <div class="bar"><div class="fill" style="width:60%;">Automatización / IoT 60%</div></div>
    </div>

    <div class="card" id="contacto">
      <h3>Contacto</h3>
      <form id="contactForm">
        <input type="text" name="nombre" placeholder="Tu nombre" required>
        <input type="email" name="email" placeholder="Tu correo" required>
        <textarea name="mensaje" placeholder="Tu mensaje" required></textarea>
        <button type="submit" class="btn btn-outline">Enviar</button>
      </form>
    </div>

    <div class="footer">
      © 2026 Felipe Botina | Portafolio Profesional
    </div>
  </div>
  <a href="https://wa.me/573001234567" class="whatsapp-float">💬</a>
  <script src="script.js"></script>
</body>
</html>