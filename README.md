# Blog-da-Dora<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Isadora Amancio</title>
  <style>
    body {
      background: linear-gradient(to bottom, #fff0f5, #ffe4e1);
      font-family: 'Comic Sans MS', cursive;
      color: #ff1493;
      margin: 0;
      padding: 0;
      text-align: center;
      overflow-x: hidden;
    }
    header {
      background: url('https://i.imgur.com/Ic3zKDB.png') no-repeat center top, #fffafc;
      background-size: contain;
      padding: 40px 20px 20px;
      border-bottom: 3px dotted #ffb6c1;
    }
    h1 {
      font-size: 3em;
      text-shadow: 2px 2px #ffc0cb;
    }
    nav {
      margin-top: 20px;
    }
    nav a {
      margin: 0 10px;
      color: #ff1493;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.2em;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .content {
      background-color: rgba(255, 250, 250, 0.9);
      margin: 30px auto;
      padding: 20px;
      width: 90%;
      max-width: 800px;
      border: 2px dashed #ffc0cb;
      border-radius: 20px;
      box-shadow: 0 0 15px #ff69b4;
    }
    .sparkle {
      width: 100px;
      position: absolute;
      animation: sparkle 2s infinite ease-in-out;
    }
    @keyframes sparkle {
      0%, 100% { transform: translateY(0) rotate(0deg); }
      50% { transform: translateY(20px) rotate(15deg); }
    }
    .bows {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin: 20px 0;
    }
    .bows img {
      width: 60px;
      height: auto;
    }
    footer {
      font-size: 0.8em;
      color: #ff69b4;
      margin: 40px 0 20px;
    }
    @media (max-width: 600px) {
      h1 { font-size: 2em; }
      nav a { font-size: 1em; }
      .bows img { width: 40px; }
    }
  </style>
</head>
<body>
  <header>
    <h1>Isadora Amancio</h1>
    <p>Blog pessoal cheio de glitter e vibes 2000!</p>
    <nav>
      <a href="#">Home</a>
      <a href="#">Sobre</a>
      <a href="#">Diário</a>
      <a href="#">Contatos</a>
    </nav>
  </header>
  <div class="bows">
    <img src="https://i.imgur.com/OdL0XPt.png" alt="Laço rosa fofo">
    <img src="https://i.imgur.com/OdL0XPt.png" alt="Laço rosa fofo">
    <img src="https://i.imgur.com/OdL0XPt.png" alt="Laço rosa fofo">
  </div>
  <div class="content">
    <h2>Oi, você!</h2>
    <p>Bem-vinda ao meu mundinho cor-de-rosa! Aqui compartilho tudo que amo: glitter, diários, dias de chuva, músicas que tocam o coração e coisinhas fofas!</p>
    <p>Fique à vontade para explorar e me acompanhar!</p>
  </div>
  <footer>
    © 2025 Isadora Amancio. Feito com amor, laços e glitter.
  </footer>

  <!-- Sparkle effect -->
  <img src="https://i.imgur.com/rGLvF3z.gif" class="sparkle" style="top: 20px; left: 20px;">
  <img src="https://i.imgur.com/rGLvF3z.gif" class="sparkle" style="top: 80px; right: 20px;">
</body>
</html>
