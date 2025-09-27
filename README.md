<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bienvenido a mi GitHub 🚀</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0d1117;
      --card:#161b22;
      --text:#c9d1d9;
      --muted:#8b949e;
      --accent:#58a6ff;
      --radius:14px;
    }
    *{box-sizing:border-box;margin:0;padding:0;font-family:'Inter',sans-serif}
    body{background:var(--bg);color:var(--text);line-height:1.6;}
    header{padding:20px;text-align:center;}
    header h1{font-size:2rem;color:var(--accent)}
    header p{color:var(--muted)}

    .hero{display:flex;flex-direction:column;align-items:center;justify-content:center;padding:40px 20px;text-align:center}
    .hero img{border-radius:50%;width:140px;height:140px;margin-bottom:20px;border:3px solid var(--accent)}
    .hero h2{margin-bottom:10px}
    .hero p{max-width:600px;color:var(--muted)}

    .links{margin-top:20px;display:flex;gap:15px;flex-wrap:wrap;justify-content:center}
    .links a{padding:10px 18px;border-radius:var(--radius);background:var(--accent);color:#fff;text-decoration:none;font-weight:600;transition:0.2s}
    .links a:hover{opacity:0.85}

    section{max-width:1000px;margin:40px auto;padding:0 20px}
    h3{margin-bottom:12px;color:var(--accent)}
    .projects{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:20px}
    .card{background:var(--card);padding:20px;border-radius:var(--radius);transition:0.2s;box-shadow:0 4px 12px rgba(0,0,0,0.2)}
    .card:hover{transform:translateY(-4px)}
    .card h4{margin-bottom:10px}
    .card p{color:var(--muted);font-size:14px}

    footer{text-align:center;color:var(--muted);padding:20px;margin-top:40px;border-top:1px solid #21262d}
    @media(max-width:600px){
      .hero img{width:100px;height:100px}
      header h1{font-size:1.6rem}
    }
  </style>
</head>
<body>
  <header>
    <h1>👋 ¡Hola, soy [Ely]!</h1>
    <p>Desarrollador | Open Source | Tech Enthusiast</p>
  </header>

  <section class="hero">
    <img src="https://avatars.githubusercontent.com/u/9919?s=280&v=4" alt="Avatar">
    <h2>Bienvenido a mi GitHub</h2>
    <p>Aquí comparto mis proyectos, ideas y experimentos. Me apasiona crear soluciones útiles y aprender tecnologías nuevas 🚀</p>
    
  </section>


<section id="contacto">
    <h3>📬 Contáctame</h3>
    <p>Lindkedin: <a href="www.linkedin.com/in/elisabeth-bargallo-ortiz-b7a130329" style="color:var(--accent)">www.linkedin.com/in/elisabeth-bargallo-ortiz-b7a130329</a></p>
  </section>

  <footer>
    <p>© <span id="year"></span> [Elisabeth]. Creado con ❤️ y GitHub Pages.</p>
  </footer>

  
</body>
</html>

