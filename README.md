<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Afya RDC</title>

  <!-- Font Awesome pour les icônes -->
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"
    integrity="sha512-..."
    crossorigin="anonymous"
    referrerpolicy="no-referrer"
  />

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f8f9fa;
    }

    header {
      background-color: #007b5e;
      padding: 15px 0;
      color: white;
      text-align: center;
    }

    nav {
      background-color: #004d40;
      display: flex;
      justify-content: center;
      gap: 25px;
      padding: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    main {
      padding: 20px;
    }

    section {
      margin-bottom: 40px;
    }

    h2 {
      color: #007b5e;
    }

    .icon {
      margin-right: 8px;
      color: #007b5e;
    }

    footer {
      background-color: #004d40;
      color: white;
      text-align: center;
      padding: 15px 10px;
      position: relative;
    }

    form {
      max-width: 600px;
      margin: auto;
      background-color: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-top: 8px;
      margin-bottom: 16px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    form button {
      background-color: #007b5e;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }

    form button:hover {
      background-color: #005f4f;
    }
  </style>
</head>
<body>

  <header>
    <h1><i class="fa-solid fa-heart-pulse icon"></i>Afya RDC</h1>
    <p>Pour une population informée et en meilleure santé</p>
  </header>

  <nav>
    <a href="#accueil"><i class="fa-solid fa-house icon"></i>Accueil</a>
    <a href="#apropos"><i class="fa-solid fa-circle-info icon"></i>À propos</a>
    <a href="#objectifs"><i class="fa-solid fa-bullseye icon"></i>Objectifs</a>
    <a href="#contact"><i class="fa-solid fa-envelope icon"></i>Contact</a>
  </nav>

  <main>
    <section id="accueil">
      <h2><i class="fa-solid fa-hand-holding-medical icon"></i>Bienvenue sur Afya RDC</h2>
      <p>Afya RDC est un projet web visant à informer la population congolaise sur les questions de santé courante, en mettant l'accent sur l'éducation, la sensibilisation et l’accès à des informations fiables.</p>
    </section>

    <section id="apropos">
      <h2><i class="fa-solid fa-circle-info icon"></i>À propos</h2>
      <p>Notre plateforme s’adresse à tous, avec un focus particulier sur les femmes en âge de procréer. Nous voulons créer un espace accessible, enrichi de contenus éducatifs, préventifs et interactifs.</p>
    </section>

    <section id="objectifs">
      <h2><i class="fa-solid fa-bullseye icon"></i>Nos objectifs</h2>
      <ul>
        <li>Offrir des fiches d’information simples et fiables sur les maladies fréquentes.</li>
        <li>Faciliter la compréhension du système de santé local (structures, démarches, contacts).</li>
        <li>Encourager les bonnes pratiques de prévention et d'hygiène.</li>
      </ul>
    </section>

    <section id="contact">
      <h2><i class="fa-solid fa-envelope icon"></i>Contactez-nous</h2>
      <form>
        <label for="name">Nom :</label>
        <input type="text" id="name" name="name" placeholder="Votre nom" required>

        <label for="email">Email :</label>
        <input type="email" id="email" name="email" placeholder="Votre email" required>

        <label for="message">Message :</label>
        <textarea id="message" name="message" rows="5" placeholder="Votre message" required></textarea>

        <button type="submit">Envoyer</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Afya RDC. Tous droits réservés.</p>
  </footer>

</body>
</html>
