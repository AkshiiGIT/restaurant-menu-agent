<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>MenuAI | Version Ultime & Éditable</title>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=DM+Mono:wght@300;400;500&display=swap" rel="stylesheet"/>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jsQR/1.4.0/jsQR.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>
  <style>
    :root { --cream:#F5F0E8;--ink:#1A1410;--gold:#C9A84C;--gold-light:#E8D4A0;--rust:#8B3A2A;--sage:#4A5E4A;--warm-gray:#8A847A;--card-bg:#FDFAF4; }
    *{margin:0;padding:0;box-sizing:border-box;}
    body{background:var(--cream);color:var(--ink);font-family:'Cormorant Garamond',Georgia,serif;min-height:100vh;overflow-x:hidden;}
    header{position:relative;z-index:1;text-align:center;padding:3rem 1rem 0;border-bottom:1px solid var(--gold-light);}
    .logo-line{display:flex;align-items:center;justify-content:center;gap:1rem;margin-bottom:0.5rem;}
    .logo-ornament{width:40px;height:1px;background:linear-gradient(to right,transparent,var(--gold));}
    .logo-ornament.right{background:linear-gradient(to left,transparent,var(--gold));}
    h1{font-size:2.2rem;font-weight:300;letter-spacing:0.15em;}
    h1 span{color:var(--gold);font-style:italic;}
    .tagline{font-family:'DM Mono',monospace;font-size:0.7rem;letter-spacing:0.3em;color:var(--warm-gray);text-transform:uppercase;margin-top:0.5rem;}
    .tabs{display:flex;justify-content:center;max-width:460px;margin:2rem auto 0;border:1px solid var(--gold-light);border-bottom:none;border-radius:2px 2px 0 0;overflow:hidden;}
    .tab{flex:1;padding:0.85rem 1rem;background:var(--cream);border:none;font-family:'DM Mono',monospace;font-size:0.62rem;letter-spacing:0.18em;text-transform:uppercase;color:var(--warm-gray);cursor:pointer;transition:all 0.2s;border-right:1px solid var(--gold-light);}
    .tab:last-child{border-right:none;}
    .tab.active{background:var(--ink);color:var(--cream);}
    main{position:relative;z-index:1;max-width:1200px;margin:0 auto;padding:3rem 1.5rem;display:grid;grid-template-columns:1fr 1fr;gap:3rem;align-items:start;}
    @media(max-width:768px){main{grid-template-columns:1fr;gap:2rem;}}
    .panel{background:var(--card-bg);border:1px solid var(--gold-light);border-radius:2px;padding:2.5rem;position:relative;}
    .panel::before{content:'';position:absolute;top:6px;left:6px;right:-6px;bottom:-6px;border:1px solid var(--gold-light);border-radius:2px;z-index:-1;}
    .panel-title{font-size:1.1rem;font-weight:600;letter-spacing:0.1em;margin-bottom:0.3rem;}
    .panel-subtitle{font-family:'DM Mono',monospace;font-size:0.65rem;color:var(--warm-gray);letter-spacing:0.2em;text-transform:uppercase;margin-bottom:2rem;}
    .tab-content{display:none;} .tab-content.active{display:block;}
    .photo-drop-zone{border:2px dashed var(--gold-light);border-radius:2px;padding:2rem 1.5rem;text-align:center;cursor:pointer;transition:all 0.3s;position:relative;}
    .photo-drop-zone:hover{border-color:var(--gold);background:rgba(201,168,76,0.04);}
    .photo-drop-zone input[type=file]{position:absolute;inset:0;opacity:0;cursor:pointer;width:100%;height:100%;}
    .drop-icon{font-size:2.5rem;margin-bottom:0.8rem;display:block;opacity:0.7;}
    .drop-text{font-size:1rem;color:var(--warm-gray);font-style:italic;margin-bottom:0.4rem;}
    .drop-hint{font-family:'DM Mono',monospace;font-size:0.6rem;color:var(--gold);letter-spacing:0.2em;text-transform:uppercase;}
    #photo-previews{display:none;flex-wrap:wrap;gap:0.6rem;margin-top:1.2rem;}
    .photo-thumb{position:relative;width:80px;height:80px;border:1px solid var(--gold-light);border-radius:2px;overflow:hidden;}
    .photo-thumb img{width:100%;height:100%;object-fit:cover;}
    .remove-btn{position:absolute;top:2px;right:2px;width:18px;height:18px;background:rgba(26,20,16,0.8);color:white;border:none;border-radius:50%;font-size:11px;cursor:pointer;}
    .info-group{margin-top:1.5rem;}
    .info-label{font-family:'DM Mono',monospace;font-size:0.6rem;letter-spacing:0.2em;text-transform:uppercase;color:var(--warm-gray);margin-bottom:0.4rem;display:block;}
    .info-input{width:100%;padding:0.7rem 1rem;border:1px solid var(--gold-light);border-radius:2px;background:white;font-family:'Cormorant Garamond',serif;font-size:1rem;margin-bottom:0.8rem;outline:none;}
    .btn-generate-full{display:block;width:100%;margin-top:1.5rem;padding:1rem;background:var(--ink);color:var(--cream);border:none;font-family:'DM Mono',monospace;font-size:0.7rem;letter-spacing:0.25em;text-transform:uppercase;cursor:pointer;transition:0.25s;}
    .btn-generate-full:hover{background:var(--gold);color:var(--ink);}
    .btn-generate-full:disabled{opacity:0.5;cursor:not-allowed;}
    .drop-zone{border:2px dashed var(--gold-light);border-radius:2px;padding:2.5rem 1.5rem;text-align:center;cursor:pointer;position:relative;}
    .url-group{display:flex;gap:0;}
    .url-input{flex:1;padding:0.8rem 1rem;border:1px solid var(--gold-light);border-right:none;font-family:'DM Mono',monospace;font-size:0.75rem;outline:none;}
    .btn-generate{padding:0.8rem 1.5rem;background:var(--ink);color:var(--cream);border:none;font-family:'DM Mono',monospace;font-size:0.65rem;text-transform:uppercase;cursor:pointer;}
    #error-box{display:none;margin-top:1rem;padding:1rem;border:1px solid var(--rust);background:rgba(139,58,42,0.05);color:var(--rust);font-family:'DM Mono',monospace;font-size:0.65rem;}
    #progress-box{display:none;margin-top:1.5rem;}
    .progress-step{display:flex;align-items:center;gap:0.8rem;padding:0.5rem 0;font-family:'DM Mono',monospace;font-size:0.65rem;color:var(--warm-gray);opacity:0.4;}
    .progress-step.active{opacity:1;color:var(--ink);}
    .progress-step.done{opacity:0.7;color:var(--sage);}
    .step-dot{width:8px;height:8px;border-radius:50%;border:1px solid currentColor;}
    .progress-step.active .step-dot{background:var(--gold);animation:pulse 1s infinite;}
    @keyframes pulse{0%,100%{transform:scale(1);}50%{transform:scale(1.3);}}
    #output-panel{display:none;animation:fadeIn 0.6s ease forwards;}
    @keyframes fadeIn{from{opacity:0;transform:translateY(12px);}to{opacity:1;transform:translateY(0);}}
    
    /* --- ZONES ÉDITABLES --- */
    [contenteditable="true"] { outline: none; transition: background 0.2s, border 0.2s; border-radius: 2px; padding: 2px 4px; margin: -2px -4px; }
    [contenteditable="true"]:hover { background: rgba(201,168,76,0.15); cursor: text; }
    [contenteditable="true"]:focus { background: rgba(201,168,76,0.25); border-bottom: 1px dashed var(--gold); }
    .edit-hint { background: var(--gold-light); color: var(--ink); text-align: center; padding: 0.5rem; font-family: 'DM Mono', monospace; font-size: 0.7rem; font-weight: bold; margin-bottom: 1rem; border-radius: 2px; }

    /* --- SÉLECTEUR DE THÈMES --- */
    .style-switcher { margin-bottom: 1.5rem; display: flex; align-items: center; justify-content: center; gap: 1rem; background: rgba(201,168,76,0.1); padding: 1rem; border-radius: 2px; border: 1px solid var(--gold-light); flex-wrap: wrap; }
    .style-switcher label { font-family: 'DM Mono', monospace; font-size: 0.75rem; text-transform: uppercase; color: var(--ink); font-weight: bold; }
    .style-switcher select { padding: 0.5rem 1rem; border: 1px solid var(--gold); border-radius: 2px; background: white; font-family: 'Cormorant Garamond', serif; font-size: 1.1rem; outline: none; cursor: pointer; color: var(--ink); min-width: 200px; }

    /* --- BASE CARTE MENU --- */
    .menu-card { transition: all 0.3s ease; background: var(--card-bg); color: var(--ink); border: 1px solid var(--gold-light); border-radius: 2px; position: relative; padding-bottom: 2rem; font-family: 'Cormorant Garamond', Georgia, serif; }
    .menu-card::before { content:''; position:absolute; top:6px; left:6px; right:-6px; bottom:-6px; border:1px solid var(--gold-light); border-radius:2px; z-index:-1; transition: all 0.3s ease; }
    .menu-header { background: var(--ink); color: var(--cream); padding: 2.5rem; text-align: center; position: relative; transition: all 0.3s ease; }
    .menu-restaurant-name { font-size: 2rem; font-weight: 300; letter-spacing: 0.2em; font-family: 'Cormorant Garamond', serif; }
    .menu-tagline-text { font-family: 'DM Mono', monospace; font-size: 0.6rem; color: var(--gold); margin-top: 0.5rem; text-transform: uppercase; }
    .menu-section { padding: 1.5rem 2.5rem 0.5rem; }
    .section-title { font-size: 1.1rem; font-weight: 600; letter-spacing: 0.15em; color: var(--rust); text-transform: uppercase; margin-bottom: 1rem; border-bottom: 1px solid var(--gold-light); transition: all 0.3s ease; }
    .menu-item { display: flex; justify-content: space-between; align-items: baseline; gap: 1rem; padding: 0.6rem 0; border-bottom: 1px dotted rgba(201,168,76,0.2); transition: all 0.3s ease; }
    .item-name { font-size: 1.1rem; font-weight: 500; color: inherit; }
    .item-desc { font-size: 0.85rem; font-style: italic; color: var(--warm-gray); margin-top: 0.2rem; }
    .item-price { font-family: 'DM Mono', monospace; font-size: 0.9rem; color: var(--gold); font-weight: bold; white-space: nowrap; }
    .menu-footer { margin-top: 2rem; padding: 1rem; text-align: center; border-top: 1px solid var(--gold-light); font-family: 'DM Mono', monospace; font-size: 0.65rem; color: var(--warm-gray); transition: all 0.3s ease; }

    /* THEMES SUPPLEMENTAIRES INCLUS */
    .menu-card.theme-minimal { background: #ffffff; color: #111111; border: 1px solid #e0e0e0; font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; }
    .menu-card.theme-minimal::before { display: none; }
    .menu-card.theme-minimal .menu-header { background: #ffffff; color: #111111; border-bottom: 2px solid #111111; padding: 3rem 2rem; }
    .menu-card.theme-minimal .section-title { color: #111111; border-bottom: 2px solid #111111; font-family: 'Helvetica Neue', sans-serif; font-weight: 700; }
    .menu-card.theme-minimal .menu-item { border-bottom: 1px solid #f0f0f0; }
    
    .menu-card.theme-dark { background: #121212; color: #e0e0e0; border: 1px solid #333333; }
    .menu-card.theme-dark::before { border: 1px solid #333333; }
    .menu-card.theme-dark .menu-header { background: #0a0a0a; color: #C9A84C; border-bottom: 1px solid #222222; }
    .menu-card.theme-dark .section-title { color: #C9A84C; border-bottom: 1px solid #333333; }
    .menu-card.theme-dark .item-name { color: #ffffff; }

    .menu-card.theme-fastfood { background: #ffffff; color: #212121; border: 4px solid #E53935; font-family: 'Impact', 'Arial Black', sans-serif; border-radius: 8px; }
    .menu-card.theme-fastfood::before { display: none; }
    .menu-card.theme-fastfood .menu-header { background: #E53935; color: #FFEB3B; padding: 2rem; }
    .menu-card.theme-fastfood .section-title { color: #E53935; border-bottom: 3px solid #FFEB3B; font-size: 1.5rem; }
    .menu-card.theme-fastfood .item-name { font-family: Arial, sans-serif; font-weight: 900; font-size: 1.2rem; text-transform: uppercase; }

    .menu-card.theme-pizzeria { background: #FDFBF7; color: #3E2723; border: 2px solid #2E7D32; border-radius: 4px; }
    .menu-card.theme-pizzeria::before { content: ''; position: absolute; top: 4px; left: 4px; right: 4px; bottom: 4px; border: 1px solid #C62828; z-index: -1; }
    .menu-card.theme-pizzeria .menu-header { background: #2E7D32; color: #ffffff; border-bottom: 4px solid #C62828; }
    .menu-card.theme-pizzeria .section-title { color: #C62828; border-bottom: 2px dashed #2E7D32; font-weight: bold; }

    .menu-card.theme-turkish { background: #FAFAFA; color: #212121; border: 2px solid #B71C1C; }
    .menu-card.theme-turkish::before { border: 1px solid #00838F; top: 8px; left: 8px; right: -8px; bottom: -8px; }
    .menu-card.theme-turkish .menu-header { background: #B71C1C; color: #ffffff; }
    .menu-card.theme-turkish .section-title { color: #00838F; border-bottom: 2px solid #B71C1C; }

    .menu-card.theme-indian { background: #FFF8E1; color: #3E2723; border: 0; box-shadow: 0 0 0 4px #E65100, 0 0 0 8px #880E4F; margin: 8px; }
    .menu-card.theme-indian::before { display: none; }
    .menu-card.theme-indian .menu-header { background: #E65100; color: #ffffff; border-bottom: 5px solid #880E4F; }
    .menu-card.theme-indian .section-title { color: #880E4F; border-bottom: 2px solid #E65100; }

    .menu-card.theme-french { background: #F9F9F9; color: #1A237E; border: 1px solid #1A237E; }
    .menu-card.theme-french::before { border: 1px solid #B71C1C; top: 4px; left: 4px; right: 4px; bottom: 4px; z-index: 1; pointer-events: none; }
    .menu-card.theme-french .menu-header { background: #1A237E; color: #ffffff; padding-bottom: 3rem; }
    .menu-card.theme-french .section-title { color: #B71C1C; border-bottom: 1px solid #1A237E; text-align: center; }

    /* --- ÉLÉMENTS UI GÉNÉRAUX --- */
    .timer-badge{display:inline-flex;align-items:center;gap:0.4rem;background:var(--sage);color:white;font-family:'DM Mono',monospace;font-size:0.6rem;padding:0.4rem 0.8rem;border-radius:20px;margin-top:1rem;}
    .action-row{display:flex;gap:0.8rem;margin-top:1.2rem;}
    .btn-action{flex:1;padding:0.75rem;border:1px solid var(--gold-light);background:transparent;font-family:'DM Mono',monospace;font-size:0.6rem;text-transform:uppercase;cursor:pointer;}
    .btn-action.primary{background:var(--ink);color:var(--cream);}
    #qr-canvas{display:none;}
    #qr-preview-box{margin-top:1rem;display:none;align-items:center;gap:1rem;padding:0.8rem;background:rgba(201,168,76,0.06);border:1px solid var(--gold-light);}
    #qr-preview-box img{width:50px;height:50px;object-fit:cover;}

    /* --- SECTION DÉPLOIEMENT --- */
    .deploy-box { margin-top: 2rem; padding: 1.5rem; border: 1px dashed var(--gold); background: rgba(201,168,76,0.05); border-radius: 2px; text-align: center; }
    .deploy-box h3 { margin-bottom: 0.5rem; color: var(--ink); font-size: 1.2rem; }
    .deploy-box p { font-family: 'DM Mono', monospace; font-size: 0.75rem; color: var(--warm-gray); margin-bottom: 1.5rem; line-height: 1.4; }
    .deploy-inputs { display: flex; gap: 0.5rem; justify-content: center; margin-bottom: 1.5rem; flex-wrap: wrap; }
    .deploy-inputs input { padding: 0.8rem; border: 1px solid var(--gold-light); border-radius: 2px; font-family: 'DM Mono', monospace; font-size: 0.75rem; width: 220px; outline: none; }
    #qrcode-container { margin-top: 2rem; display: none; flex-direction: column; align-items: center; gap: 1rem; background: white; padding: 1.5rem; border: 1px solid var(--gold-light); }
    .qr-link { font-family: 'DM Mono', monospace; font-size: 0.8rem; color: var(--rust); font-weight: bold; text-decoration: none; word-break: break-all; }
    .qr-link:hover { text-decoration: underline; }
    
    /* Bouton Paramètres */
    .settings-btn { margin-top: 3rem; text-align: center; padding-bottom: 2rem; }
    .settings-btn button { background: none; border: none; color: var(--warm-gray); font-family: 'DM Mono', monospace; font-size: 0.7rem; cursor: pointer; text-decoration: underline; transition: color 0.2s; }
    .settings-btn button:hover { color: var(--ink); }
  </style>
</head>
<body>

<header>
  <div class="logo-line">
    <div class="logo-ornament"></div>
    <h1>Menu<span>AI</span></h1>
    <div class="logo-ornament right"></div>
  </div>
  <p class="tagline">Génération de carte par IA (Gemini 2.5)</p>
  <div class="tabs">
    <button class="tab active" onclick="switchTab('photo')">Photos du menu</button>
    <button class="tab" onclick="switchTab('qr')">QR Code / URL</button>
  </div>
</header>

<main>
  <div>
    <div class="panel">
      <div class="tab-content active" id="tab-photo">
        <div class="panel-title">Analysez vos photos</div>
        <div class="panel-subtitle">Vision intelligente pour extraire plats & prix</div>
        <div class="photo-drop-zone" id="photo-drop-zone">
          <input type="file" id="photo-input" accept="image/*" multiple />
          <span class="drop-icon">📷</span>
          <p class="drop-text">Déposez vos photos ici</p>
          <p class="drop-hint">PNG, JPG, HEIC acceptés</p>
        </div>
        <div id="photo-previews"></div>
        <div class="info-group">
          <label class="info-label">Nom du restaurant</label>
          <input type="text" class="info-input" id="resto-name" placeholder="Ex: Le Petit Bistrot" />
          <label class="info-label">Ville / Adresse</label>
          <input type="text" class="info-input" id="resto-address" placeholder="Ex: Lyon, France" />
        </div>
        <button class="btn-generate-full" id="btn-analyze" onclick="analyzePhotos()">Générer la carte</button>
      </div>

      <div class="tab-content" id="tab-qr">
        <div class="panel-title">Scanner un menu en ligne</div>
        <div class="panel-subtitle">Déposez le QR Code ou collez l'URL</div>
        <div class="drop-zone" id="drop-zone">
          <input type="file" id="file-input" accept="image/*" />
          <span class="drop-icon">🔗</span>
          <p class="drop-text">Déposez le QR Code ici</p>
        </div>
        <div id="qr-preview-box">
          <img id="qr-preview-img" src="" alt="QR"/>
          <div style="font-family:'DM Mono'; font-size: 0.65rem;" id="qr-url-display"></div>
        </div>
        <div style="margin:1.5rem 0; text-align:center; color:var(--warm-gray); font-style: italic;">— ou —</div>
        <div class="url-group">
          <input type="text" class="url-input" id="url-input" placeholder="https://votre-menu-en-ligne.fr"/>
          <button class="btn-generate" id="btn-generate" onclick="generateFromURL()">Go</button>
        </div>
      </div>

      <div id="error-box"></div>
      
      <div id="progress-box">
        <div class="progress-step" id="step-1"><div class="step-dot"></div><span id="lbl-1">Préparation des données</span></div>
        <div class="progress-step" id="step-2"><div class="step-dot"></div><span id="lbl-2">Analyse visuelle en cours...</span></div>
        <div class="progress-step" id="step-3"><div class="step-dot"></div><span id="lbl-3">Structuration de la carte</span></div>
        <div class="progress-step" id="step-4"><div class="step-dot"></div><span id="lbl-4">Rendu du design</span></div>
      </div>
    </div>
  </div>

  <div id="output-panel">
    <div class="edit-hint">
      ✏️ Tapez directement sur les textes ou les prix ci-dessous pour les modifier avant la publication.
    </div>

    <div class="style-switcher">
      <label for="theme-select">🎨 Style du menu :</label>
      <select id="theme-select" onchange="changeTheme()">
        <option value="theme-classic">🥐 Classique & Bistrot</option>
        <option value="theme-french">🍷 Brasserie Française</option>
        <option value="theme-pizzeria">🍕 Pizzeria / Italien</option>
        <option value="theme-fastfood">🍔 Fast Food / Burger</option>
        <option value="theme-turkish">🥙 Turc / Oriental</option>
        <option value="theme-indian">🍛 Indien / Épicé</option>
        <option value="theme-minimal">🧊 Moderne & Épuré</option>
        <option value="theme-dark">🌙 Gastronomique Sombre</option>
      </select>
    </div>

    <div class="menu-card theme-classic" id="menu-card"></div>
    
    <div class="action-row">
      <button class="btn-action" onclick="window.print()">Imprimer</button>
      <button class="btn-action primary" onclick="downloadMenu()">Télécharger HTML</button>
    </div>

    <div class="deploy-box">
      <h3>🚀 Publier en ligne & Créer QR Code</h3>
      <p>Crée automatiquement un site web gratuit via GitHub Pages. <br/>(Nécessite un Token d'accès classique avec les droits 'repo')</p>
      
      <div class="deploy-inputs">
        <input type="text" id="gh-token" placeholder="Token GitHub (ghp_...)" />
        <input type="text" id="gh-repo" placeholder="Nom du lien (ex: menu-resto)" />
      </div>
      
      <button class="btn-generate-full" id="btn-deploy" onclick="deployAndGenerateQR()" style="margin-top:0;">Générer le site web et le QR</button>
      
      <div id="qrcode-container">
        <p style="color:var(--ink); font-weight:bold; margin-bottom:0;">Flashez pour voir le menu !</p>
        <div id="qrcode-box"></div>
        <a id="qr-link" class="qr-link" href="#" target="_blank">Lien de votre menu</a>
        <p style="font-size:0.65rem; color:var(--warm-gray); margin-top:0.5rem; border:none;">(Note: GitHub Pages peut mettre 1 à 2 minutes avant que le lien soit actif)</p>
      </div>
    </div>

    <div id="timer-display"></div>
  </div>

  <div class="settings-btn">
    <button onclick="resetAPIKey()">⚙️ Changer la clé API Gemini</button>
  </div>
</main>

<canvas id="qr-canvas"></canvas>

<script>
/**
 * GESTION SÉCURISÉE DE LA CLÉ API GEMINI
 */
let GEMINI_API_KEY = localStorage.getItem("geminiKey");

if (!GEMINI_API_KEY || GEMINI_API_KEY === "null") {
  GEMINI_API_KEY = prompt("🔐 Bienvenue sur MenuAI !\nPour utiliser l'intelligence artificielle, collez votre clé API Gemini ici :");
  
  if (GEMINI_API_KEY && GEMINI_API_KEY.trim() !== "") {
    GEMINI_API_KEY = GEMINI_API_KEY.trim();
    localStorage.setItem("geminiKey", GEMINI_API_KEY);
  } else {
    alert("⚠️ Vous devez rafraîchir la page et entrer une clé API pour que l'application fonctionne.");
  }
}

function resetAPIKey() {
  localStorage.removeItem("geminiKey");
  alert("La clé a été effacée. La page va se recharger pour vous demander la nouvelle clé.");
  location.reload();
}

let uploadedPhotos = [];
let currentStep = -1;

// --- ONGLET NAVIGATION ---
function switchTab(tab){
  document.querySelectorAll('.tab').forEach((t,i) => t.classList.toggle('active',(tab==='photo'&&i===0)||(tab==='qr'&&i===1)));
  document.getElementById('tab-photo').classList.toggle('active',tab==='photo');
  document.getElementById('tab-qr').classList.toggle('active',tab==='qr');
  hideError();
}

// --- GESTION DU THÈME ---
function changeTheme() {
  const theme = document.getElementById('theme-select').value;
  document.getElementById('menu-card').className = 'menu-card ' + theme;
}

// --- GESTION DES PHOTOS ---
const photoInput = document.getElementById('photo-input');
photoInput.addEventListener('change', e => handlePhotoFiles(Array.from(e.target.files)));

async function handlePhotoFiles(files){
  const imgs = files.filter(f => f.type.startsWith('image/'));
  for(let f of imgs){
    const base64 = await fileToBase64(f);
    uploadedPhotos.push({ mimeType: f.type, data: base64.split(',')[1], preview: base64 });
  }
  renderThumbs();
}

function fileToBase64(file){
  return new Promise(res => { const r = new FileReader(); r.onload = () => res(r.result); r.readAsDataURL(file); });
}

function renderThumbs(){
  const div = document.getElementById('photo-previews');
  div.style.display = uploadedPhotos.length ? 'flex' : 'none';
  div.innerHTML = uploadedPhotos.map((p,i) => `
    <div class="photo-thumb">
      <img src="${p.preview}" />
      <button class="remove-btn" onclick="removePhoto(${i})">×</button>
    </div>
  `).join('');
}

function removePhoto(i){ uploadedPhotos.splice(i,1); renderThumbs(); }

// --- APPEL API GEMINI ---
async function callGemini(parts, restoInfo) {
  if (!GEMINI_API_KEY) throw new Error("Clé API manquante. Cliquez sur 'Changer la clé API' en bas de page.");

  const systemPrompt = `Tu es un expert en numérisation de menus de restaurants.
  INSTRUCTIONS:
  1. Extrais TOUS les plats, descriptions et prix.
  2. Organise par sections logiques (Entrées, Plats, Desserts, Boissons...).
  3. Formate les prix proprement (ex: 12,00€). Si absent, mets "NC".
  4. Réponds UNIQUEMENT en JSON valide.
  
  STRUCTURE JSON:
  {
    "name": "${restoInfo.name || 'Le Restaurant'}",
    "tagline": "Cuisine Inspirée • ${restoInfo.addr || 'Fait Maison'}",
    "address": "${restoInfo.addr || ''}",
    "sections": [
      { "title": "SECTION", "items": [{"name": "Nom", "desc": "Desc", "price": "10€"}] }
    ]
  }`;

  const body = {
    contents: [{ parts: [{ text: systemPrompt }, ...parts] }],
    generationConfig: { responseMimeType: "application/json", temperature: 0.2 }
  };

  const primaryUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash:generateContent?key=${GEMINI_API_KEY}`;
  
  let resp = await fetch(primaryUrl, { method: "POST", body: JSON.stringify(body) });
  
  if(!resp.ok) {
    const errorDetails = await resp.json();
    console.warn("Échec sur Gemini 2.5, bascule sur Gemini 2.0...", errorDetails);
    
    if(errorDetails.error?.message?.includes("is not found") || errorDetails.error?.code === 404) {
        const fallbackUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${GEMINI_API_KEY}`;
        resp = await fetch(fallbackUrl, { method: "POST", body: JSON.stringify(body) });
        if(!resp.ok) {
           const finalError = await resp.json();
           throw new Error("Erreur API : " + (finalError.error?.message || "Modèle introuvable."));
        }
    } else {
        throw new Error(errorDetails.error?.message || "Erreur de connexion à l'API. Vérifiez votre clé.");
    }
  }
  
  const json = await resp.json();
  return JSON.parse(json.candidates[0].content.parts[0].text);
}

// --- ACTIONS : GÉNÉRATION VIA PHOTOS ---
async function analyzePhotos(){
  if(!uploadedPhotos.length) return showError("Veuillez ajouter au moins une photo.");
  const startTime = Date.now();
  const name = document.getElementById('resto-name').value;
  const addr = document.getElementById('resto-address').value;

  setLoading(true); showProgress();

  try {
    await advanceStep(1, 400);
    const parts = uploadedPhotos.map(p => ({ inlineData: { mimeType: p.mimeType, data: p.data } }));
    
    await advanceStep(2, 200);
    const data = await callGemini(parts, {name, addr});
    
    await advanceStep(3, 400); await advanceStep(4, 200);
    
    renderMenu(data, ((Date.now() - startTime)/1000).toFixed(1));
  } catch(e) {
    showError("Échec de l'analyse : " + e.message);
  } finally {
    setLoading(false); hideProgress();
  }
}

// --- ACTIONS : GÉNÉRATION VIA URL ---
async function generateFromURL(){
  const urlStr = document.getElementById('url-input').value;
  if(!urlStr) return showError("Veuillez entrer une URL valide.");
  
  const startTime = Date.now();
  setLoading(true); showProgress();

  try {
    await advanceStep(1, 400);
    const parts = [{ text: "Génère un menu structuré à partir du contenu de cette page : " + urlStr }];
    
    await advanceStep(2, 600);
    const data = await callGemini(parts, {name:"", addr:""});
    
    renderMenu(data, ((Date.now() - startTime)/1000).toFixed(1));
  } catch(e) {
    showError("Échec de l'analyse : " + e.message);
  } finally {
    setLoading(false); hideProgress();
  }
}

// --- RENDU HTML DE LA CARTE (Maintenant Editable par l'utilisateur) ---
function renderMenu(data, elapsed){
  const card = document.getElementById('menu-card');
  card.innerHTML = `
    <div class="menu-header">
      <div class="menu-restaurant-name" contenteditable="true">${data.name}</div>
      <div class="menu-tagline-text" contenteditable="true">${data.tagline}</div>
    </div>
    ${data.sections.map(s => `
      <div class="menu-section">
        <div class="section-title" contenteditable="true">${s.title}</div>
        ${s.items.map(it => `
          <div class="menu-item">
            <div>
              <div class="item-name" contenteditable="true">${it.name}</div>
              <div class="item-desc" contenteditable="true">${it.desc || ''}</div>
            </div>
            <div class="item-price" contenteditable="true">${it.price}</div>
          </div>
        `).join('')}
      </div>
    `).join('')}
    <div class="menu-footer" contenteditable="true">${data.address}</div>
  `;
  
  changeTheme(); 
  document.getElementById('output-panel').style.display = 'block';
  document.getElementById('timer-display').innerHTML = `<div class="timer-badge">Généré en ${elapsed}s (Gemini AI)</div>`;
  window.scrollTo({top: document.getElementById('output-panel').offsetTop - 20, behavior: 'smooth'});
}

// --- HELPERS UI ---
function setLoading(val){
  document.getElementById('btn-analyze').disabled = val;
  document.getElementById('btn-generate').disabled = val;
}
function showError(m){ const b=document.getElementById('error-box'); b.textContent=m; b.style.display='block'; }
function hideError(){ document.getElementById('error-box').style.display='none'; }
function showProgress(){ document.getElementById('progress-box').style.display='block'; currentStep=-1; }
function hideProgress(){ setTimeout(()=>document.getElementById('progress-box').style.display='none', 800); }

async function advanceStep(n, d){
  if(currentStep >= 0) document.getElementById('step-'+(currentStep+1)).className='progress-step done';
  currentStep = n-1;
  document.getElementById('step-'+(currentStep+1)).className='progress-step active';
  await new Promise(r => setTimeout(r, d));
}

// --- EXPORT HTML LOCAL (Retire l'attribut contenteditable pour la version finale) ---
function downloadMenu(){
  // On récupère le HTML mais on enlève la possibilité de l'éditer pour le site final
  let content = document.getElementById('menu-card').outerHTML;
  content = content.replace(/contenteditable="true"/g, '');

  const styles = document.querySelector('style').innerHTML; 
  
  const fullHtml = `<!DOCTYPE html><html><head><meta charset="UTF-8">
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=DM+Mono:wght@300;400;500&display=swap" rel="stylesheet"/>
    <style>
      ${styles} 
      body { background: #f0f0f0; padding: 40px; font-family: sans-serif; } 
      .menu-card { max-width: 800px; margin: auto; box-shadow: 0 10px 30px rgba(0,0,0,0.1); }
    </style>
    </head><body>${content}</body></html>`;
    
  const blob = new Blob([fullHtml], {type:'text/html'});
  const a = document.createElement('a');
  a.href = URL.createObjectURL(blob);
  a.download = 'carte-menu.html';
  a.click();
}

// --- LECTURE QR CODE (ONGLET 2) ---
const fileInput = document.getElementById('file-input');
fileInput.addEventListener('change', e => {
  const f = e.target.files[0];
  if(!f) return;
  const r = new FileReader();
  r.onload = ev => {
    const img = new Image();
    img.onload = () => {
      const c = document.getElementById('qr-canvas');
      const ctx = c.getContext('2d');
      c.width = img.width; c.height = img.height;
      ctx.drawImage(img,0,0);
      const code = jsQR(ctx.getImageData(0,0,c.width,c.height).data, c.width, c.height);
      if(code){
        document.getElementById('url-input').value = code.data;
        document.getElementById('qr-preview-box').style.display = 'flex';
        document.getElementById('qr-preview-img').src = ev.target.result;
        document.getElementById('qr-url-display').textContent = "Lien détecté : " + code.data;
      } else {
        showError("QR Code illisible ou image trop floue.");
      }
    };
    img.src = ev.target.result;
  };
  r.readAsDataURL(f);
});

// --- DÉPLOIEMENT GITHUB PAGES & GÉNÉRATION QR (Nettoie aussi l'édition) ---
async function deployAndGenerateQR() {
  const token = document.getElementById('gh-token').value.trim();
  let repoName = document.getElementById('gh-repo').value.trim();
  const btn = document.getElementById('btn-deploy');

  if(!token || !repoName) return showError("Le Token GitHub et le Nom du lien sont obligatoires.");
  
  repoName = repoName.replace(/\s+/g, '-').toLowerCase(); 

  btn.disabled = true;
  btn.textContent = "⚙️ Déploiement en cours...";
  hideError();

  try {
    let res = await fetch('https://api.github.com/user', { headers: { 'Authorization': `token ${token}` } });
    if(!res.ok) throw new Error("Le Token GitHub est invalide ou expiré.");
    const user = await res.json();
    const username = user.login;

    await fetch('https://api.github.com/user/repos', {
      method: 'POST',
      headers: { 'Authorization': `token ${token}`, 'Content-Type': 'application/json' },
      body: JSON.stringify({ name: repoName, auto_init: true })
    });

    // Récupération du HTML et suppression des attributs "contenteditable"
    let content = document.getElementById('menu-card').outerHTML;
    content = content.replace(/contenteditable="true"/g, '');

    const styles = document.querySelector('style').innerHTML; 
    const fullHtml = `<!DOCTYPE html><html><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>Menu | ${username}</title><link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=DM+Mono:wght@300;400;500&display=swap" rel="stylesheet"/><style>${styles} body { background: #f5f0e8; padding: 15px; } .menu-card { max-width: 800px; margin: auto; box-shadow: 0 5px 20px rgba(0,0,0,0.1); }</style></head><body>${content}</body></html>`;
    
    const encodedHtml = btoa(unescape(encodeURIComponent(fullHtml)));

    const putUrl = `https://api.github.com/repos/${username}/${repoName}/contents/index.html`;
    let fileSha = null;
    const getRes = await fetch(putUrl, { headers: { 'Authorization': `token ${token}` } });
    if(getRes.ok) {
       const fileData = await getRes.json();
       fileSha = fileData.sha;
    }

    const body = { message: "Mise à jour du menu via MenuAI", content: encodedHtml };
    if(fileSha) body.sha = fileSha;

    res = await fetch(putUrl, {
      method: 'PUT',
      headers: { 'Authorization': `token ${token}`, 'Content-Type': 'application/json' },
      body: JSON.stringify(body)
    });
    if(!res.ok) throw new Error("Impossible de créer la page web sur GitHub.");

    await fetch(`https://api.github.com/repos/${username}/${repoName}/pages`, {
      method: 'POST',
      headers: { 'Authorization': `token ${token}`, 'Accept': 'application/vnd.github.switcheroo-preview+json' },
      body: JSON.stringify({ source: { branch: 'main', path: '/' } })
    });

    const pageUrl = `https://${username}.github.io/${repoName}/`;
    
    document.getElementById('qrcode-box').innerHTML = ''; 
    new QRCode(document.getElementById("qrcode-box"), {
      text: pageUrl,
      width: 180,
      height: 180,
      colorDark : "#1A1410",
      colorLight : "#ffffff",
      correctLevel : QRCode.CorrectLevel.H
    });
    
    document.getElementById('qr-link').href = pageUrl;
    document.getElementById('qr-link').textContent = pageUrl;
    document.getElementById('qrcode-container').style.display = 'flex';
    
    btn.textContent = "✅ Déploiement réussi !";
    setTimeout(() => { btn.disabled = false; btn.textContent = "Mettre à jour la page"; }, 3000);

  } catch(e) {
    showError(e.message);
    btn.disabled = false;
    btn.textContent = "Générer le site web et le QR";
  }
}
</script>
</body>
</html>