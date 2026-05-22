<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Snail 96 Mucin Power Essence</title>
<style>
:root{
  --cream:#fdf8f3;--blush:#e8c9b0;--mocha:#7a5c44;--dark:#2e1f14;
  --accent:#c0875a;--gold:#f5a623;--red:#e53935;--green:#2e7d32;
  --white:#fff;--shadow:0 4px 24px rgba(122,92,68,.13);
}
*{margin:0;padding:0;box-sizing:border-box;}
body{font-family:'Segoe UI',Arial,sans-serif;background:var(--cream);color:var(--dark);}

/* ── NAV ── */
nav{background:var(--white);box-shadow:var(--shadow);position:sticky;top:0;z-index:999;
  display:flex;align-items:center;justify-content:space-between;padding:0 40px;height:64px;}
.nav-logo{font-size:1.1rem;font-weight:800;color:var(--mocha);letter-spacing:2px;}
.lang-toggle{display:flex;border:2px solid var(--accent);border-radius:24px;overflow:hidden;}
.lang-btn{padding:7px 20px;font-size:.85rem;font-weight:700;border:none;background:transparent;
  color:var(--accent);cursor:pointer;transition:all .2s;}
.lang-btn.active{background:var(--accent);color:var(--white);}

/* ── HERO ── */
.hero{display:flex;flex-wrap:wrap;align-items:flex-start;justify-content:center;
  gap:48px;padding:60px 40px;max-width:1100px;margin:0 auto;}

/* ── GALLERY ── */
.gallery{display:flex;gap:12px;flex-shrink:0;}
.thumbs{display:flex;flex-direction:column;gap:10px;}
.thumb{width:68px;height:68px;border-radius:12px;overflow:hidden;cursor:pointer;
  border:2px solid transparent;transition:border-color .2s;flex-shrink:0;}
.thumb.active{border-color:var(--accent);}
.thumb-inner{width:100%;height:100%;display:flex;align-items:center;justify-content:center;
  font-size:1.6rem;}

.main-img-box{width:300px;height:370px;border-radius:22px;overflow:hidden;
  box-shadow:var(--shadow);position:relative;display:flex;align-items:center;
  justify-content:center;flex-shrink:0;}
.main-visual{width:100%;height:100%;display:flex;align-items:center;
  justify-content:center;position:relative;transition:opacity .3s;}
.badge-red{position:absolute;top:14px;left:14px;background:var(--red);color:#fff;
  font-size:.68rem;font-weight:700;padding:5px 12px;border-radius:20px;z-index:3;
  text-transform:uppercase;letter-spacing:.5px;}
.badge-dark{position:absolute;top:14px;right:14px;background:var(--mocha);color:#fff;
  font-size:.68rem;font-weight:700;padding:5px 12px;border-radius:20px;z-index:3;}

/* Product bottle SVG visual */
.bottle-visual{display:flex;flex-direction:column;align-items:center;gap:6px;}
.bottle-visual svg{filter:drop-shadow(0 8px 16px rgba(122,92,68,.25));}
.bottle-tagline{font-size:.75rem;font-weight:700;color:var(--mocha);letter-spacing:1px;
  text-transform:uppercase;opacity:.7;}

/* ── HERO TEXT ── */
.hero-text{max-width:460px;}
.hero-tag{font-size:.73rem;font-weight:700;color:var(--accent);letter-spacing:2px;
  text-transform:uppercase;margin-bottom:10px;}
