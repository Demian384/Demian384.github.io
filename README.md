<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Tienda</title>
  <style>
    theme: jekyll-theme-minimal
    title: TiendaTest homepage
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f8f8f8;
    }
    header {
      background: #333;
      color: white;
      text-align: center;
      padding: 1rem;
    }
    .productos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
      padding: 1rem;
    }
    .producto {
      background: white;
      border-radius: 8px;
      padding: 1rem;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    .producto img {
      max-width: 100%;
      border-radius: 5px;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #333;
      color: white;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Mi Tienda de Productos</h1>
  </header>

  <section class="productos">
    <div class="producto">
      <img src="producto1.jpg" alt="Producto 1">
      <h2>Producto 1</h2>
      <p>Descripción breve del producto.</p>
    </div>
    <div class="producto">
      <img src="producto2.jpg" alt="Producto 2">
      <h2>Producto 2</h2>
      <p>Descripción breve del producto.</p>
    </div>
    <div class="producto">
      <img src="producto1.jpg" alt="Producto 1">
      <h2>Producto 1</h2>
      <p>Descripción breve del producto.</p>
    </div>
    <!-- Agregás más productos copiando el bloque -->
  </section>

  <footer>
    <p>Contacto: +54 11 1234-5678</p>
  </footer>
</body>
</html>

