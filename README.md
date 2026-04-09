<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portail Média Mauricie</title>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box;}
body{font-family:'Montserrat',sans-serif;background:#f0f0f0;color:#2d2d2d;min-height:100vh;}
.wrap{max-width:960px;margin:0 auto;padding:48px 24px 80px;}

.header{display:flex;align-items:center;justify-content:space-between;margin-bottom:52px;padding-bottom:24px;border-bottom:3px solid #2d2d2d;}
.header-right{text-align:right;}
.header-title{font-size:13px;font-weight:800;letter-spacing:3px;text-transform:uppercase;color:#aaa;}
.header-sub{font-size:11px;font-weight:600;color:#bbb;margin-top:4px;}

.hero{margin-bottom:48px;}
.hero-eyebrow{font-size:11px;font-weight:800;letter-spacing:3px;text-transform:uppercase;color:#c0392b;margin-bottom:14px;}
.hero-title{font-size:52px;font-weight:900;color:#2d2d2d;letter-spacing:-2px;line-height:1;margin-bottom:12px;}
.hero-sub{font-size:14px;font-weight:500;color:#666;line-height:1.7;max-width:560px;}

.section-label{font-size:11px;font-weight:800;letter-spacing:3px;text-transform:uppercase;color:#aaa;margin-bottom:16px;display:flex;align-items:center;gap:12px;}
.section-label::after{content:'';flex:1;height:1px;background:#e0e0e0;}

.cards{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-bottom:40px;}
.card{background:#fff;border:2px solid #e0e0e0;border-radius:14px;padding:22px 20px;text-decoration:none;color:inherit;transition:all 0.2s;display:flex;flex-direction:column;}
.card:hover{border-color:#2d2d2d;transform:translateY(-2px);box-shadow:0 8px 24px rgba(0,0,0,0.08);}
.card.featured{border-color:#c0392b;border-top:4px solid #c0392b;}
.card-icon{font-size:28px;margin-bottom:12px;}
.card-code{font-size:9px;font-weight:800;letter-spacing:2px;text-transform:uppercase;color:#aaa;margin-bottom:6px;}
.card-name{font-size:15px;font-weight:800;color:#2d2d2d;line-height:1.3;margin-bottom:6px;}
.card-desc{font-size:11px;font-weight:500;color:#888;line-height:1.6;flex:1;}
.card-arrow{font-size:12px;font-weight:800;color:#c0392b;margin-top:14px;letter-spacing:1px;}

.card-wide{grid-column:span 2;}

.questionnaire-card{background:#2d2d2d;border:none;color:#fff;}
.questionnaire-card:hover{background:#1a1a1a;border:none;}
.questionnaire-card .card-code{color:rgba(255,255,255,0.35);}
.questionnaire-card .card-name{color:#fff;}
.questionnaire-card .card-desc{color:rgba(255,255,255,0.55);}
.questionnaire-card .card-arrow{color:#c0392b;}

.footer{padding-top:24px;border-top:2px solid #ddd;display:flex;justify-content:space-between;align-items:center;gap:14px;flex-wrap:wrap;}
.footer-legal{font-size:11px;font-weight:500;color:#aaa;line-height:1.8;}
.footer-legal strong{color:#888;}

@media(max-width:640px){
  .cards{grid-template-columns:1fr;}
  .card-wide{grid-column:span 1;}
  .hero-title{font-size:36px;}
  .header{flex-direction:column;align-items:flex-start;gap:12px;}
}
</style>
</head>
<body>
<div class="wrap">

<div class="header">
  <img src="https://mediamauricie.com/wp-content/uploads/2026/03/Media-Mauricie_logo_M-coul.png" alt="Média Mauricie" style="height:48px;width:auto;">
  <div class="header-right">
    <div class="header-title">Portail interne</div>
    <div class="header-sub">Média Mauricie Inc. · 2026</div>
  </div>
</div>

<div class="hero">
  <div class="hero-eyebrow">Documents &amp; contrats</div>
  <div class="hero-title">Ressources<br>de l'équipe.</div>
  <div class="hero-sub">Accès rapide à tous les contrats, offres et outils de qualification client. Usage interne uniquement.</div>
</div>

<div class="section-label">Contrats interactifs</div>
<div class="cards">
  <a href="contrats/MM-PHO.html" class="card">
    <div class="card-icon">📷</div>
    <div class="card-code">MM-PHO</div>
    <div class="card-name">Séance photo unique</div>
    <div class="card-desc">Portraits, équipe, événement, extérieur · 1h à 12h · drone inclus</div>
    <div class="card-arrow">Ouvrir le contrat →</div>
  </a>
  <a href="contrats/MM-EVT.html" class="card featured">
    <div class="card-icon">🎬</div>
    <div class="card-code">MM-EVT</div>
    <div class="card-name">Couverture événementielle</div>
    <div class="card-desc">Photo + vidéo + montages · packages 2h à 12h · clé en main ou à la carte</div>
    <div class="card-arrow">Ouvrir le contrat →</div>
  </a>
  <a href="contrats/MM-VID.html" class="card">
    <div class="card-icon">🎞️</div>
    <div class="card-code">MM-VID</div>
    <div class="card-name">Production vidéo</div>
    <div class="card-desc">Corporatif, voxpop, reel, documentaire · tournages multiples · post-production</div>
    <div class="card-arrow">Ouvrir le contrat →</div>
  </a>
  <a href="contrats/MM-BIMG.html" class="card">
    <div class="card-icon">📸</div>
    <div class="card-code">MM-BIMG</div>
    <div class="card-name">Banque d'images mensuelle</div>
    <div class="card-desc">Shooting mensuel · photos HD · drone · Pixpa · abonnement 3–12 mois</div>
    <div class="card-arrow">Ouvrir le contrat →</div>
  </a>
  <a href="contrats/MM-FCM.html" class="card">
    <div class="card-icon">🎥</div>
    <div class="card-code">MM-FCM</div>
    <div class="card-name">Forfait contenu mensuel</div>
    <div class="card-desc">Photos + reels + drone · 2h ou 4h terrain · abonnement 3–12 mois</div>
    <div class="card-arrow">Ouvrir le contrat →</div>
  </a>
  <a href="contrats/MM-BH.html" class="card">
    <div class="card-icon">💻</div>
    <div class="card-code">MM-BH</div>
    <div class="card-name">Banque d'heures montage</div>
    <div class="card-desc">15h · 25h · 50h · valide 12 mois · tous types de montages · registre de suivi</div>
    <div class="card-arrow">Ouvrir le contrat →</div>
  </a>
</div>

<div class="section-label">Qualification client</div>
<div class="cards">
  <a href="questionnaire.html" class="card questionnaire-card card-wide">
    <div class="card-icon">📋</div>
    <div class="card-code">Formulaire web</div>
    <div class="card-name">Questionnaire de qualification</div>
    <div class="card-desc">Envoyez ce lien au client après le premier contact · Les réponses arrivent directement dans le système · Personnalisable avec ?lead=LEAD-XXX</div>
    <div class="card-arrow">Ouvrir le questionnaire →</div>
  </a>
  <a href="contrats/MM-VID-POST.html" class="card">
    <div class="card-icon">🎨</div>
    <div class="card-code">Offre supplémentaire</div>
    <div class="card-name">Fichiers bruts &amp; colorisation</div>
    <div class="card-desc">Tarifs remise de fichiers bruts selon durée de tournage · banques d'heures colorisation</div>
    <div class="card-arrow">Voir l'offre →</div>
  </a>
</div>

<div class="section-label">Propositions clients</div>
<div class="cards">
  <a href="https://mediamauricie.github.io/ville-de-louiseville/" target="_blank" class="card">
    <div class="card-icon">🏙️</div>
    <div class="card-code">Proposition active</div>
    <div class="card-name">Ville de Louiseville</div>
    <div class="card-desc">Couverture événements commandités · partenariat 2026</div>
    <div class="card-arrow">Voir la proposition →</div>
  </a>
  <a href="https://mediamauricie.github.io/country-pop/" target="_blank" class="card">
    <div class="card-icon">🎵</div>
    <div class="card-code">Proposition active</div>
    <div class="card-name">Country Pop 103.1</div>
    <div class="card-desc">Offre de contenu · partenariat média régional</div>
    <div class="card-arrow">Voir la proposition →</div>
  </a>
  <a href="https://mediamauricie.github.io/master-cowork/" class="card" style="border-style:dashed;background:#fafafa;">
    <div class="card-icon">➕</div>
    <div class="card-code">À venir</div>
    <div class="card-name">Nouvelle proposition</div>
    <div class="card-desc">Microbrasserie Broadway · QDCM Metal Fest · et autres mandats</div>
    <div class="card-arrow" style="color:#aaa;">Bientôt disponible</div>
  </a>
</div>

<div class="footer">
  <img src="https://mediamauricie.com/wp-content/uploads/2026/03/Media-Mauricie_logo_coul.png" alt="Média Mauricie" style="height:32px;width:auto;">
  <div class="footer-legal">
    <strong>Média Mauricie Inc.</strong> · Usage interne · 2026<br>
    info@mediamauricie.com · (819) 852-0851
  </div>
</div>

</div>
</body>
</html>
