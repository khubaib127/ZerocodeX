<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CodeNova | AI-Powered Coding Platform</title>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500;600&display=swap" rel="stylesheet">

    <style>
        :root {
            --primary: #0A0E27;
            --secondary: #0066FF;
            --accent: #00F0FF;
            --accent-2: #8B5CF6;
            --text: #FFFFFF;
            --text-muted: #94A3B8;
            --surface: #0F172A;
            --surface-light: #1E293B;
            --gradient-1: linear-gradient(135deg, #0066FF 0%, #8B5CF6 100%);
            --gradient-2: linear-gradient(135deg, #00F0FF 0%, #0066FF 100%);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Space Grotesk', sans-serif;
            background: var(--primary);
            color: var(--text);
            overflow-x: hidden;
            line-height: 1.6;
        }

        /* NAV */
        nav {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            padding: 1.5rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 1000;
            background: rgba(10, 14, 39, 0.8);
            backdrop-filter: blur(20px);
        }

        .logo {
            display: flex;
            gap: 0.75rem;
            font-size: 1.5rem;
            font-weight: 700;
        }

        .nav-links {
            display: flex;
            gap: 2rem;
            list-style: none;
        }

        .nav-links a {
            color: var(--text-muted);
            text-decoration: none;
        }

        /* HERO */
        .hero {
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            text-align: center;
            padding: 8rem 5% 4rem;
        }

        .hero h1 {
            font-size: 4rem;
        }

        .hero p {
            color: var(--text-muted);
            margin-top: 1rem;
        }

        /* FEATURES */
        .features {
            padding: 6rem 5%;
        }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
        }

        .feature-card {
            background: var(--surface);
            padding: 2rem;
            border-radius: 16px;
        }

        /* BRAND */
        .brand-names {
            padding: 6rem 5%;
            background: var(--surface);
        }

        .brand-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 1.5rem;
        }

        .brand-item {
            background: var(--primary);
            padding: 1.5rem;
            border-radius: 12px;
        }

        /* VISUAL IDENTITY */
        .visual-identity {
            padding: 6rem 5%;
        }

        .identity-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .identity-card {
            background: var(--surface);
            padding: 2rem;
            border-radius: 16px;
        }

        /* FIXED BLOCK (your error was here) */
        .color-swatches {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 1rem;
        }

        .swatch {
            height: 50px;
            border-radius: 8px;
        }

        .swatch:nth-child(1) { background: #0066FF; }
        .swatch:nth-child(2) { background: #00F0FF; }
        .swatch:nth-child(3) { background: #8B5CF6; }
        .swatch:nth-child(4) { background: #0F172A; }

    </style>
</head>

<body>

<!-- NAV -->
<nav>
    <div class="logo">CodeNova</div>
    <ul class="nav-links">
        <li><a href="#">Home</a></li>
        <li><a href="#">Features</a></li>
        <li><a href="#">Brands</a></li>
    </ul>
</nav>

<!-- HERO -->
<section class="hero">
    <h1>AI-Powered Coding Platform</h1>
    <p>Build, run, and learn coding in one modern interface.</p>
</section>

<!-- FEATURES -->
<section class="features">
    <div class="features-grid">
        <div class="feature-card">Run HTML instantly</div>
        <div class="feature-card">AI Code Assistant</div>
        <div class="feature-card">Multi-language support</div>
    </div>
</section>

<!-- BRAND -->
<section class="brand-names">
    <div class="brand-grid">
        <div class="brand-item">CodeNova AI</div>
        <div class="brand-item">Blackbox Style Editor</div>
        <div class="brand-item">Dev Studio Pro</div>
    </div>
</section>

<!-- VISUAL IDENTITY -->
<section class="visual-identity">
    <div class="identity-grid">

        <div class="identity-card">
            <h3>Color System</h3>
            <div class="color-swatches">
                <div class="swatch"></div>
                <div class="swatch"></div>
                <div class="swatch"></div>
                <div class="swatch"></div>
            </div>
        </div>

    </div>
</section>

</body>
</html>
