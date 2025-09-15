---
layout: home
title: ""
list_title: "Blog"
---
<!-- Add an image from assets folder  -->
<input type="text" id="search-input" placeholder="Buscar seminarios...">
<ul id="results-container"></ul>

![Flyer1]({{ '/assets/flyer1.png' | relative_url }})

Aquí vas a encontrar la información sobre el próximo seminario y un archivo de los seminarios anteriores.

## 📢 Próximo seminario
<!-- Template (no me borres): -->
<!-- <div style="background:#2c2c2c; border-left:5px solid #4fc3f7; border-radius:12px; padding:1.2em; margin:1.5em 0; color:#e0e0e0; font-family: sans-serif; box-shadow: 0 4px 10px rgba(0,0,0,0.5);">
  <h3><em style="color:#4fc3f7; font-size:1.5em;">Título de seminario a confirmar</em></h3>
  <p><strong>Orador:</strong> Paula Céspedes (IFEG-FAMAF)</p>
  <p>🗓️ <strong>Viernes 12 de septiembre, 14:00 hs</strong><br>
     📍 Of. 324 – FAMAF</p>
  <p><strong>Resumen:</strong><br>
     Estén atentos a las novedades que se publicarán próximamente.
  </p>
</div> -->

<div style="background:#2c2c2c; border-left:5px solid #4fc3f7; border-radius:12px; padding:1.2em; margin:1.5em 0; color:#e0e0e0; font-family: sans-serif; box-shadow: 0 4px 10px rgba(0,0,0,0.5);">
  <h3><em style="color:#4fc3f7; font-size:1.5em;">Título de seminario a confirmar</em></h3>
  <p><strong>Orador:</strong> Diego Reyes (CIEM-FAMAF)</p>
  <p>🗓️ <strong>Viernes 19 de septiembre, 14:00 hs</strong><br>
     📍 Of. 324 – FAMAF</p>
  <p><strong>Resumen:</strong><br>
     Estén atentos a las novedades que se publicarán próximamente.
  </p>
</div>


## 📂 Resúmenes de seminarios anteriores
<!-- Template (no me borres) -->
<!-- <div style="background:#1e1e1e; border-radius:12px; padding:1em; margin:1em 0; color:#e0e0e0; font-family: sans-serif;">
  <h3><em style="color:#4fc3f7;">Título del seminario</em></h3>
  <p><strong>Orador:</strong> Nombre del orador (Grupo-Instituto)</p>
  <p>🗓️ <strong>Fecha, Hora</strong><br>
     📍 Of. 324 – FAMAF</p>
  <p><strong>Resumen:</strong><br>
    Aquí va el resumen del seminario.
  </p>
</div> -->

<div style="background:#1e1e1e; border-radius:12px; padding:1em; margin:1em 0; color:#e0e0e0; font-family: sans-serif;">
  <h3><em style="color:#4fc3f7;">De Argentina vs el Dream Team y nuestros grados de separación con Michael Jordan</em></h3>
  <p><strong>Oradora:</strong> Paula Céspedes (IFEG-FAMAF)</p>
  <p>🗓️ <strong>Viernes 12 de septiembre, 14 hs</strong><br>
     📍 Of. 324 – FAMAF</p>
  <p><strong>Resumen:</strong><br>
     En este seminario recordaremos el mítico enfrentamiento de la Selección Argentina de Básquet vs el Dream Team de Estados Unidos en el Preolímpico de 1992 y charlaremos brevemente de lo que significó el Oro Olímpico de Argentina en Atenas 2004. Descubriremos también cuántos grados de separación o handshakes nos distancian de Michael Jordan y otras estrellas del básquet.
  </p>
</div>

<div style="background:#1e1e1e; border-radius:12px; padding:1em; margin:1em 0; color:#e0e0e0; font-family: sans-serif;">
  <h3><em style="color:#4fc3f7;">La historia de un guerrero: ISinVidal</em></h3>
  <p><strong>Orador:</strong> Jonathan Claros (IFEG-FAMAF)</p>
  <p>🗓️ <strong>Viernes 5 de septiembre, 14:00 hs</strong><br>
     📍 Of. 324 – FAMAF</p>
  <p><strong>Resumen:</strong><br>
     Esta es la historia de un militar que, cansado de tanta maldad, encontró un refugio. En su camino, se enfrentó a las potencias mundiales que dominaban la época, encontrando aliados en un grupo que compartía sus ideales. Así, pudo transmitir su sabiduría y eventualmente, asumir el liderazgo. Tras tres años intensos y decisivos, comprendió que su ciclo en esta vida difícil había llegado a su fin. Esta es la biografía de ISinVidal (2011-2014).
  </p>
</div>

***Para ver el archivo completo de resúmenes, hacé click [aquí]({{ '/archivo/' | relative_url }}).***

