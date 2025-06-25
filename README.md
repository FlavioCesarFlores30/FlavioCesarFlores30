<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>I Am Atomic - GitHub</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=UnifrakturCook:wght@700&display=swap');

    body {
      margin: 0;
      padding: 0;
      background: radial-gradient(circle, #0a0a0a 0%, #000000 100%);
      color: #e0d4ff;
      font-family: 'Segoe UI', sans-serif;
      overflow-x: hidden;
    }

    header {
      text-align: center;
      padding: 4rem 2rem;
      background: linear-gradient(145deg, #1a0033 0%, #0a001a 100%);
      animation: pulse 5s infinite alternate;
    }

    h1 {
      font-family: 'UnifrakturCook', cursive;
      font-size: 4rem;
      color: #c084fc;
      text-shadow: 0 0 15px #a855f7, 0 0 40px #7e22ce;
    }

    p.tagline {
      font-style: italic;
      font-size: 1.3rem;
      color: #ccc;
      margin-top: -1rem;
      text-shadow: 0 0 8px #6b21a8;
    }

    .section {
      max-width: 900px;
      margin: 2rem auto;
      padding: 2rem;
      background: rgba(30, 0, 60, 0.25);
      border: 1px solid #4c1d95;
      border-radius: 20px;
      box-shadow: 0 0 25px #7c3aed33;
      backdrop-filter: blur(4px);
    }

    .section h2 {
      color: #f0abfc;
      border-bottom: 1px solid #a855f7;
      padding-bottom: 0.4rem;
      font-size: 1.8rem;
    }

    .section ul {
      list-style: none;
      padding: 0;
    }

    .section li::before {
      content: "⫸ ";
      color: #9333ea;
    }

    a {
      color: #c084fc;
      text-decoration: none;
      transition: 0.3s;
    }

    a:hover {
      text-shadow: 0 0 10px #f0abfc;
    }

    footer {
      text-align: center;
      padding: 2rem;
      color: #666;
      font-size: 0.9rem;
    }

    @keyframes pulse {
      0% { background-color: #0a001a; }
      100% { background-color: #1a0033; }
    }

    .glow-box {
      border: 1px solid #a855f7;
      padding: 1rem;
      border-radius: 12px;
      background: rgba(0, 0, 0, 0.4);
      box-shadow: 0 0 20px #9333ea88;
      animation: glow 4s ease-in-out infinite alternate;
    }

    @keyframes glow {
      from {
        box-shadow: 0 0 5px #9333ea44;
      }
      to {
        box-shadow: 0 0 25px #9333ea;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>I AM ATOMIC</h1>
    <p class="tagline">The Shadow who rules this code domain</p>
  </header>

  <div class="section glow-box">
    <h2>🧠 Who Am I?</h2>
    <p>I am the one who works in silence, who watches from the depths. I build, I destroy, I code — not for fame, but for power.</p>
  </div>

  <div class="section">
    <h2>🔥 My Arsenal</h2>
    <ul>
      <li>JavaScript (Stealth Edition)</li>
      <li>Python (Dark Mode Activated)</li>
      <li>Rust (Silent but Deadly)</li>
      <li>Linux Sorcery</li>
      <li>Shadow DevOps Rituals</li>
    </ul>
  </div>

  <div class="section glow-box">
    <h2>📦 My Projects</h2>
    <p>My creations are weapons forged in silence.<br>
    <a href="https://github.com/TU_USUARIO" target="_blank">See my repositories</a></p>
  </div>

  <div class="section">
    <h2>📜 Quote</h2>
    <p><em>"No one notices a shadow… until it consumes the light."</em></p>
  </div>

  <footer>
    Crafted from the shadows by <strong>@TU_USUARIO</strong><br>
    May the code serve your dominion.
  </footer>

</body>
</html>
