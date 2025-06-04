<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Olula del Río | Arte, Historia y Naturaleza</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    :root {
      --azul-oscuro: #023e8a;
      --azul-medio: #0077b6;
      --azul-claro: #90e0ef;
      --azul-fondo: #caf0f8;
      --blanco: #ffffff;
      --gris-claro: #f8f9fa;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: var(--gris-claro);
      color: #333;
    }

    header {
      background: linear-gradient(to right, var(--azul-medio), var(--azul-oscuro));
      color: white;
      text-align: center;
      padding: 60px 20px;
    }

    header h1 {
      font-size: 3em;
    }

    header p {
      font-size: 1.3em;
      opacity: 0.9;
    }

    nav {
      background-color: var(--azul-claro);
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 15px;
    }

    nav a {
      color: var(--azul-oscuro);
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1em;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
      background-color: var(--blanco);
      border-radius: 12px;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
      margin-bottom: 40px;
    }

    section h2 {
      color: var(--azul-oscuro);
      font-size: 2em;
      margin-bottom: 15px;
    }

    section p {
      font-size: 1.1em;
      line-height: 1.7;
    }

    .gallery img {
      width: 100%;
      border-radius: 10px;
      margin-top: 15px;
    }

    .video-container {
      position: relative;
      padding-bottom: 56.25%;
      height: 0;
      overflow: hidden;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
      margin-top: 30px;
    }

    .video-container iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
    }

    footer {
      background-color: var(--azul-oscuro);
      color: white;
      text-align: center;
      padding: 30px 20px;
    }

    .autor {
      background-color: var(--azul-fondo);
      text-align: center;
      padding: 40px;
      border-radius: 15px;
      font-size: 1.2em;
    }

    .autor span {
      font-size: 2em;
    }
  </style>
</head>
<body>

  <header>
    <h1>Olula del Río</h1>
    <p>EL MEJOR SITIO EN MI OPINIÓN</p>
  </header>

  <nav>
    <a href="#historia">Historia</a>
    <a href="#cultura">Cultura</a>
    <a href="#naturaleza">Naturaleza</a>
    <a href="#fiestas">Fiestas</a>
    <a href="#videos">Vídeo</a>
  </nav>

  <section id="historia">
    <h2>📜 Historia y Patrimonio</h2>
    <p>Olula del Río tiene una historia rica desde época íbera, romana y musulmana. Se integró a la Corona de Castilla tras la Reconquista y prosperó gracias al mármol. El Puente Romano, la Iglesia de San Sebastián (siglo XVIII) y otras construcciones muestran ese legado.</p>
    <div class="gallery">
      <img src="https://turismoalmanzora.com/wp-content/uploads/portada-olula2.jpg" alt="Vista histórica">
    </div>
  </section>

  <section id="cultura">
    <h2>🎨 Cultura y Arte</h2>
    <p>El arte contemporáneo está muy presente: el Museo Casa Ibáñez alberga más de 1.200 obras. La escultura “La Mujer del Almanzora”, de Antonio López, es la más grande de mármol en España. También destacan el Centro Pérez Siquier y el proyecto olulARTE.</p>
    <div class="gallery">
      <img src="https://turismoalmanzora.com/wp-content/uploads/museo-casa-ibanez-olula.jpg" alt="Museo Casa Ibáñez">
    </div>
  </section>

  <section id="naturaleza">
    <h2>⛰️ Naturaleza y Rutas</h2>
    <p>La Sierra de los Filabres ofrece un entorno natural único. Senderos como la Ruta del Maimón, la Cueva del Agua y la Cascada de los Chorros son muy visitados. Ideal para senderismo, ciclismo y aire puro.</p>
    <div class="gallery">
      <img src="https://s1.wklcdn.com/image_11/336209/20819387/13039231.400x300.jpg" alt="Ruta del Maimón">
    </div>
  </section>

  <section id="fiestas">
    <h2>🎉 Fiestas y Tradiciones</h2>
    <p>Las fiestas patronales de San Sebastián (enero) y la Feria de Agosto llenan las calles de música, luces y emoción. La Semana Santa es muy sentida y cuenta con procesiones solemnes. También se celebra San Isidro con una alegre romería.</p>
    <div class="gallery">
      <img src="https://static.grupojoly.com/clip/3b42afb4-0d02-4c48-b3fd-a47c87beae23_source-aspect-ratio_1600w_0.jpg" alt="Fiestas de Olula del Río">
    </div>
  </section>

  <section id="videos">
    <h2>🎬 Vídeos sobre Olula del Río</h2>
    <p>Disfruta de este vídeo sobre nuestro querido pueblo. ¡Aprende, descubre y explora visualmente! 📺✨</p>
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/290Lt9I20AY?si=4Z-VS-OGZgK3XzwQ" title="Olula del Río Video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </section>

  <section class="autor">
    <p><span>✨</span><br>
    <strong>Creado por Muhammad Abdullah</strong><br>
    Estudiante de <strong>2º de la ESO A</strong><br>
    🌍📘✏️💻🎓</p>
  </section>

  <footer>
    <p>&copy; 2025 | Creado por Muhammad Abdullah</p>
  </footer>

</body>
</html>

