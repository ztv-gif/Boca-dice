# Boca-dice
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Boca Dice</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #0033a0; /* Azul Boca */
      color: #ffcc00;           /* Amarillo Boca */
      text-align: center;
      padding: 1.5rem;
    }

    header h1 {
      margin: 0;
      font-size: 2rem;
    }

    header p {
      margin: 0.5rem 0 0;
      font-size: 1.2rem;
    }

    main {
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    .noticia {
      background: white;
      border-left: 8px solid #ffcc00;
      padding: 1rem;
      margin-bottom: 2rem;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    .partidos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }

    .partido {
      background: white;
      border: 2px solid #0033a0;
      border-radius: 10px;
      padding: 1rem;
      text-align: center;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    footer {
      background: #0033a0;
      color: #ffcc00;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>BOCA DICE</h1>
    <p>Noticias y próximos partidos del Xeneize</p>
  </header>

  <main>
    <section class="noticia">
      <h2>Última noticia</h2>
      <p><strong>Boca Juniors</strong> se prepara para su próximo compromiso en la Copa de la Liga, con la mira puesta en seguir sumando puntos importantes y consolidar el plantel de cara al cierre del semestre.</p>
    </section>

    <h2>Próximos 5 partidos</h2>
    <div class="partidos">
      <div class="partido">
        <h3>Boca vs Atlético Tucumán</h3>
        <p>Domingo 7 de septiembre, 21:00</p>
      </div>
      <div class="partido">
        <h3>San Lorenzo vs Boca</h3>
        <p>Miércoles 10 de septiembre, 19:30</p>
      </div>
      <div class="partido">
        <h3>Boca vs Talleres</h3>
        <p>Sábado 13 de septiembre, 20:00</p>
      </div>
      <div class="partido">
        <h3>Racing vs Boca</h3>
        <p>Miércoles 17 de septiembre, 21:30</p>
      </div>
      <div class="partido">
        <h3>Boca vs Independiente</h3>
        <p>Domingo 21 de septiembre, 18:00</p>
      </div>
    </div>
  </main>

  <footer>
    <p>© 2025 Boca Dice - Sitio de noticias no oficial</p>
  </footer>
</body>
</html>