## ✉️ Suscribite
<div style="text-align: center; margin-top: 1.5em;">
      <p>📩 Sumate a la lista de difusión para estar atento al próximo seminario</p>
      <a href="https://forms.gle/rpGbTqEZgYM9etnn8" target="_blank" rel="noopener">
        <img src="{{ '/assets/img/qr-form.jpeg' | relative_url }}" 
             alt="QR para sumarte a la lista de difusión" 
             style="max-width: 150px; border-radius: 8px;">
      </a>
      <p><small>Escaneá el código o tocá la imagen</small></p>
    </div>


  <script src="https://cdn.jsdelivr.net/npm/simple-jekyll-search@1.10.0/dest/simple-jekyll-search.min.js"></script>
  <script>
    SimpleJekyllSearch({
      searchInput: document.getElementById('search-input'),
      resultsContainer: document.getElementById('results-container'),
      json: '{{ "/search.json" | relative_url }}',
      searchResultTemplate: '<li><a href="{url}">{title}</a><br><small>{date}</small><br>{content}</li>',
      noResultsText: 'No se encontraron resultados',
      limit: 10,
      fuzzy: false,
    })
  </script>


  <!-- probando light and dark mode -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Page with Theme Toggle</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        :root {
            --primary-color: #6e5494;
            --bg-color: #ffffff;
            --text-color: #333333;
            --card-bg: #f6f8fa;
            --header-bg: #f5f5f5;
            --border-color: #e1e4e8;
            --shadow-color: rgba(0, 0, 0, 0.1);
        }
        
        [data-theme="dark"] {
            --primary-color: #8c63c7;
            --bg-color: #1a1a1a;
            --text-color: #f0f0f0;
            --card-bg: #2d2d2d;
            --header-bg: #242424;
            --border-color: #444444;
            --shadow-color: rgba(0, 0, 0, 0.4);
        }
        
        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
            line-height: 1.6;
            transition: background-color 0.3s ease, color 0.3s ease;
        }
        
        header {
            background-color: var(--header-bg);
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 10px var(--shadow-color);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 12px;
            font-weight: 600;
            color: var(--primary-color);
        }
        
        .logo img {
            width: 40px;
            height: 40px;
        }
        
        .nav-links {
            display: flex;
            gap: 1.5rem;
        }
        
        .nav-links a {
            text-decoration: none;
            color: var(--text-color);
            font-weight: 500;
            transition: color 0.3s;
        }
        
        .nav-links a:hover {
            color: var(--primary-color);
        }
        
        .theme-toggle {
            background: none;
            border: none;
            cursor: pointer;
            font-size: 1.5rem;
            padding: 0.5rem;
            border-radius: 50%;
            width: 2.8rem;
            height: 2.8rem;
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: var(--card-bg);
            color: var(--text-color);
            box-shadow: 0 2px 5px var(--shadow-color);
            transition: transform 0.3s;
        }
        
        .theme-toggle:hover {
            transform: scale(1.1);
        }
        
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1.5rem;
        }
        
        .hero {
            text-align: center;
            padding: 3rem 1rem;
            margin-bottom: 2rem;
        }
        
        .hero h1 {
            font-size: 2.8rem;
            margin-bottom: 1rem;
            color: var(--primary-color);
        }
        
        .hero p {
            font-size: 1.2rem;
            max-width: 700px;
            margin: 0 auto;
            color: var(--text-color);
            opacity: 0.9;
        }
        
        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 3rem;
        }
        
        .card {
            background-color: var(--card-bg);
            border-radius: 10px;
            padding: 1.5rem;
            box-shadow: 0 4px 6px var(--shadow-color);
            border: 1px solid var(--border-color);
        }
        
        .card h3 {
            color: var(--primary-color);
            margin-bottom: 1rem;
            font-size: 1.4rem;
        }
        
        .card p {
            color: var(--text-color);
            opacity: 0.9;
        }
        
        footer {
            text-align: center;
            padding: 2rem;
            margin-top: 3rem;
            background-color: var(--header-bg);
            color: var(--text-color);
            border-top: 1px solid var(--border-color);
        }
        
        @media (max-width: 768px) {
            header {
                padding: 1rem;
            }
            
            .nav-links {
                display: none;
            }
            
            .hero h1 {
                font-size: 2.2rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">
            <svg width="40" height="40" viewBox="0 0 16 16" fill="currentColor">
                <path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"/>
            </svg>
            <span>GitHub Page</span>
        </div>
        
        <nav class="nav-links">
            <a href="#">Home</a>
            <a href="#">Projects</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </nav>
        
        <button class="theme-toggle" id="theme-toggle" aria-label="Toggle dark/light mode">
            🌙
        </button>
    </header>
    
    <div class="container">
        <section class="hero">
            <h1>Welcome to My GitHub Page</h1>
            <p>This is a demonstration of a simple dark/light mode toggle button that you can easily add to your GitHub page. The toggle is located in the header for easy access.</p>
        </section>
        
        <section class="features">
            <div class="card">
                <h3>Easy to Implement</h3>
                <p>Just copy the HTML, CSS, and JavaScript code into your GitHub page. The toggle button uses emojis for a clean, universal design.</p>
            </div>
            
            <div class="card">
                <h3>User Preference</h3>
                <p>The toggle remembers the user's selection using localStorage, so their theme preference is saved between visits.</p>
            </div>
            
            <div class="card">
                <h3>Responsive Design</h3>
                <p>The layout adapts to different screen sizes, making it look great on both desktop and mobile devices.</p>
            </div>
        </section>
    </div>
    
    <footer>
        <p>© 2023 GitHub Page Example. All rights reserved.</p>
    </footer>

    <script>
        const toggleButton = document.getElementById('theme-toggle');
        const prefersDarkScheme = window.matchMedia('(prefers-color-scheme: dark)');
        
        // Check for saved theme preference or use system preference
        const currentTheme = localStorage.getItem('theme') || 
                            (prefersDarkScheme.matches ? 'dark' : 'light');
        
        // Set initial theme
        if (currentTheme === 'dark') {
            document.body.setAttribute('data-theme', 'dark');
            toggleButton.textContent = '☀️';
        } else {
            document.body.removeAttribute('data-theme');
            toggleButton.textContent = '🌙';
        }
        
        // Toggle theme when button is clicked
        toggleButton.addEventListener('click', () => {
            let theme = 'light';
            if (!document.body.getAttribute('data-theme')) {
                theme = 'dark';
                document.body.setAttribute('data-theme', 'dark');
                toggleButton.textContent = '☀️';
            } else {
                document.body.removeAttribute('data-theme');
                toggleButton.textContent = '🌙';
            }
            localStorage.setItem('theme', theme);
        });
    </script>
</body>
</html>