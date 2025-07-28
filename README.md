# <!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>NovaWeb - Creación de páginas web</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }
    body {
      background-color: #000;
      color: #fff;
      line-height: 1.6;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 2rem;
    }
    header img {
      height: 60px;
    }
    .hero {
      text-align: center;
      padding: 5rem 2rem;
    }
    .hero h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.25rem;
      color: #ccc;
      margin-bottom: 2rem;
    }
    .hero a {
      background: #00aaff;
      padding: 1rem 2rem;
      color: #000;
      font-weight: bold;
      text-decoration: none;
      border-radius: 8px;
      transition: 0.3s;
    }
    .hero a:hover {
      background: #0077cc;
    }
    .section-img {
      padding: 4rem 2rem;
      display: flex;
      justify-content: center;
      background: #111;
    }
    .section-img img {
      width: 90%;
      max-width: 900px;
      border-radius: 12px;
    }
    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.875rem;
      color: #666;
    }
  </style>
</head>
<body>
  <header>
    <img src="/mnt/data/A_logo_design_for_NovaWeb_is_displayed_in_white_.png" alt="Logo NovaWeb">
  </header>

  <section class="hero">
    <h1>CREACIÓN DE PÁGINAS WEB</h1>
    <p>Tu negocio online empieza aquí. Diseños modernos, rápidos y funcionales.</p>
    <a href="#">COMENZAR</a>
  </section>

  <section class="section-img">
    <img src="/mnt/data/A_2D_digital_graphic_design_hero_section_of_NovaWe.png" alt="Ejemplo de diseño NovaWeb">
  </section>

  <footer>
    &copy; 2025 NovaWeb. Todos los derechos reservados.
  </footer>
</body>
</html>
