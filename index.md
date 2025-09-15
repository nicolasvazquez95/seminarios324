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
    <title>GitHub Page with Dark/Light Toggle</title>
    <style>
        :root {
            --bg-color: #ffffff;
            --text-color: #333333;
            --header-bg: #f5f5f5;
        }

        [data-theme="dark"] {
            --bg-color: #1a1a1a;
            --text-color: #f0f0f0;
            --header-bg: #2d2d2d;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        header {
            background-color: var(--header-bg);
            padding: 1rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .theme-toggle {
            background: none;
            border: none;
            cursor: pointer;
            font-size: 1.5rem;
            padding: 0.5rem;
            border-radius: 50%;
            width: 2.5rem;
            height: 2.5rem;
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: var(--bg-color);
            color: var(--text-color);
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }

        .container {
            max-width: 800px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        /* Additional styling for content */
        h1, h2, h3 {
            color: var(--text-color);
        }
    </style>
</head>
<body>
    <header>
        <h1>My GitHub Page</h1>
        <button class="theme-toggle" id="theme-toggle" aria-label="Toggle dark/light mode">
            🌙
        </button>
    </header>
    
    <div class="container">
        <h2>Welcome to My Page</h2>
        <p>This is an example GitHub page with a dark/light mode toggle button.</p>
        <p>Click the button in the top right to switch between themes!</p>
    </div>

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