.hero-title{font-size:2rem;font-weight:800;line-height:1.2;margin-bottom:8px;}
.hero-sub{font-size:.87rem;color:#9b7355;margin-bottom:14px;line-height:1.5;}
.star-row{display:flex;align-items:center;gap:8px;margin-bottom:18px;}
.stars{color:var(--gold);font-size:1.05rem;}
.star-info{font-size:.84rem;color:#7a6050;}
.hero-desc{font-size:.97rem;line-height:1.75;color:#6b4f38;margin-bottom:22px;}

/* ── QUANTITY ── */
.qty-section{background:var(--white);border:2px solid var(--blush);border-radius:18px;
  padding:20px;margin-bottom:18px;}
.qty-label{font-size:.78rem;font-weight:700;color:var(--mocha);text-transform:uppercase;
  letter-spacing:1px;margin-bottom:12px;}
.qty-options{display:flex;flex-direction:column;gap:9px;}
.qty-opt{display:flex;align-items:center;justify-content:space-between;
  border:2px solid #e8d5c0;border-radius:13px;padding:11px 15px;cursor:pointer;
  transition:all .2s;position:relative;user-select:none;}
.qty-opt:hover{border-color:var(--accent);background:#fff8f2;}
.qty-opt.selected{border-color:var(--accent);background:#fff3e8;}
.qty-left{display:flex;align-items:center;gap:10px;}
.bottle-icons{font-size:1.2rem;letter-spacing:1px;}
.qty-title{font-weight:700;font-size:.92rem;color:var(--dark);}
.qty-save-txt{font-size:.73rem;color:var(--green);font-weight:600;margin-top:2px;}
.qty-right{text-align:right;}
.qty-p{font-size:1.05rem;font-weight:800;color:var(--red);}
.qty-per{font-size:.7rem;color:#9b7355;margin-top:2px;}
.pop-badge{position:absolute;top:-9px;right:10px;color:#fff;
  font-size:.63rem;font-weight:700;padding:3px 9px;border-radius:10px;}

/* ── PRICE ── */
.price-box{background:linear-gradient(90deg,#fff7f0,#ffeedd);
  border:1.5px solid var(--blush);border-radius:14px;padding:16px 20px;margin-bottom:16px;}
.price-now{font-size:2.2rem;font-weight:900;color:var(--red);}
.price-was{font-size:.95rem;text-decoration:line-through;color:#bbb;margin-left:8px;}
.price-tag{background:var(--red);color:#fff;font-size:.7rem;font-weight:700;
  padding:2px 9px;border-radius:10px;margin-left:8px;vertical-align:middle;}
.price-note{font-size:.75rem;color:#9b7355;margin-top:6px;}

.trust-row{display:flex;flex-wrap:wrap;gap:8px;margin-bottom:18px;}
.chip{background:var(--white);border:1.5px solid var(--blush);border-radius:20px;
  padding:5px 13px;font-size:.75rem;color:var(--mocha);font-weight:600;}

.btn-buy{width:100%;background:var(--red);color:#fff;padding:16px;border-radius:50px;
  font-size:1rem;font-weight:800;border:none;cursor:pointer;margin-bottom:10px;
  transition:transform .15s,box-shadow .15s;box-shadow:0 4px 16px rgba(229,57,53,.35);}
.btn-buy:hover{transform:translateY(-2px);box-shadow:0 8px 24px rgba(229,57,53,.5);}
.btn-buy:active{transform:translateY(0);}
.btn-cart{width:100%;background:transparent;color:var(--accent);padding:14px;
  border-radius:50px;font-size:1rem;font-weight:700;border:2px solid var(--accent);
  cursor:pointer;transition:all .18s;}
.btn-cart:hover{background:var(--accent);color:#fff;}

/* ── STATS ── */
.stats{background:var(--mocha);color:#fff;display:flex;flex-wrap:wrap;justify-content:center;}
.stat{padding:28px 44px;text-align:center;border-right:1px solid rgba(255,255,255,.15);}
.stat:last-child{border-right:none;}
.stat-num{font-size:1.9rem;font-weight:800;}
.stat-label{font-size:.8rem;opacity:.8;margin-top:4px;}

/* ── PHOTO STRIP ── */
.strip-section{max-width:1100px;margin:0 auto;padding:64px 40px 0;}
.section-title{font-size:1.6rem;font-weight:800;text-align:center;margin-bottom:40px;color:var(--dark);}
.photo-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;}
.photo-card{border-radius:20px;overflow:hidden;box-shadow:var(--shadow);position:relative;cursor:pointer;}
.photo-card-inner{height:230px;display:flex;align-items:center;justify-content:center;
  font-size:4rem;transition:transform .3s;}
.photo-card:hover .photo-card-inner{transform:scale(1.06);}
.photo-cap{background:rgba(46,31,20,.75);color:#fff;padding:10px 16px;
  font-size:.82rem;font-weight:600;backdrop-filter:blur(4px);}

/* ── BENEFITS ── */
.section{max-width:1100px;margin:0 auto;padding:64px 40px;}
.benefits{display:flex;flex-wrap:wrap;gap:20px;justify-content:center;}
.benefit-card{background:var(--white);border-radius:18px;padding:28px 22px;width:205px;
  text-align:center;box-shadow:var(--shadow);transition:transform .2s;}
.benefit-card:hover{transform:translateY(-5px);}
.b-icon{font-size:2.2rem;margin-bottom:12px;}
.b-title{font-weight:700;font-size:.95rem;color:var(--mocha);margin-bottom:6px;}
.b-desc{font-size:.83rem;color:#7a6050;line-height:1.55;}

/* ── HOW ── */
.how{background:linear-gradient(135deg,#fdf0e6,#f5e6d8);padding:64px 0;}
.how-inner{max-width:1100px;margin:0 auto;padding:0 40px;}
.steps{display:flex;flex-wrap:wrap;gap:16px;justify-content:center;}
.step{background:var(--white);border-radius:14px;padding:26px 20px;width:195px;
  text-align:center;box-shadow:var(--shadow);}
.step-num{width:36px;height:36px;border-radius:50%;background:var(--accent);color:#fff;
  font-weight:800;display:flex;align-items:center;justify-content:center;margin:0 auto 12px;}
.step-text{font-size:.84rem;color:#6b4f38;line-height:1.5;}

/* ── REVIEWS ── */
.reviews{display:flex;flex-wrap:wrap;gap:20px;justify-content:center;}
.review-card{background:var(--white);border-radius:18px;padding:26px;width:290px;
  box-shadow:var(--shadow);}
.r-stars{color:var(--gold);font-size:1rem;margin-bottom:9px;}
.r-text{font-size:.88rem;color:#5c3d28;line-height:1.65;margin-bottom:12px;font-style:italic;}
.r-author{font-weight:700;font-size:.8rem;color:var(--mocha);}

/* ── CTA ── */
.cta-section{background:linear-gradient(135deg,var(--mocha),var(--accent));
  color:#fff;text-align:center;padding:64px 40px;}
.cta-title{font-size:1.9rem;font-weight:800;margin-bottom:12px;}
.cta-sub{font-size:.98rem;opacity:.9;margin-bottom:28px;}
.btn-white{background:#fff;color:var(--red);padding:16px 44px;border-radius:50px;
  font-size:1rem;font-weight:800;border:none;cursor:pointer;
  box-shadow:0 4px 16px rgba(0,0,0,.2);transition:transform .15s,box-shadow .15s;}
.btn-white:hover{transform:translateY(-2px);box-shadow:0 8px 28px rgba(0,0,0,.3);}

footer{background:var(--dark);color:#c4a68a;text-align:center;padding:26px;font-size:.8rem;}

/* ── RESPONSIVE ── */
@media(max-width:768px){
  nav{padding:0 14px;height:56px;}
  .nav-logo{font-size:.95rem;}
  .lang-btn{padding:5px 14px;}
  .hero{flex-direction:column;align-items:center;padding:28px 14px 36px;gap:20px;}
  .gallery{flex-direction:column;align-items:center;width:100%;}
  .thumbs{flex-direction:row;justify-content:center;}
  .thumb{width:58px;height:58px;}
  .main-img-box{width:100%;max-width:340px;height:320px;}
  .hero-text{width:100%;}
  .hero-title{font-size:1.6rem;}
  .btn-buy,.btn-cart{border-radius:14px;}
  .stat{padding:18px 16px;min-width:50%;}
  .stat-num{font-size:1.5rem;}
  .strip-section{padding:40px 14px 0;}
  .photo-grid{grid-template-columns:1fr 1fr;gap:12px;}
  .photo-card-inner{height:160px;font-size:3rem;}
  .section{padding:44px 14px;}
  .section-title{font-size:1.35rem;}
  .benefit-card{width:calc(50% - 12px);padding:20px 14px;}
  .how-inner{padding:0 14px;}
  .step{width:calc(50% - 10px);}
  .review-card{width:100%;max-width:380px;}
  .cta-section{padding:48px 16px;}
  .cta-title{font-size:1.4rem;}
}
@media(max-width:400px){
  .benefit-card,.step{width:100%;}
  .photo-grid{grid-template-columns:1fr;}
}
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <div class="nav-logo">✦ COSMO GLOW</div>
  <div class="lang-toggle">
    <button class="lang-btn active" id="btn-fr" onclick="setLang('fr')">FR</button>
    <button class="lang-btn" id="btn-en" onclick="setLang('en')">EN</button>
  </div>
</nav>

<!-- HERO -->
<section>
<div class="hero">

  <!-- GALERIE -->
  <div class="gallery">
    <div class="thumbs">
      <div class="thumb active" onclick="switchImg(0,this)">
        <div class="thumb-inner" style="background:linear-gradient(135deg,#f5e6d8,#e0c5a8);">🧴</div>
      </div>
      <div class="thumb" onclick="switchImg(1,this)">
        <div class="thumb-inner" style="background:linear-gradient(135deg,#e8f5e9,#c8e6c9);">🐌</div>
      </div>
      <div class="thumb" onclick="switchImg(2,this)">
        <div class="thumb-inner" style="background:linear-gradient(135deg,#fce4ec,#f8bbd0);">✨</div>
      </div>
      <div class="thumb" onclick="switchImg(3,this)">
        <div class="thumb-inner" style="background:linear-gradient(135deg,#e3f2fd,#bbdefb);">💧</div>
      </div>
    </div>

    <div class="main-img-box" id="mainBox">
      <div class="badge-red" data-i18n="hero_badge">Offre bienvenue</div>
      <div class="badge-dark" data-i18n="sold_badge">2 000+ vendus</div>
      <div class="main-visual" id="mainVisual">
        <!-- Visuel 0 : Produit -->
        <div class="bottle-visual">
          <svg width="130" height="220" viewBox="0 0 130 220" xmlns="http://www.w3.org/2000/svg">
            <defs>
              <linearGradient id="bg0" x1="0" y1="0" x2="1" y2="1">
                <stop offset="0%" stop-color="#f5e6d8"/>
                <stop offset="100%" stop-color="#e0c5a8"/>
              </linearGradient>
              <linearGradient id="bot" x1="0" y1="0" x2="1" y2="1">
                <stop offset="0%" stop-color="#fff"/>
                <stop offset="100%" stop-color="#f0e0cc"/>
              </linearGradient>
              <linearGradient id="cap" x1="0" y1="0" x2="0" y2="1">
                <stop offset="0%" stop-color="#2e1f14"/>
                <stop offset="100%" stop-color="#4a3020"/>
              </linearGradient>
            </defs>
            <!-- Body -->
            <rect x="25" y="50" width="80" height="155" rx="18" fill="url(#bot)" stroke="#d4a57a" stroke-width="1.5"/>
            <!-- Cap -->
            <rect x="35" y="18" width="60" height="38" rx="10" fill="url(#cap)"/>
            <!-- Label bg -->
            <rect x="30" y="90" width="70" height="100" rx="8" fill="#c0875a" opacity=".15"/>
            <!-- Logo snail -->
            <text x="65" y="118" text-anchor="middle" font-size="22">🐌</text>
            <!-- Product name -->
            <text x="65" y="140" text-anchor="middle" fill="#7a5c44" font-size="8" font-weight="700" letter-spacing="1">SNAIL 96</text>
            <text x="65" y="153" text-anchor="middle" fill="#7a5c44" font-size="7">MUCIN POWER</text>
            <text x="65" y="164" text-anchor="middle" fill="#7a5c44" font-size="7">ESSENCE</text>
            <!-- Volume -->
            <text x="65" y="185" text-anchor="middle" fill="#9b7355" font-size="6.5">100 ml / 3.38 fl.oz</text>
            <!-- Shine -->
            <ellipse cx="42" cy="80" rx="5" ry="14" fill="white" opacity=".3" transform="rotate(-15 42 80)"/>
          </svg>
        </div>
      </div>
    </div>
  </div>

  <!-- TEXTE -->
  <div class="hero-text">
    <div class="hero-tag" data-i18n="hero_tag">K-Beauty · SkinLuxe Store</div>
    <h1 class="hero-title" data-i18n="hero_title">Snail 96 Mucin<br/>Power Essence</h1>
    <p class="hero-sub" data-i18n="hero_subtitle">Lissante · Raffermissante · Éclat · Anti-rides · 100 ml</p>
    <div class="star-row">
      <span class="stars">★★★★☆</span>
      <span class="star-info" data-i18n="star_info">4.4 · 294 avis · <strong>2 000+ vendus</strong></span>
    </div>
    <p class="hero-desc" data-i18n="hero_desc">Formulée avec 96 % de filtrat de bave d'escargot, cette essence culte repulpe, régénère et illumine votre teint. Texture légère absorbée instantanément — résultats visibles dès 7 jours.</p>

    <!-- QUANTITÉ -->
    <div class="qty-section">
      <div class="qty-label" data-i18n="qty_label">🛍️ Choisissez votre offre</div>
      <div class="qty-options">

        <div class="qty-opt selected" id="opt1" onclick="selectQty(1)">
          <div class="qty-left">
            <div class="bottle-icons">🧴</div>
            <div>
              <div class="qty-title" data-i18n="qty1_title">1 bouteille</div>
              <div class="qty-save-txt" data-i18n="qty1_save">Prix régulier</div>
            </div>
          </div>
          <div class="qty-right">
            <div class="qty-p" data-i18n="qty1_price">24,99 $CA</div>
            <div class="qty-per" data-i18n="qty1_per">24,99 $ / unité</div>
          </div>
        </div>

        <div class="qty-opt" id="opt2" onclick="selectQty(2)">
          <div class="pop-badge" style="background:var(--green);" data-i18n="best">⭐ POPULAIRE</div>
          <div class="qty-left">
            <div class="bottle-icons">🧴🧴</div>
            <div>
              <div class="qty-title" data-i18n="qty2_title">2 bouteilles</div>
              <div class="qty-save-txt" data-i18n="qty2_save">−10% · Vous sauvez 5,00 $</div>
            </div>
          </div>
          <div class="qty-right">
            <div class="qty-p" data-i18n="qty2_price">44,98 $CA</div>
            <div class="qty-per" data-i18n="qty2_per">22,49 $ / unité</div>
          </div>
        </div>

        <div class="qty-opt" id="opt3" onclick="selectQty(3)">
          <div class="pop-badge" style="background:#b8550a;" data-i18n="bestval">🔥 MEILLEURE VALEUR</div>
          <div class="qty-left">
            <div class="bottle-icons">🧴🧴🧴</div>
            <div>
              <div class="qty-title" data-i18n="qty3_title">3 bouteilles</div>
              <div class="qty-save-txt" data-i18n="qty3_save">−20% · Vous sauvez 15,00 $</div>
            </div>
          </div>
          <div class="qty-right">
            <div class="qty-p" data-i18n="qty3_price">59,97 $CA</div>
            <div class="qty-per" data-i18n="qty3_per">19,99 $ / unité</div>
          </div>
        </div>

      </div>
    </div>

    <!-- PRIX -->
    <div class="price-box">
      <div>
        <span class="price-now" id="displayPrice">24,99 $CA</span>
        <span class="price-was" id="displayWas">49,99 $CA</span>
        <span class="price-tag" id="displaySave">−50%</span>
      </div>
      <div class="price-note" data-i18n="price_note">✓ Livraison gratuite · Livraison : 25–30 mai · Retours 90 jours</div>
    </div>

    <div class="trust-row">
      <span class="chip" data-i18n="trust1">🚚 Livraison gratuite</span>
      <span class="chip" data-i18n="trust2">🔄 Retours 90 jours</span>
      <span class="chip" data-i18n="trust3">🔒 Paiement sécurisé</span>
    </div>

    <button class="btn-buy" id="btnBuy" onclick="goToStripe()">Acheter maintenant — 24,99 $CA</button>
    <button class="btn-cart" onclick="goToStripe()" data-i18n="btn_cart">Ajouter au panier</button>
  </div>
</div>
</section>

<!-- STATS -->
<div class="stats">
  <div class="stat"><div class="stat-num">96%</div><div class="stat-label" data-i18n="stat1">Filtrat bave d'escargot</div></div>
  <div class="stat"><div class="stat-num">+2 000</div><div class="stat-label" data-i18n="stat2">Unités vendues</div></div>
  <div class="stat"><div class="stat-num">★ 4.4</div><div class="stat-label" data-i18n="stat3">294 avis vérifiés</div></div>
  <div class="stat"><div class="stat-num">90 j</div><div class="stat-label" data-i18n="stat4">Retours acceptés</div></div>
</div>

<!-- GALERIE -->
<div class="strip-section">
  <h2 class="section-title" data-i18n="gallery_title">La magie en images</h2>
  <div class="photo-grid">
    <div class="photo-card">
      <div class="photo-card-inner" style="background:linear-gradient(135deg,#f5e6d8,#e0c5a8);">🧴✨</div>
      <div class="photo-cap" data-i18n="cap1">Le produit original</div>
    </div>
    <div class="photo-card">
      <div class="photo-card-inner" style="background:linear-gradient(135deg,#e8f5e9,#c8e6c9);">🐌💚</div>
      <div class="photo-cap" data-i18n="cap2">96% filtrat naturel</div>
    </div>
    <div class="photo-card">
      <div class="photo-card-inner" style="background:linear-gradient(135deg,#fce4ec,#f8bbd0);">💆‍♀️✨</div>
      <div class="photo-cap" data-i18n="cap3">Peau lumineuse & repulpée</div>
    </div>
  </div>
</div>

<!-- BENEFITS -->
<section class="section">
  <h2 class="section-title" data-i18n="benefits_title">Pourquoi votre peau va l'adorer</h2>
  <div class="benefits">
    <div class="benefit-card"><div class="b-icon">💧</div><div class="b-title" data-i18n="b1_title">Hydratation intense</div><div class="b-desc" data-i18n="b1_desc">Pénètre en profondeur pour un effet plump durable toute la journée.</div></div>
    <div class="benefit-card"><div class="b-icon">✨</div><div class="b-title" data-i18n="b2_title">Éclat & uniformité</div><div class="b-desc" data-i18n="b2_desc">Estompe les taches sombres et unifie le teint en quelques semaines.</div></div>
    <div class="benefit-card"><div class="b-icon">🔄</div><div class="b-title" data-i18n="b3_title">Anti-rides</div><div class="b-desc" data-i18n="b3_desc">Stimule le renouvellement cellulaire pour atténuer les ridules.</div></div>
    <div class="benefit-card"><div class="b-icon">💪</div><div class="b-title" data-i18n="b4_title">Raffermissante</div><div class="b-desc" data-i18n="b4_desc">Améliore l'élasticité et la fermeté de la peau au fil du temps.</div></div>
    <div class="benefit-card"><div class="b-icon">🌿</div><div class="b-title" data-i18n="b5_title">Formule douce</div><div class="b-desc" data-i18n="b5_desc">Sans parabènes ni parfum. Idéale pour peaux sensibles et acnéiques.</div></div>
  </div>
</section>

<!-- HOW -->
<div class="how">
<div class="how-inner">
  <h2 class="section-title" data-i18n="how_title">Comment l'utiliser</h2>
  <div class="steps">
    <div class="step"><div class="step-num">1</div><div class="step-text" data-i18n="step1">Nettoyez et appliquez votre tonique habituel.</div></div>
    <div class="step"><div class="step-num">2</div><div class="step-text" data-i18n="step2">Versez 2–3 gouttes dans votre paume.</div></div>
    <div class="step"><div class="step-num">3</div><div class="step-text" data-i18n="step3">Tapotez sur le visage et le cou.</div></div>
    <div class="step"><div class="step-num">4</div><div class="step-text" data-i18n="step4">Terminez avec votre crème ou FPS.</div></div>
  </div>
</div>
</div>

<!-- REVIEWS -->
<section class="section" style="padding-top:0;">
  <h2 class="section-title" data-i18n="reviews_title">Avis clients vérifiés</h2>
  <div class="reviews">
    <div class="review-card">
      <div class="r-stars">★★★★★</div>
      <p class="r-text" data-i18n="r1_text">« Ma peau n'a jamais été aussi douce et lumineuse. Mes amies me demandent ce que j'ai changé ! »</p>
      <div class="r-author" data-i18n="r1_author">— Amélie L., Montréal ✓</div>
    </div>
    <div class="review-card">
      <div class="r-stars">★★★★★</div>
      <p class="r-text" data-i18n="r2_text">« Peau sensible — zéro irritation, texture ultra soyeuse. J'en ai commandé 3 bouteilles ! »</p>
      <div class="r-author" data-i18n="r2_author">— Sofia M., Québec ✓</div>
    </div>
    <div class="review-card">
      <div class="r-stars">★★★★☆</div>
      <p class="r-text" data-i18n="r3_text">« Mes ridules sont visiblement atténuées après un mois. Je recommande l'offre 3 bouteilles ! »</p>
      <div class="r-author" data-i18n="r3_author">— Martine D., Laval ✓</div>
    </div>
  </div>
</section>

<!-- CTA -->
<section class="cta-section">
  <h2 class="cta-title" data-i18n="cta_title">Prête à transformer votre routine beauté ?</h2>
  <p class="cta-sub" data-i18n="cta_sub">🔥 Jusqu'à −20% · Livraison gratuite · Retours 90 jours</p>
  <button class="btn-white" onclick="goToStripe()" data-i18n="cta_btn">Commander maintenant →</button>
</section>

<footer><span data-i18n="footer">© 2026 Cosmo Glow · Tous droits réservés</span></footer>

<script>
// ── STRIPE ──
const STRIPE_LINKS = {
  1: "https://buy.stripe.com/test_fZu8wP5sUdiy2Uq9U32go00",
  2: "https://buy.stripe.com/test_3cIeVddZqceu1Qm6HR2go01",
  3: "https://buy.stripe.com/test_dRm5kD5sU7YebqW2rB2go02"
};
function goToStripe() {
  window.open(STRIPE_LINKS[currentQty], '_blank');
}

// ── GALLERY VISUALS ──
const visuals = [
  `<div class="bottle-visual">
    <svg width="130" height="220" viewBox="0 0 130 220" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <linearGradient id="bot" x1="0" y1="0" x2="1" y2="1"><stop offset="0%" stop-color="#fff"/><stop offset="100%" stop-color="#f0e0cc"/></linearGradient>
        <linearGradient id="cap" x1="0" y1="0" x2="0" y2="1"><stop offset="0%" stop-color="#2e1f14"/><stop offset="100%" stop-color="#4a3020"/></linearGradient>
      </defs>
      <rect x="25" y="50" width="80" height="155" rx="18" fill="url(#bot)" stroke="#d4a57a" stroke-width="1.5"/>
      <rect x="35" y="18" width="60" height="38" rx="10" fill="url(#cap)"/>
      <rect x="30" y="90" width="70" height="100" rx="8" fill="#c0875a" opacity=".15"/>
      <text x="65" y="118" text-anchor="middle" font-size="22">🐌</text>
      <text x="65" y="140" text-anchor="middle" fill="#7a5c44" font-size="8" font-weight="700" letter-spacing="1">SNAIL 96</text>
      <text x="65" y="153" text-anchor="middle" fill="#7a5c44" font-size="7">MUCIN POWER</text>
      <text x="65" y="164" text-anchor="middle" fill="#7a5c44" font-size="7">ESSENCE</text>
      <text x="65" y="185" text-anchor="middle" fill="#9b7355" font-size="6.5">100 ml / 3.38 fl.oz</text>
      <ellipse cx="42" cy="80" rx="5" ry="14" fill="white" opacity=".3" transform="rotate(-15 42 80)"/>
    </svg>
  </div>`,
  `<div style="text-align:center;padding:20px;">
    <div style="font-size:5rem;margin-bottom:16px;">🐌</div>
    <div style="font-size:1.1rem;font-weight:800;color:#7a5c44;margin-bottom:8px;">96% Mucin Filtrate</div>
    <div style="font-size:.85rem;color:#9b7355;line-height:1.6;max-width:220px;">Ingrédient naturel récolté éthiquement · Zéro cruauté animale</div>
    <div style="margin-top:16px;font-size:2rem;">🌿✨</div>
  </div>`,
  `<div style="text-align:center;padding:24px;">
    <div style="font-size:4rem;margin-bottom:12px;">💆‍♀️</div>
    <div style="font-size:1rem;font-weight:800;color:#7a5c44;margin-bottom:12px;">Résultats visibles</div>
    <div style="display:flex;flex-direction:column;gap:8px;align-items:center;">
      <div style="background:#fff3e8;border-radius:12px;padding:8px 16px;font-size:.8rem;color:#7a5c44;font-weight:600;">Jour 7 — Hydratation +40%</div>
      <div style="background:#fff3e8;border-radius:12px;padding:8px 16px;font-size:.8rem;color:#7a5c44;font-weight:600;">Jour 14 — Éclat visible</div>
      <div style="background:#fff3e8;border-radius:12px;padding:8px 16px;font-size:.8rem;color:#7a5c44;font-weight:600;">Jour 30 — Peau repulpée ✨</div>
    </div>
  </div>`,
  `<div style="text-align:center;padding:20px;">
    <div style="font-size:4rem;margin-bottom:14px;">💧</div>
    <div style="font-size:1rem;font-weight:800;color:#7a5c44;margin-bottom:10px;">Texture Ultra-Légère</div>
    <div style="font-size:.83rem;color:#9b7355;line-height:1.6;margin-bottom:14px;">S'absorbe en secondes · Sans résidu · Compatible toutes peaux</div>
    <div style="display:flex;justify-content:center;gap:8px;flex-wrap:wrap;">
      <span style="background:#e8f5e9;color:#2e7d32;font-size:.72rem;font-weight:700;padding:4px 10px;border-radius:12px;">✓ Sans parfum</span>
      <span style="background:#e8f5e9;color:#2e7d32;font-size:.72rem;font-weight:700;padding:4px 10px;border-radius:12px;">✓ Sans parabènes</span>
      <span style="background:#e8f5e9;color:#2e7d32;font-size:.72rem;font-weight:700;padding:4px 10px;border-radius:12px;">✓ Vegan</span>
    </div>
  </div>`
];

const bgColors = [
  "linear-gradient(135deg,#f5e6d8,#e8d0b8)",
  "linear-gradient(135deg,#e8f5e9,#c8e6c9)",
  "linear-gradient(135deg,#fce4ec,#f8bbd0)",
  "linear-gradient(135deg,#e3f2fd,#bbdefb)"
];

function switchImg(i, el) {
  document.getElementById('mainVisual').innerHTML = visuals[i];
  document.getElementById('mainBox').style.background = bgColors[i];
  document.querySelectorAll('.thumb').forEach(t => t.classList.remove('active'));
  el.classList.add('active');
}
// Init background
document.getElementById('mainBox').style.background = bgColors[0];

// ── QUANTITY ──
const qtyData = {
  fr:{
    1:{price:"24,99 $CA",was:"49,99 $CA",save:"−50%",btn:"Acheter maintenant — 24,99 $CA"},
    2:{price:"44,98 $CA",was:"49,98 $CA",save:"−10%",btn:"Acheter 2 bouteilles — 44,98 $CA"},
    3:{price:"59,97 $CA",was:"74,97 $CA",save:"−20%",btn:"Acheter 3 bouteilles — 59,97 $CA"}
  },
  en:{
    1:{price:"CA$24.99",was:"CA$49.99",save:"−50%",btn:"Buy Now — CA$24.99"},
    2:{price:"CA$44.98",was:"CA$49.98",save:"−10%",btn:"Buy 2 Bottles — CA$44.98"},
    3:{price:"CA$59.97",was:"CA$74.97",save:"−20%",btn:"Buy 3 Bottles — CA$59.97"}
  }
};
let currentLang='fr', currentQty=1;

function selectQty(n){
  currentQty=n;
  [1,2,3].forEach(i=>document.getElementById('opt'+i).classList.toggle('selected',i===n));
  updatePrice();
}
function updatePrice(){
  const d=qtyData[currentLang][currentQty];
  document.getElementById('displayPrice').textContent=d.price;
  document.getElementById('displayWas').textContent=d.was;
  document.getElementById('displaySave').textContent=d.save;
  document.getElementById('btnBuy').textContent=d.btn;
}

// ── i18n ──
const i18n={
  fr:{
    hero_badge:"Offre bienvenue",sold_badge:"2 000+ vendus",
    hero_tag:"K-Beauty · SkinLuxe Store",
    hero_title:"Snail 96 Mucin<br/>Power Essence",
    hero_subtitle:"Lissante · Raffermissante · Éclat · Anti-rides · 100 ml",
    star_info:"4.4 · 294 avis · <strong>2 000+ vendus</strong>",
    hero_desc:"Formulée avec 96 % de filtrat de bave d'escargot, cette essence culte repulpe, régénère et illumine votre teint. Texture légère absorbée instantanément — résultats visibles dès 7 jours.",
    qty_label:"🛍️ Choisissez votre offre",
    qty1_title:"1 bouteille",qty1_save:"Prix régulier",qty1_price:"24,99 $CA",qty1_per:"24,99 $ / unité",
    qty2_title:"2 bouteilles",qty2_save:"−10% · Vous sauvez 5,00 $",qty2_price:"44,98 $CA",qty2_per:"22,49 $ / unité",
    qty3_title:"3 bouteilles",qty3_save:"−20% · Vous sauvez 15,00 $",qty3_price:"59,97 $CA",qty3_per:"19,99 $ / unité",
    best:"⭐ POPULAIRE",bestval:"🔥 MEILLEURE VALEUR",
    price_note:"✓ Livraison gratuite · Livraison : 25–30 mai · Retours 90 jours",
    trust1:"🚚 Livraison gratuite",trust2:"🔄 Retours 90 jours",trust3:"🔒 Paiement sécurisé",
    btn_cart:"Ajouter au panier",
    stat1:"Filtrat bave d'escargot",stat2:"Unités vendues",stat3:"294 avis vérifiés",stat4:"Retours acceptés",
    gallery_title:"La magie en images",
    cap1:"Le produit original",cap2:"96% filtrat naturel",cap3:"Peau lumineuse & repulpée",
    benefits_title:"Pourquoi votre peau va l'adorer",
    b1_title:"Hydratation intense",b1_desc:"Pénètre en profondeur pour un effet plump durable toute la journée.",
    b2_title:"Éclat & uniformité",b2_desc:"Estompe les taches sombres et unifie le teint en quelques semaines.",
    b3_title:"Anti-rides",b3_desc:"Stimule le renouvellement cellulaire pour atténuer les ridules.",
    b4_title:"Raffermissante",b4_desc:"Améliore l'élasticité et la fermeté de la peau au fil du temps.",
    b5_title:"Formule douce",b5_desc:"Sans parabènes ni parfum. Idéale pour peaux sensibles et acnéiques.",
    how_title:"Comment l'utiliser",
    step1:"Nettoyez et appliquez votre tonique habituel.",
    step2:"Versez 2–3 gouttes dans votre paume.",
    step3:"Tapotez sur le visage et le cou.",
    step4:"Terminez avec votre crème ou FPS.",
    reviews_title:"Avis clients vérifiés",
    r1_text:"« Ma peau n'a jamais été aussi douce et lumineuse. Mes amies me demandent ce que j'ai changé ! »",
    r1_author:"— Amélie L., Montréal ✓",
    r2_text:"« Peau sensible — zéro irritation, texture ultra soyeuse. J'en ai commandé 3 bouteilles ! »",
    r2_author:"— Sofia M., Québec ✓",
    r3_text:"« Mes ridules sont visiblement atténuées après un mois. Je recommande l'offre 3 bouteilles ! »",
    r3_author:"— Martine D., Laval ✓",
    cta_title:"Prête à transformer votre routine beauté ?",
    cta_sub:"🔥 Jusqu'à −20% · Livraison gratuite · Retours 90 jours",
    cta_btn:"Commander maintenant →",
    footer:"© 2026 Cosmo Glow · Tous droits réservés"
  },
  en:{
    hero_badge:"Welcome Deal",sold_badge:"2,000+ sold",
    hero_tag:"K-Beauty · SkinLuxe Store",
    hero_title:"Snail 96 Mucin<br/>Power Essence",
    hero_subtitle:"Smoothing · Firming · Brightening · Anti-Wrinkle · 100 ml",
    star_info:"4.4 · 294 reviews · <strong>2,000+ sold</strong>",
    hero_desc:"Powered by 96% snail secretion filtrate, this cult essence plumps, repairs, and illuminates your complexion. Lightweight formula absorbed instantly — visible results in as little as 7 days.",
    qty_label:"🛍️ Choose Your Bundle",
    qty1_title:"1 Bottle",qty1_save:"Regular price",qty1_price:"CA$24.99",qty1_per:"$24.99 / unit",
    qty2_title:"2 Bottles",qty2_save:"−10% · You save $5.00",qty2_price:"CA$44.98",qty2_per:"$22.49 / unit",
    qty3_title:"3 Bottles",qty3_save:"−20% · You save $15.00",qty3_price:"CA$59.97",qty3_per:"$19.99 / unit",
    best:"⭐ POPULAR",bestval:"🔥 BEST VALUE",
    price_note:"✓ Free shipping · Delivery: May 25–30 · 90-day returns",
    trust1:"🚚 Free Shipping",trust2:"🔄 90-Day Returns",trust3:"🔒 Secure Payment",
    btn_cart:"Add to Cart",
    stat1:"Snail secretion filtrate",stat2:"Units sold",stat3:"294 verified reviews",stat4:"Returns accepted",
    gallery_title:"The Magic in Pictures",
    cap1:"The original product",cap2:"96% natural filtrate",cap3:"Glowing & plump skin",
    benefits_title:"Why Your Skin Will Love It",
    b1_title:"Deep Hydration",b1_desc:"Absorbs fast for a lasting plump effect that keeps skin bouncy all day.",
    b2_title:"Glow & Even Tone",b2_desc:"Visibly fades dark spots and evens skin tone within just a few weeks.",
    b3_title:"Anti-Wrinkle",b3_desc:"Boosts cell renewal to smooth fine lines and restore a youthful look.",
    b4_title:"Firming",b4_desc:"Improves skin elasticity and firmness with consistent use over time.",
    b5_title:"Gentle Formula",b5_desc:"Fragrance-free & paraben-free. Great for sensitive and acne-prone skin.",
    how_title:"How To Use It",
    step1:"Cleanse your face and apply your toner.",
    step2:"Dispense 2–3 drops into your palm.",
    step3:"Pat gently onto face and neck.",
    step4:"Finish with moisturizer or SPF.",
    reviews_title:"Verified Customer Reviews",
    r1_text:"\"My skin has never felt this soft and glowing. Everyone is asking what I changed!\"",
    r1_author:"— Emily R., Toronto ✓",
    r2_text:"\"Sensitive skin here — zero irritation, silky texture. I ordered 3 bottles!\"",
    r2_author:"— Sarah M., Vancouver ✓",
    r3_text:"\"Fine lines visibly softer after one month. I highly recommend the 3-bottle bundle!\"",
    r3_author:"— Jessica D., Calgary ✓",
    cta_title:"Ready to Transform Your Skincare Routine?",
    cta_sub:"🔥 Up to −20% off · Free shipping · 90-day returns",
    cta_btn:"Order Now →",
    footer:"© 2026 Cosmo Glow · All rights reserved"
  }
};

function setLang(lang){
  currentLang=lang;
  const t=i18n[lang];
  document.querySelectorAll('[data-i18n]').forEach(el=>{
    const k=el.getAttribute('data-i18n');
    if(t[k]!==undefined) el.innerHTML=t[k];
  });
  document.getElementById('btn-fr').classList.toggle('active',lang==='fr');
  document.getElementById('btn-en').classList.toggle('active',lang==='en');
  document.documentElement.lang=lang;
  updatePrice();
}
</script>
</body>
</html>
