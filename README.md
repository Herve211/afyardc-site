# afyardc-site<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Afya RDC</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f5f8fb;
      color: #333;
    }

    header {
      background-color: #0057a8;
      color: white;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      margin: 0;
      font-size: 1.5rem;
    }

    nav a {
      color: white;
      margin-left: 1.5rem;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      text-align: center;
      padding: 4rem 1rem;
      background-color: #e8f0fe;
    }

    .hero h2 {
      color: #0057a8;
      font-size: 2rem;
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.2rem;
      color: #333;
      max-width: 700px;
      margin: 0 auto;
    }

    .content {
      padding: 2rem 1rem;
      max-width: 900px;
      margin: 0 auto;
    }

    .content h3 {
      color: #0057a8;
      margin-top: 2rem;
    }

    footer {
      background-color: #0057a8;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 4rem;
    }

    @media (max-width: 600px) {
      nav a {
        display: block;
        margin: 0.5rem 0;
      }

      header {
        flex-direction: column;
        align-items: flex-start;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Afya RDC</h1>
    <nav>
      <a href="#mission">Mission</a>
      <a href="#vision">Vision</a>
      <a href="#objectifs">Objectifs</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>La santé, notre droit. L’information, notre force.</h2>
    <p>Bienvenue sur Afya RDC, votre portail numérique dédié à l'information sanitaire accessible et fiable pour tous les citoyens de la République Démocratique du Congo.</p>
  </section>

  <section class="content" id="mission">
    <h3>Notre Mission</h3>
    <p>Afya RDC vise à lutter contre les inégalités d’accès à l’information sanitaire en RDC en mettant à disposition du grand public une plateforme éducative, fiable et gratuite sur les questions de santé. Notre objectif est de renforcer l’autonomie sanitaire des populations en leur offrant les outils nécessaires pour comprendre, prévenir et réagir face aux problèmes de santé courants.</p>
  </section>

  <section class="content" id="vision">
    <h3>Notre Vision</h3>
    <p>Créer un réseau d’éducation santé digital à travers le pays, capable d’atteindre chaque coin du territoire, en particulier les milieux semi-urbains et ruraux, pour bâtir une génération informée, consciente et engagée pour sa propre santé.</p>
  </section>

  <section class="content" id="objectifs">
    <h3>Nos Objectifs Spécifiques</h3>
    <ul>
      <li>Offrir une base de données vulgarisée sur les maladies courantes.</li>
      <li>Promouvoir la santé des femmes, en particulier en âge de procréer.</li>
      <li>Sensibiliser sur les gestes simples de prévention.</li>
      <li>Faciliter l’orientation vers des structures de santé fiables.</li>
      <li>Combattre la désinformation et les croyances néfastes en matière de santé.</li>
    </ul>
  </section>

  <section class="content" id="contact">
    <h3>Contact</h3>
    <p>Une équipe dédiée travaille en coulisses pour mettre à jour le site, écouter vos retours, et répondre à vos besoins d'information. Une boîte de contact sera bientôt disponible.</p>
  </section>

  <footer>
    © 2025 Afya RDC. Tous droits réservés.
  </footer>

</body>
</html>
