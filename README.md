<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>treff_inclan - Vêtements en ligne</title>
  <style>
    /* Styles généraux */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    
    /* En-tête */
    header {
      background-color: #333;
      padding: 20px;
      color: #fff;
      text-align: center;
    }
    
    h1 {
      font-size: 36px;
      margin: 0;
    }
    
    /* Menu de navigation */
    nav ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    
    nav ul li {
      display: inline-block;
      margin-right: 20px;
    }
    
    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-size: 18px;
    }
    
    /* Section principale */
    main {
      padding: 40px;
    }
    
    h2 {
      font-size: 24px;
      margin-bottom: 10px;
    }
    
    p {
      margin-top: 0;
    }
    
    /* Pied de page */
    footer {
      background-color: #333;
      padding: 20px;
      color: #fff;
      text-align: center;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    <h1>treff_inclan</h1>
    <nav>
      <ul>
        <li><a href="#">Accueil</a></li>
        <li><a href="#">Collections</a></li>
        <li><a href="#">Promotions</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>
  
  <main>
    <section>
      <h2>Nouvelles collections</h2>
      <p>Découvrez nos dernières collections de vêtements tendance.</p>
    </section>
    
    <section>
      <h2>Promotions</h2>
      <p>Profitez de nos offres spéciales et économisez sur vos achats.</p>
    </section>
    
    <section>
      <h2>Contactez-nous</h2>
      <p>Nous sommes là pour répondre à toutes vos questions.</p>
      <form>
        <label for="name">Nom :</label>
        <input type="text" id="name" name="name" required>
        <br>
        <label for="email">Email :</label>
        <input type="email" id="email" name="email" required>
        <br>
        <label for="message">Message :</label>
        <textarea id="message" name="message" required></textarea>
        <br>
        <button type="submit">Envoyer</button>
      </form>
    </section>
  </main>
  
  <footer>
    <


