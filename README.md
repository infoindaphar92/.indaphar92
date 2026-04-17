<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mon Site Pharma</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- HEADER -->
  <header>
    <div class="logo">MonPharma</div>
    <nav>
      <ul>
        <li><a href="#">Accueil</a></li>
        <li><a href="#">Gallery</a></li>
        <li><a href="#">Nos produits</a></li>
        <li><a href="#">Commande en ligne</a></li>
      </ul>
    </nav>
  </header>

  <!-- SECTION ACCUEIL -->
  <section class="hero">
    <h1>Bienvenue chez MonPharma</h1>
    <p>Votre partenaire de confiance pour des médicaments de qualité.</p>
  </section>

  <!-- SECTION PRODUITS -->
  <section class="produits">
    <h2>Nos Produits</h2>
    <div class="grid">
      <div class="card">
        <img src="images/produit1.jpg" alt="Produit 1">
        <h3>Produit 1</h3>
        <p>Description courte du produit.</p>
      </div>
      <div class="card">
        <img src="images/produit2.jpg" alt="Produit 2">
        <h3>Produit 2</h3>
        <p>Description courte du produit.</p>
      </div>
      <div class="card">
        <img src="images/produit3.jpg" alt="Produit 3">
        <h3>Produit 3</h3>
        <p>Description courte du produit.</p>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <p>&copy; 2026 MonPharma. Tous droits réservés.</p>
    <ul>
      <li><a href="#">Termes et conditions</a></li>
      <li><a href="#">Politique de confidentialité</a></li>
      <li><a href="#">Mentions légales</a></li>
    </ul>
  </footer>
</body>
</html>
/* style.css */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background: #e6007e;
  color: white;
  display: flex;
  justify-content: space-between;
  padding: 15px 30px;
}

header .logo {
  font-weight: bold;
  font-size: 1.2em;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav a {
  color: white;
  text-decoration: none;
}

.hero {
  background: #f2f2f2;
  text-align: center;
  padding: 60px 20px;
}

.produits {
  padding: 40px 20px;
}

.produits .grid {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
}

.card {
  background: white;
  border: 1px solid #ddd;
  padding: 20px;
  flex: 1;
  min-width: 200px;
  text-align: center;
}

.card img {
  max-width: 100%;
  height: auto;
}

footer {
  background: #333;
  color: white;
  text-align: center;
  padding: 20px;
}

footer ul {
  list-style: none;
  padding: 0;
}

footer ul li {
  display: inline;
  margin: 0 10px;
}

footer a {
  color: white;
  text-decoration: none;
}
