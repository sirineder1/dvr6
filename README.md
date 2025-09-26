<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pâtisserie sirine</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    .navbar {
      background: #E69DB8;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 50px;
    }
    .navbar .logo {
      font-size: 22px;
      font-weight: bold;
      color: #E53888;
    }
    .nav-links {
      list-style: none;
      display: flex;
      gap: 20px;
    }
    .nav-links a {
      text-decoration: none;
      color: #BE5985;
      font-weight: bold;
    }
    .nav-links a:hover {
      color: #BE5985;
    }    
    .hero {
      color: #E53888;
      text-align: center;
      padding: 100px 20px;
    }
    .hero h2 {
      font-size: 40px;
    }
    .hero p {
      font-size: 20px;
      margin-top: 10px;
    }

    
    .choisir {
      padding: 50px 20px;
      text-align: center;
      color: #E53888;
    }
    .cards {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 30px;
      flex-wrap: wrap;
    }
    .card {
      background: #FFEDFA;
      border-radius: 15px;
      padding: 20px;
      width: 250px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    .card img {
      width: 100%;
      border-radius: 10px;
    }

    
    .galerie {
      padding: 50px 20px;
      text-align: center;
      color: #E53888;
    }
    .galerie .images {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 15px;
      margin-top: 30px;
    }
    .galerie img {
      border-radius: 15px;
      width: 200px;
      height: 200px;
      object-fit: cover;
    }

    
    .commande {
      padding: 50px 20px;
      text-align: center;
      color: #E53888;
    }
    .commande form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 400px;
      margin: auto;
    }
    .commande input, .commande select, .commande textarea {
      padding: 10px;
      border-radius: 10px;
      border: 1px solid #ccc;
    }
    .commande button {
      padding: 12px;
      background: #E53888;
      color: white;
      border: none;
      border-radius: 10px;
      font-weight: bold;
      cursor: pointer;
    }
    .commande button:hover {
      background: #E53888;
    }

    
    footer {
      background: #E69DB8;
      color: #BE5985;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
  </style>
</head>
<body>

 
  <header>
    <div class="navbar">
      <h1 class="logo">Pâtisserie sirine</h1>
      <div class="nav-links">
        <a href="#accueil">Accueil</a>
        <a href="#apropos">À propos</a>
        <a href="#galerie">Galerie</a>
        <a href="#commande">Commande</a>
      </div>
    </div>
  </header>

  
  <div id="accueil" class="hero">
    <h2>Bienvenue dans notre univers sucré 🍩</h2>
    <p>Des gâteaux faits avec amour pour chaque occasion.</p>
  </div>

  
  <div id="apropos" class="choisir">
    <h2>Pourquoi nous choisir ?</h2>
    <div class="cards">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1627308595229-7830a5c91f9f?auto=format&fit=crop&w=800&q=80" alt="Artisan Breads">
        <h3>Artisan Breads</h3>
        <p>Pains faits maison, croûte croustillante et mie moelleuse.</p>
      </div>
      <div class="card">
        <img src="https://media.istockphoto.com/id/497959594/fr/photo/des-g%C3%A2teaux.webp?a=1&b=1&s=612x612&w=0&k=20&c=YZeb7r0NaatJoQMdsVMdZZQBsob8yIlVRTtwrf_F6PQ=" alt="Sweet Pastries">
        <h3>Sweet Pastries</h3>
        <p>Viennoiseries légères, sucrées et fondantes en bouche.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1578985545062-69928b1d9587?auto=format&fit=crop&w=800&q=80" alt="Custom Cakes">
        <h3>Custom Cakes</h3>
        <p>Personnalisez vos gâteaux pour toutes les occasions.</p>
      </div>
    </div>
</div>

  
  <div id="galerie" class="galerie">
    <h2>Visit Us Today</h2>
    <div class="images">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRVSl80yDK0X5XBdDujMzDFxphsu56QoDlJrA&s" alt="cupcake">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSOSDwqfFv7B8yMF_EYJwln6_-qf2dyKuvwNg&s" alt="dessert">
      <img src="data:image/jpeg;base64,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" alt="Pain">
      <img src="https://www.cakesparadise.fr/wp-content/uploads/2023/06/26-garnitures-de-croissants-pour-une-patisserie-parfaite..jpg" alt="Croissant"> 
  </div>
  </div>
 
  <div id="commande" class="commande">
    <h2>Passez votre commande</h2>
    <form>
      <input type="text" placeholder="Nom" required>
      <input type="email" placeholder="Email" required>
      <select required>
        <option>Choisissez un produit</option>
        <option>Gâteau</option>
        <option>Croissant</option>
        <option>Pain</option>
      </select>
      <input type="number" placeholder="Quantité" min="1" required>
      <textarea placeholder="Message"></textarea>
      <button type="submit">Commander</button>
    </form>
  </div>

  
  <footer>
    <p>© 2025 Pâtisserie Gourmande - Réalisé par ab informatique</p>
  </footer>

</body>
</html>
