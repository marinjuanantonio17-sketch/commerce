<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Panadería Marín</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #fdfaf6;
      color: #4b2e1e;
      line-height: 1.6;
    }
    header {
      background-color: #f5deb3;
      padding: 20px;
      text-align: center;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    header img {
      max-width: 120px;
    }
    nav {
      background-color: #d4a373;
      padding: 10px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      margin: 0 15px;
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      text-align: center;
      padding: 80px 20px;
      background: url('https://images.unsplash.com/photo-1608198093002-de4d45e0a7a1?auto=format&fit=crop&w=1600&q=80') no-repeat center/cover;
      color: white;
    }
    .hero h1 {
      font-size: 3em;
      background: rgba(0,0,0,0.5);
      display: inline-block;
      padding: 10px 20px;
      border-radius: 10px;
    }
    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      text-align: center;
      margin-bottom: 20px;
    }
    .productos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .producto {
      background: #fff;
      border-radius: 10px;
      box-shadow: 0px 2px 6px rgba(0,0,0,0.1);
      padding: 20px;
      text-align: center;
      transition: transform 0.2s;
    }
    .producto:hover {
      transform: scale(1.05);
    }
    .producto img {
      max-width: 100%;
      border-radius: 10px;
    }
    footer {
      background-color: #d4a373;
      text-align: center;
      padding: 20px;
      color: #fff;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <img src="FB_IMG_1756431456918.jpg" alt="Logo Panadería Marín">
    <h2>Panadería Marín</h2>
    <p>Tradición desde 1960</p>
  </header>

  <nav>
    <a href="#nosotros">Nosotros</a>
    <a href="#productos">Productos</a>
    <a href="#ubicacion">Ubicación</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <div class="hero">
    <h1>El sabor de la tradición en cada mordida</h1>
  </div>

  <section id="nosotros">
    <h2>Sobre Nosotros</h2>
    <p>
      En <strong>Panadería Marín</strong>, desde 1960, horneamos con amor y dedicación pan fresco para nuestra comunidad.
      Ubicados en el centro de Ocampo, Michoacán, seguimos conservando el sabor auténtico que ha acompañado a generaciones.
    </p>
  </section>

  <section id="productos">
    <h2>Nuestros Productos</h2>
    <div class="productos">
      <div class="producto">
        <img src="https://images.unsplash.com/photo-1608198093002-de4d45e0a7a1?auto=format&fit=crop&w=500&q=80" alt="Pan artesanal">
        <h3>Pan artesanal</h3>
      </div>
      <div class="producto">
        <img src="https://images.unsplash.com/photo-1542831371-d531d36971e6?auto=format&fit=crop&w=500&q=80" alt="Pasteles">
        <h3>Pasteles</h3>
      </div>
      <div class="producto">
        <img src="https://images.unsplash.com/photo-1622737133809-d95047b9bb25?auto=format&fit=crop&w=500&q=80" alt="Conchas">
        <h3>Conchas</h3>
      </div>
    </div>
  </section>

  <section id="ubicacion">
    <h2>Ubicación</h2>
    <p>📍 Nos encuentras en el centro de Ocampo, Michoacán.</p>
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!..." width="100%" height="300" style="border:0;" allowfullscreen loading="lazy"></iframe>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p>📞 Teléfono: 55-1234-5678</p>
    <p>💬 WhatsApp: <a href="https://wa.me/5215512345678" target="_blank">Haz tu pedido aquí</a></p>
    <p>📩 Facebook: <a href="https://facebook.com" target="_blank">Panadería Marín</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Panadería Marín - Ocampo, Michoacán</p>
  </footer>

</body>
</html>
