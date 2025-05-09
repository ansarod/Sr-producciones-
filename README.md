<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SR Producciones</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f5f5f5;
      color: #000;
    }
    header {
      background-color: #000;
      color: #fff;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav a {
      color: #fff;
      margin-left: 1.5rem;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .logo {
      height: 60px;
    }
    section {
      padding: 4rem 2rem;
    }
    .title {
      text-align: center;
      margin-bottom: 2rem;
    }
    .services-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1.5rem;
    }
    .service-item {
      background: #fff;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
      text-align: center;
    }
    iframe {
      display: block;
      margin: 0 auto;
      border: none;
      width: 100%;
      max-width: 640px;
      height: 800px;
    }
    footer {
      background-color: #000;
      color: #fff;
      text-align: center;
      padding: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="SR Producciones" class="logo">
    <nav>
      <a href="#inicio">Inicio</a>
      <a href="#nosotros">Nosotros</a>
      <a href="#servicios">Servicios</a>
      <a href="#galeria">Galería</a>
      <a href="#contacto">Contáctanos</a>
    </nav>
  </header>

  <section id="inicio">
    <h1 class="title">Soluciones creativas para tu empresa</h1>
  </section>

  <section id="nosotros">
    <h2 class="title">Nosotros</h2>
    <p>En SR Producciones nos dedicamos a ofrecer experiencias únicas y creativas en eventos comerciales y privados. Nuestro equipo profesional se encarga de animación en puerta, perifoneo, anfitrionas, volanteos y más.</p>
  </section>

  <section id="servicios">
    <h2 class="title">Servicios</h2>
    <div class="services-list">
      <div class="service-item">Eventos comerciales</div>
      <div class="service-item">Animación en puerta</div>
      <div class="service-item">Anfitrionas</div>
      <div class="service-item">Volanteos</div>
      <div class="service-item">Perifoneo</div>
      <div class="service-item">Bingos</div>
      <div class="service-item">Fiestas privadas</div>
      <div class="service-item">Bodas</div>
      <div class="service-item">Cumpleaños</div>
    </div>
  </section>

  <section id="galeria">
    <h2 class="title">Galería</h2>
    <p>Próximamente podrás ver nuestras fotos destacadas de eventos realizados.</p>
  </section>

  <section id="contacto">
    <h2 class="title">Contáctanos</h2>
    <p>Completa el siguiente formulario para recibir más información o solicitar una cotización.</p>
    <!-- Reemplaza la URL del iframe con la URL de tu formulario de Google Forms -->
    <iframe src="https://docs.google.com/forms/d/e/tu-formulario-id/viewform?embedded=true" frameborder="0" marginheight="0" marginwidth="0">Cargando…</iframe>
  </section>

  <footer>
    &copy; 2025 SR Producciones. Todos los derechos reservados.
  </footer>
</body>
</html>
