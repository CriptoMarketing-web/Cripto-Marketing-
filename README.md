<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Criptomonedas y Marketing Digital</title>

  <!-- Estilos -->
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #eef3f9;
      color: #1b1b1b;
      scroll-behavior: smooth;
    }

    /* Animaciones */
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    @keyframes slideUp {
      from { transform: translateY(30px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    header {
      background: linear-gradient(135deg, #0a4480, #2da4ff);
      color: white;
      padding: 60px 20px;
      text-align: center;
      animation: fadeIn 1.5s ease;
    }

    header img {
      width: 120px;
      margin-bottom: 15px;
      filter: drop-shadow(0 3px 6px rgba(0,0,0,0.25));
      animation: slideUp 1s;
    }

    .container {
      max-width: 1100px;
      margin: auto;
      padding: 20px;
    }

    .section {
      background: white;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
      margin-bottom: 25px;
      animation: slideUp 0.8s;
      transition: transform 0.3s;
    }

    .section:hover {
      transform: translateY(-5px);
    }

    .section h2 {
      color: #0a4480;
      margin-top: 0;
      transition: color 0.3s;
    }

    .section h2:hover {
      color: #2da4ff;
    }

    /* Tarjetas con interacción */
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px;
    }

    .card {
      background: #ffffff;
      border-radius: 12px;
      padding: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.08);
      text-align: center;
      transition: transform 0.3s, box-shadow 0.3s;
      animation: fadeIn 1s;
    }

    .card:hover {
      transform: translateY(-8px) scale(1.02);
      box-shadow: 0 8px 18px rgba(0,0,0,0.15);
    }

    .card img {
      width: 100%;
      border-radius: 12px;
      margin-bottom: 10px;
      transition: transform 0.3s;
    }

    .card img:hover {
      transform: scale(1.05);
    }

    /* Botón subir */
    #topBtn {
      position: fixed;
      bottom: 25px;
      right: 25px;
      background: #0a4480;
      color: white;
      padding: 12px 16px;
      border-radius: 50%;
      font-size: 18px;
      cursor: pointer;
      box-shadow: 0 4px 10px rgba(0,0,0,0.25);
      display: none;
      transition: background 0.3s;
    }

    #topBtn:hover {
      background: #2da4ff;
    }

    footer {
      text-align: center;
      padding: 15px;
      margin-top: 30px;
      background: #0a4480;
      color: white;
    }
  </style>
</head>

<body>

<header>
  <img src="https://cdn-icons-png.flaticon.com/512/6001/6001375.png">
  <h1>Criptomonedas y Marketing Digital</h1>
  <p>Interactividad, adopción empresarial y estrategias modernas</p>
</header>

<div class="container">

  <section class="section">
    <h2>🎯 Objetivo General</h2>
    <p>Evaluar cómo la adopción de criptomonedas influye en las decisiones de marketing digital en empresas contemporáneas.</p>
  </section>

  <section class="section">
    <h2>📌 Objetivos Específicos</h2>
    <ul>
      <li>Identificar niveles de conocimiento y adopción en empresas.</li>
      <li>Examinar beneficios y riesgos administrativos.</li>
      <li>Analizar su impacto en estrategias digitales.</li>
    </ul>
  </section>

  <section class="section">
    <h2>📊 Adopción Cripto</h2>
    <div class="grid">
      <div class="card">
        <img src="https://cryptologos.cc/logos/bitcoin-btc-logo.png">
        <h3>Adopción creciente</h3>
      </div>

      <div class="card">
        <img src="https://cdn.pixabay.com/photo/2021/02/07/11/33/blockchain-5991483_1280.jpg">
        <h3>Pagos rápidos</h3>
      </div>

      <div class="card">
        <img src="https://cdn.pixabay.com/photo/2016/11/29/02/00/marketing-1868728_1280.jpg">
        <h3>Marketing innovador</h3>
      </div>
    </div>
  </section>

</div>

<footer>
  Página interactiva — Criptomonedas y Marketing Digital © 2025
</footer>

<!-- Botón volver arriba -->
<button id="topBtn" onclick="window.scrollTo({ top: 0, behavior: 'smooth' })">↑</button>

<!-- Script para mostrar/ocultar botón -->
<script>
window.addEventListener("scroll", function() {
  const btn = document.getElementById("topBtn");
  if (window.scrollY > 300) { btn.style.display = "block"; }
  else { btn.style.display = "none"; }
});
</script>

</body>
</html>
