# sportivus.github.io
<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sportivus</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: url('background.jpg') no-repeat center center/cover; /* Replace with stadium image */
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      min-height: 100vh;
      text-align: center;
    }
    .logo {
      position: absolute;
      top: 20px;
      left: 20px;
      height: 70px;
    }
    h1 {
      font-size: 2.5rem;
      font-weight: bold;
      line-height: 1.4;
    }
    h1 span {
      color: #a855f7; /* Purple highlight */
    }
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 24px;
      background: #9333ea;
      color: white;
      font-weight: bold;
      text-decoration: none;
      border-radius: 8px;
      transition: background 0.3s;
    }
    .btn:hover {
      background: #7e22ce;
    }
    .stats {
      display: flex;
      justify-content: center;
      gap: 40px;
      padding: 20px;
      background: rgba(0, 0, 0, 0.7);
    }
    .stat p:first-child {
      font-size: 2rem;
      font-weight: bold;
      color: #a855f7;
      margin: 0;
    }
    .stat p:last-child {
      font-size: 0.9rem;
      margin: 5px 0 0;
    }
  </style>
</head>
<body>

  <!-- Logo -->
  <img src="logo.png" alt="Sportivus" class="logo">

  <!-- Hero Section -->
  <div>
    <h1>
      ONDE O <span>MARKETING</span><br>
      O <span>DESPORTO</span> E<br>
      A <span>CRIATIVIDADE</span><br>
      SE ENCONTRAM
    </h1>
    <a href="https://wa.me/258XXXXXXXXX" target="_blank" class="btn">WHATSAPP</a>
  </div>

  <!-- Stats -->
  <div class="stats">
    <div class="stat">
      <p>1000+</p>
      <p>PARTICIPANTES EM EVENTOS</p>
    </div>
    <div class="stat">
      <p>5000+</p>
      <p>HORAS DE SERVIÇOS PRESTADOS</p>
    </div>
    <div class="stat">
      <p>5+</p>
      <p>ANOS DE EXPERIÊNCIA</p>
    </div>
  </div>

</body>
</html>
