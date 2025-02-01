# ventas-E-Instalaciones-SYL
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ventas e Instalaciones de Cámaras de Seguridad</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
    }
    header {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 20px 0;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    header p {
      margin: 0;
      font-size: 1.2em;
    }
    .container {
      padding: 20px;
      max-width: 1200px;
      margin: auto;
    }
    .benefits, .products, .contact {
      margin-bottom: 30px;
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    .benefits h2, .products h2, .contact h2 {
      color: #333;
      margin-bottom: 10px;
    }
    ul {
      list-style-type: none;
      padding: 0;
    }
    ul li {
      margin: 10px 0;
    }
    .button {
      display: inline-block;
      padding: 10px 20px;
      background-color: #007BFF;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 20px;
    }
    .button:hover {
      background-color: #0056b3;
    }
    footer {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 10px 0;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Cámaras de Seguridad</h1>
    <p>Ventas e instalaciones profesionales al mejor precio</p>
  </header>
  <div class="container">
    <!-- Beneficios -->
    <section class="benefits">
      <h2>¿Por qué elegirnos?</h2>
      <ul>
        <li>✓ Instalación profesional garantizada.</li>
        <li>✓ Cámaras de alta resolución HD y 4K.</li>
        <li>✓ Atención personalizada para empresas y hogares.</li>
        <li>✓ Precios competitivos y soporte técnico 24/7.</li>
      </ul>
    </section>
    <!-- Productos/Servicios -->
    <section class="products">
      <h2>Nuestros productos y servicios</h2>
      <ul>
        <li>📷 Cámara de seguridad HD (Precio: $100)</li>
        <li>📷 Cámara de seguridad 4K (Precio: $200)</li>
        <li>⚙️ Instalación profesional (desde $50)</li>
        <li>🛠️ Mantenimiento y soporte técnico</li>
      </ul>
      <a href="#" class="button">Solicitar Cotización</a>
    </section>
    <!-- Formulario de Contacto -->
    <section class="contact">
      <h2>Contáctanos</h2>
      <p>Déjanos tus datos y te contactaremos a la brevedad:</p>
      <form action="https://formspree.io/f/tu_correo" method="POST">
        <label for="name">Nombre:</label><br>
        <input type="text" id="name" name="name" required><br><br>
        <label for="email">Correo Electrónico:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        <label for="message">Mensaje:</label><br>
        <textarea id="message" name="message" rows="4" required></textarea><br><br>
        <button type="submit" class="button">Enviar</button>
      </form>
    </section>
  </div>
  <footer>
    <p>© 2025 Cámaras de Seguridad. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
