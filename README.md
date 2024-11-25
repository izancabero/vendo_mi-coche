<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Decepción</title>
  <style>
    /* Estilos Generales */
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #2c3e50, #4ca1af); /* Fondo con degradado */
      color: #fff; /* Texto blanco para destacar sobre el fondo */
    }

    h1 {
      color: #ffcc00; /* Amarillo brillante */
      font-size: 2.5em;
      margin: 20px 0;
      text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5); /* Sombra para destacar */
    }

    p {
      margin: 10px 20px;
      font-size: 1.2em;
      line-height: 1.5;
      text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.4);
    }

    /* Estilo para la galería */
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
      padding: 20px;
    }

    .gallery img {
      width: 200px;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .gallery img:hover {
      transform: scale(1.1); /* Efecto de zoom */
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.7);
    }

    /* Video */
    .video-container {
      margin: 30px auto;
      max-width: 300px;
      border: 5px solid #ffcc00;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.7);
    }

    video {
      width: 100%;
      height: auto;
    }
  </style>
</head>
<body>
  <h1>¡ATENCIÓN AMANTES DE LOS CLÁSICOS! 🚗✨</h1>
  <p>¿Te imaginas rodando en un coche histórico de 1970, lleno de personalidad y carácter? Este es el vehículo que cuenta una historia, un verdadero testigo de su época, con todas sus piezas originales y en perfecto estado.</p>

  <p>🛠️ Restaurado con detalle y amor, este clásico conserva su autenticidad y elegancia, acompañado de su identificación fiscal y título en regla. Es más que un coche: ¡es una obra de arte sobre ruedas!</p>

  <p>🚘 Perfecto para coleccionistas o para quienes buscan un auto único que no solo es transporte, sino estilo, historia y distinción.</p>

  <p>No dejes pasar la oportunidad de convertirte en el dueño de una joya del pasado. ¡Lláma ahora y dale vida a tu garaje con este icónico vehículo! 🔑💥</p>

  <p>📞 Contácta hoy mismo y descubre el placer de poseer un clásico inolvidable. ¡El coche de tus sueños te está esperando! 🏁 (624448841)</p>
  <div class="gallery">
    <img src="foto1.jpg" alt="Foto 1">
    <img src="foto2.jpg" alt="Foto 2">
    <img src="foto3.jpg" alt="Foto 3">
    <img src="foto4.jpg" alt="Foto 4">
    <img src="foto5.jpg" alt="Foto 5">
    <img src="foto6.jpg" alt="Foto 6">
  </div>
  
  <div class="video-container">
    <video controls>
      <source src="video.mp4" type="video/mp4">
      Tu navegador no soporta la etiqueta de video. Por favor, intenta actualizarlo.
    </video>
  </div>

  
</body>
</html>
