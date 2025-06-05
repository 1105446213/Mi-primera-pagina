<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Alejandra - Estilo y Elegancia</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      color: #333;
      background-image: url('Negocio/mariposas.jpg'); /* Fondo mariposas */
      background-size: cover;
      background-repeat: no-repeat;
      background-attachment: fixed;
    }

    header {
      background-color: rgba(255, 105, 180, 0.9); /* Rosa intenso */
      color: white;
      text-align: center;
      padding: 30px 20px;
    }

    header h1 {
      margin: 0;
      font-size: 3em;
      font-family: 'Georgia', serif;
      letter-spacing: 2px;
    }

    header p {
      margin-top: 10px;
      font-size: 1.2em;
    }

    nav {
      background-color: rgba(255, 228, 225, 0.95); /* Rosa claro */
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }

    nav a {
      color: #d63384;
      text-decoration: none;
      margin: 0 20px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      background-color: rgba(255, 255, 255, 0.6);
      height: 60vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }

    .hero h2 {
      color: #d63384;
      font-size: 2.5em;
      padding: 0 20px;
    }

    .section {
      background-color: rgba(255, 255, 255, 0.85);
      padding: 60px 20px;
      max-width: 900px;
      margin: 40px auto;
      border-radius: 12px;
    }

    .section img {
      max-width: 100%;
      border-radius: 12px;
      margin-bottom: 20px;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
    }

    .section h2 {
      color: #d63384;
      margin-bottom: 20px;
    }

    .section p {
      font-size: 1.1em;
      line-height: 1.6;
    }

    footer {
      background-color: rgba(255, 105, 180, 0.9);
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Alejandra</h1>
    <p>Estilo, fuerza y elegancia femenina</p>
  </header>

  <nav>
    <a href="#">Inicio</a>
    <a href="#">Colección</a>
    <a href="#">Nosotras</a>
    <a href="#">Contáctanos</a>
  </nav>

  <section class="hero">
    <h2>Descubre tu estilo único con Alejandra 🦋</h2>
  </section>

  <section class="section">
    <img src="https://images.unsplash.com/photo-1616587893783-d33a1571c353?auto=format&fit=crop&w=800&q=80" alt="Mujer de negocios">
    <h2>Bienvenida a Alejandra</h2>
    <p>Alejandra es más que una marca: es una declaración de identidad, confianza y belleza. Diseñamos pensando en ti, en tu autenticidad, y en tu camino único. Desde atuendos elegantes hasta opciones casuales con estilo, queremos acompañarte en cada paso de tu vida.</p>
  </section>

  <footer>
    &copy; 2025 Alejandra. Todos los derechos reservados.
  </footer>

</body>
</html>
