# Créons un fichier HTML à partir du contenu actuel du site TéléJeux.
html_content = """<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TéléJeux - Jeux PPSSPP et Android</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fff;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #d10000;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    .section {
      padding: 1rem;
    }
    h2 {
      color: #d10000;
    }
    .game {
      border: 1px solid #ccc;
      padding: 1rem;
      margin-bottom: 1rem;
      border-radius: 8px;
    }
    .game img {
      max-width: 100%;
      height: auto;
    }
    .download-btn {
      display: inline-block;
      margin-top: 0.5rem;
      padding: 0.5rem 1rem;
      background-color: #d10000;
      color: white;
      text-decoration: none;
      border-radius: 4px;
    }
  </style>
</head>
<body>
  <header>
    <h1>TéléJeux</h1>
    <p>Télécharge les meilleurs jeux PPSSPP et Android</p>
  </header>

  <div class="section">
    <h2>Jeux PPSSPP</h2>

    <div class="game">
      <h3>God of War: Ghost of Sparta</h3>
      <img src="https://upload.wikimedia.org/wikipedia/en/3/3b/God_of_War_Ghost_of_Sparta.jpg" alt="God of War">
      <p>Un jeu d'action-aventure intense avec Kratos. Compatible PPSSPP.</p>
      <a class="download-btn" href="#">Télécharger</a>
    </div>

    <div class="game">
      <h3>PES 2024 PPSSPP</h3>
      <img src="https://cdn.mobapks.com/wp-content/uploads/2023/10/PES-2024-PPSSPP-300x168.webp" alt="PES 2024">
      <p>Joue au football avec les dernières équipes et transferts.</p>
      <a class="download-btn" href="#">Télécharger</a>
    </div>

    <div class="game">
      <h3>Dragon Ball Z: Shin Budokai</h3>
      <img src="https://i.ytimg.com/vi/3k5fJfdN7rY/maxresdefault.jpg" alt="DBZ Shin Budokai">
      <p>Combats légendaires entre Goku et ses ennemis. Action rapide garantie.</p>
      <a class="download-btn" href="#">Télécharger</a>
    </div>
  </div>

  <div class="section">
    <h2>Jeux Android</h2>

    <div class="game">
      <h3>Subway Surfers</h3>
      <img src="https://play-lh.googleusercontent.com/MGZ3qjqCy8W9MQCVt29JnyvIcmRBIItKW7_m09pg4EqHYwSvlMPDN6mhAsKZ-v4EvA=w526-h296-rw" alt="Subway Surfers">
      <p>Un jeu de course infinie fun et coloré.</p>
      <a class="download-btn" href="#">Télécharger</a>
    </div>

    <div class="game">
      <h3>GTA: San Andreas</h3>
      <img src="https://cdn.cloudflare.steamstatic.com/steam/apps/12120/header.jpg" alt="GTA San Andreas">
      <p>Explore le monde ouvert de San Andreas sur ton téléphone.</p>
      <a class="download-btn" href="#">Télécharger</a>
    </div>

    <div class="game">
      <h3>Free Fire</h3>
      <img src="https://play-lh.googleusercontent.com/VSmXK3acbz9AHaYxRZd-0z5dArhNHhQZn3LywX1AP1oKjxC2wA_FnG0qLZkVPQoM-w=w526-h296-rw" alt="Free Fire">
      <p>Un battle royale dynamique avec des graphismes stylés.</p>
      <a class="download-btn" href="#">Télécharger</a>
    </div>
  </div>
</body>
</html>"""

# Enregistrer le fichier HTML
file_path = "/mnt/data/telejeux.html"
with open(file_path, "w", encoding="utf-8") as f:
    f.write(html_content)

file_path
