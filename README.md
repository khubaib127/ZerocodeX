<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CodeNova | AI Coding Platform</title>

  <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Space Grotesk', sans-serif;
    }

    body {
      background: #0A0E27;
      color: white;
      line-height: 1.6;
    }

    /* NAV */
    nav {
      position: fixed;
      width: 100%;
      top: 0;
      left: 0;
      display: flex;
      justify-content: space-between;
      padding: 20px 8%;
      background: rgba(10,14,39,0.9);
      backdrop-filter: blur(10px);
      z-index: 1000;
    }

    .logo {
      font-weight: 700;
      font-size: 20px;
    }

    .nav-links {
      display: flex;
      gap: 20px;
      list-style: none;
    }

    .nav-links a {
      color: #aaa;
      text-decoration: none;
    }

    /* HERO */
    .hero {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 0 20px;
    }

    .hero h1 {
      font-size: 48px;
      margin-bottom: 15px;
    }

    .hero p {
      color: #aaa;
      max-width: 600px;
    }

    .btn {
      margin-top: 20px;
      padding: 12px 20px;
      background: #0066FF;
      border: none;
      border-radius: 8px;
      color: white;
      cursor: pointer;
      text-decoration: none;
      display: inline-block;
    }

    /* FEATURES */
    .features {
      padding: 80px 8%;
      text-align: center;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      margin-top: 40px;
    }

    .card {
      background: #111833;
      padding: 20px;
      border-radius: 12px;
    }

    /* FOOTER */
    footer {
      text-align: center;
      padding: 30px;
      color: #777;
    }
  </style>
</head>

<body>

  <!-- NAV -->
  <nav>
    <div class="logo">CodeNova</div>
    <ul class="nav-links">
      <li><a href="#">Home</a></li>
      <li><a href="#features">Features</a></li>
    </ul>
  </nav>

  <!-- HERO -->
  <section class="hero">
    <h1>AI Powered Coding Platform</h1>
    <p>Build, run and learn coding with a modern developer experience.</p>
    <a class="btn" href="#features">Get Started</a>
  </section>

  <!-- FEATURES -->
  <section id="features" class="features">
    <h2>Features</h2>

    <div class="grid">
      <div class="card">⚡ Fast Code Execution</div>
      <div class="card">🤖 AI Assistant</div>
      <div class="card">🌐 Multi Language Support</div>
      <div class="card">🎨 Clean UI</div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    © 2026 CodeNova. All rights reserved.
  </footer>

</body>
</html>
npm i @vercel/speed-insights
import { SpeedInsights } from "@vercel/speed-insights/next"
