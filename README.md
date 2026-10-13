<!doctype html>
<html lang="fr">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <meta content="#101828" name="theme-color"/>
  <meta content="Pc Apps Store &mdash; appareils &eacute;lectroniques, prix transparents et livraison au Cameroun." name="description"/>
  <title>
   Pc Apps Store &mdash; Technologie en confiance
  </title>
  <link href="https://images.unsplash.com" rel="preconnect"/>
  <link href="styles.css" rel="stylesheet"/>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" rel="stylesheet"/>
 </head>
 <body>
  <!-- Barre d’annonce, identité du site et recherche globale. -->
  <div class="announcement">
   <span>
    <i class="fa-solid fa-truck-fast">
    </i>
    Livraison au Cameroun
   </span>
   <span>
    Prix transparents &middot; Paiement mobile s&eacute;curis&eacute; &agrave; int&eacute;grer
   </span>
   <button aria-label="Fermer l'annonce" id="dismissAnnouncement">
    <i class="fa-solid fa-xmark">
    </i>
   </button>
  </div>
  <header class="topbar">
   <a aria-label="Pc Apps Store accueil public" class="brand" href="#landing">
    <span class="brand-mark">
     <i class="fa-solid fa-bolt">
     </i>
    </span>
    <span>
     pc
     <span class="brand-accent">
      apps
     </span>
     <small>
      STORE &middot; CAMEROUN
     </small>
    </span>
   </a>
   <form class="searchbar" id="searchForm" role="search">
    <i class="fa-solid fa-magnifying-glass">
    </i>
    <input aria-label="Rechercher un produit" id="globalSearch" placeholder="Rechercher un PC, un t&eacute;l&eacute;phone, une marque&hellip;" type="search"/>
    <kbd>
     &crarr;
    </kbd>
   </form>
   <div class="top-actions">
    <button aria-label="Mes commandes" class="icon-btn desktop-only" data-view="orders">
     <i class="fa-regular fa-rectangle-list">
     </i>
    </button>
    <button aria-label="Ouvrir le panier" class="icon-btn cart-top" data-view="cart">
     <i class="fa-solid fa-bag-shopping">
     </i>
     <span class="cart-count" id="cartCount">
      0
     </span>
    </button>
    <button class="account-btn" id="accountBtn">
     <i class="fa-regular fa-user">
     </i>
     <span id="accountLabel">
      Se connecter
     </span>
    </button>
    <button aria-label="Ouvrir le menu" class="menu-toggle" id="menuToggle">
     <i class="fa-solid fa-bars">
     </i>
    </button>
   </div>
  </header>
  <!-- Navigation horizontale pour les écrans moyens et grands. -->
  <nav aria-label="Navigation principale" class="desktop-nav">
   <a class="active" data-public="landing" href="#landing">
    D&eacute;couvrir
   </a>
   <a data-view="catalogue" href="#catalogue">
    Catalogue
   </a>
   <a data-view="promotions" href="#promotions">
    Promotions
   </a>
   <a data-view="annonces" href="#annonces">
    Annonces
   </a>
   <a data-public="about" href="#about">
    Pourquoi Pc Apps
   </a>
   <span class="nav-spacer">
   </span>
   <span class="secure-note">
    <i class="fa-solid fa-shield-halved">
    </i>
    Achat en toute confiance
   </span>
  </nav>
  <!-- Vues principales : landing publique, espace client, catalogue et vues secondaires. -->
  <main id="appMain">
   <section class="view public-view" id="landingView">
    <div aria-label="D&eacute;couvrir les cat&eacute;gories de produits" aria-roledescription="carrousel" class="hero-wrap" id="heroCarousel">
     <div class="hero-copy">
      <span class="eyebrow">
       <span class="eyebrow-dot">
       </span>
       LA TECHNOLOGIE, EN TOUTE CONFIANCE
      </span>
      <span class="hero-category" id="heroCategory">
       ORDINATEURS &amp; INFORMATIQUE
      </span>
      <h1 id="heroTitle">
       Le bon appareil.
       <br/>
       <span>
        Le bon choix.
       </span>
      </h1>
      <p id="heroDescription">
       Des appareils soigneusement pr&eacute;sent&eacute;s, des caract&eacute;ristiques claires et une exp&eacute;rience d'achat pens&eacute;e pour le Cameroun.
      </p>
      <div class="hero-actions">
       <button class="btn btn-primary" data-view="catalogue" id="heroCta">
        Explorer les ordinateurs
        <i class="fa-solid fa-arrow-right">
        </i>
       </button>
       <a class="text-link" href="#brands">
        D&eacute;couvrir les marques
        <i class="fa-solid fa-arrow-down">
        </i>
       </a>
      </div>
      <div class="hero-proof">
       <div class="proof-avatars">
        <span>
         PC
        </span>
        <span>
         SM
        </span>
        <span>
         TV
        </span>
       </div>
       <div>
        <strong>
         Un catalogue pens&eacute; pour vous
        </strong>
        <small>
         Comparez avant de choisir.
        </small>
       </div>
       <div class="proof-divider">
       </div>
       <div>
        <strong>
         <i class="fa-solid fa-circle-check green">
         </i>
         Clart&eacute; d'abord
        </strong>
        <small>
         Prix et caract&eacute;ristiques visibles
        </small>
       </div>
      </div>
      <div aria-label="Contr&ocirc;les du carrousel" class="hero-carousel-controls">
       <button aria-label="Cat&eacute;gorie pr&eacute;c&eacute;dente" id="heroPrevious" type="button" hidden>
        <i class="fa-solid fa-arrow-left">
        </i>
       </button>
       <div aria-label="Choisir une cat&eacute;gorie" class="hero-dots" id="heroDots">
       </div>
       <button aria-label="Cat&eacute;gorie suivante" id="heroNext" type="button" hidden>
        <i class="fa-solid fa-arrow-right">
        </i>
       </button>
      </div>
     </div>
     <div class="hero-visual">
      <div aria-label="S&eacute;lection d'appareils &eacute;lectroniques" class="hero-image" id="heroImage" role="img">
      </div>
      <div class="floating-tag tag-top">
       <span class="tag-icon">
        <i class="fa-solid fa-microchip" id="heroFeatureIcon">
        </i>
       </span>
       <span>
        <b id="heroFeatureTitle">
         Choix &eacute;clair&eacute;
        </b>
        <small id="heroFeatureText">
         Les infos essentielles, sans d&eacute;tour
        </small>
       </span>
      </div>
      <div class="floating-tag tag-bottom">
       <span class="stock-pulse">
       </span>
       <span>
        <b id="heroBottomTitle">
         Catalogue dynamique
        </b>
        <small id="heroBottomText">
         Disponibilit&eacute; affich&eacute;e par variante
        </small>
       </span>
      </div>
      <div class="hero-index" id="heroIndex">
       01
       <span>
        /
       </span>
       05
      </div>
     </div>
    </div>
    <div class="trust-strip">
     <div>
      <i class="fa-solid fa-list-check">
      </i>
      <span>
       <b>
        Fiches d&eacute;taill&eacute;es
       </b>
       <small>
        Comparez les caract&eacute;ristiques
       </small>
      </span>
     </div>
     <div>
      <i class="fa-solid fa-tags">
      </i>
      <span>
       <b>
        Promotions lisibles
       </b>
       <small>
        Prix normal et prix r&eacute;duit
       </small>
      </span>
     </div>
     <div>
      <i class="fa-solid fa-mobile-screen-button">
      </i>
      <span>
       <b>
        Paiement mobile
       </b>
       <small>
        MTN / Orange selon int&eacute;gration
       </small>
      </span>
     </div>
     <div>
      <i class="fa-solid fa-truck">
      </i>
      <span>
       <b>
        Livraison suivie
       </b>
       <small>
        Statuts distincts et tra&ccedil;ables
       </small>
      </span>
     </div>
    </div>
    <section class="section-block" id="brands">
     <div class="section-heading">
      <div>
       <span class="eyebrow muted-eyebrow">
        TROUVEZ VOTRE UNIVERS
       </span>
       <h2>
        Les marques, sans d&eacute;tour.
       </h2>
       <p>
        Explorez les appareils par marque et d&eacute;couvrez les cat&eacute;gories disponibles.
       </p>
      </div>
      <button class="plain-link" data-view="catalogue">
       Toutes les marques
       <i class="fa-solid fa-arrow-right">
       </i>
      </button>
     </div>
     <div class="brand-grid" id="brandGrid">
     </div>
    </section>
    <section class="section-block tinted-section" id="popular">
     <div class="section-heading">
      <div>
       <span class="eyebrow muted-eyebrow">
        S&Eacute;LECTION DU MOMENT
       </span>
       <h2>
        Des choix qui font la diff&eacute;rence.
       </h2>
       <p>
        D&eacute;couvrez une s&eacute;lection de d&eacute;monstration, rempla&ccedil;able par le catalogue r&eacute;el.
       </p>
      </div>
      <button class="plain-link" data-view="catalogue">
       Voir le catalogue
       <i class="fa-solid fa-arrow-right">
       </i>
      </button>
     </div>
     <div class="product-grid" id="featuredGrid">
     </div>
    </section>
    <section class="promo-banner" id="promotions">
     <div>
      <span class="eyebrow light-eyebrow">
       BONNES AFFAIRES &middot; SANS SURPRISE
      </span>
      <h2>
       Une promotion claire.
       <br/>
       Un choix ma&icirc;tris&eacute;.
      </h2>
      <p>
       Le prix r&eacute;duit, l'ancien prix et la p&eacute;riode sont pr&eacute;sent&eacute;s distinctement lorsqu'une promotion est active.
      </p>
      <button class="btn btn-light" data-view="promotions">
       Voir les promotions
       <i class="fa-solid fa-arrow-right">
       </i>
      </button>
     </div>
     <div class="promo-art">
      <div class="promo-orbit orbit-one">
      </div>
      <div class="promo-orbit orbit-two">
      </div>
      <div class="promo-device">
       <i class="fa-solid fa-laptop">
       </i>
      </div>
      <span class="promo-percent">
       OFFRES
       <br/>
       <b>
        NETTES
       </b>
      </span>
     </div>
    </section>
    <section class="section-block community-block" id="annonces">
     <div class="section-heading">
      <div>
       <span class="eyebrow muted-eyebrow">
        LA VIE DE LA COMMUNAUT&Eacute;
       </span>
       <h2>
        Les annonces &agrave; d&eacute;couvrir.
       </h2>
       <p>
        Les annonces et commentaires sont soumis &agrave; validation avant publication.
       </p>
      </div>
      <button class="plain-link" data-view="annonces">
       Voir les annonces
       <i class="fa-solid fa-arrow-right">
       </i>
      </button>
     </div>
     <div class="notice-card">
      <span class="notice-icon">
       <i class="fa-regular fa-message">
       </i>
      </span>
      <div>
       <b>
        Des informations utiles, au m&ecirc;me endroit.
       </b>
       <p>
        Consultez les annonces publi&eacute;es et les informations valid&eacute;es par l'&eacute;quipe Pc Apps Store.
       </p>
      </div>
      <button class="btn btn-outline" data-view="annonces">
       Consulter
       <i class="fa-solid fa-arrow-right">
       </i>
      </button>
     </div>
    </section>
    <section class="about-strip" id="about">
     <div>
      <span class="eyebrow muted-eyebrow">
       NOTRE ENGAGEMENT
      </span>
      <h2>
       Moins de confusion.
       <br/>
       <span>
        Plus de confiance.
       </span>
      </h2>
     </div>
     <p>
      Pc Apps Store est con&ccedil;u pour rendre les informations produit plus accessibles, faciliter la comparaison et rendre le parcours d'achat plus lisible &mdash; du catalogue au suivi de commande.
     </p>
     <button class="btn btn-primary" id="aboutSignup">
      Cr&eacute;er mon compte
      <i class="fa-solid fa-arrow-right">
      </i>
     </button>
    </section>
   </section>
   <section class="view app-view hidden" id="clientView">
    <div class="app-greeting">
     <div>
      <span class="eyebrow muted-eyebrow">
       VOTRE ESPACE
      </span>
      <h1 id="greetingTitle">
       Bonjour, bienvenue.
      </h1>
      <p>
       Retrouvez les nouveaut&eacute;s, vos s&eacute;lections et le suivi de vos achats.
      </p>
     </div>
     <button class="btn btn-outline" data-view="catalogue">
      <i class="fa-solid fa-magnifying-glass">
      </i>
      Explorer
     </button>
    </div>
    <div class="quick-stats">
     <button data-view="orders">
      <span class="stat-icon lavender">
       <i class="fa-solid fa-box">
       </i>
      </span>
      <span>
       <small>
        Mes commandes
       </small>
       <b id="orderStat">
        0 commande
       </b>
      </span>
      <i class="fa-solid fa-chevron-right">
      </i>
     </button>
     <button data-view="cart">
      <span class="stat-icon peach">
       <i class="fa-solid fa-bag-shopping">
       </i>
      </span>
      <span>
       <small>
        Mon panier
       </small>
       <b id="cartStat">
        0 article
       </b>
      </span>
      <i class="fa-solid fa-chevron-right">
      </i>
     </button>
     <button data-view="promotions">
      <span class="stat-icon mint">
       <i class="fa-solid fa-percent">
       </i>
      </span>
      <span>
       <small>
        &Agrave; ne pas manquer
       </small>
       <b>
        Promotions
       </b>
      </span>
      <i class="fa-solid fa-chevron-right">
      </i>
     </button>
    </div>
    <section class="section-block compact-block">
     <div class="section-heading">
      <div>
       <span class="eyebrow muted-eyebrow">
        POUR VOUS
       </span>
       <h2>
        &Agrave; d&eacute;couvrir aujourd'hui
       </h2>
      </div>
      <button class="plain-link" data-view="catalogue">
       Tout voir
       <i class="fa-solid fa-arrow-right">
       </i>
      </button>
     </div>
     <div class="product-grid" id="clientFeaturedGrid">
     </div>
    </section>
    <section class="member-note">
     <i class="fa-solid fa-circle-info">
     </i>
     <div>
      <b>
       Vos informations restent sous votre contr&ocirc;le.
      </b>
      <p>
       Cette d&eacute;monstration utilise des donn&eacute;es locales fictives. L'authentification et les donn&eacute;es r&eacute;elles seront connect&eacute;es au backend plus tard.
      </p>
     </div>
    </section>
   </section>
   <section class="view content-view hidden" id="catalogueView">
    <div class="page-title-row">
     <div>
      <span class="eyebrow muted-eyebrow">
       TROUVER LE BON PRODUIT
      </span>
      <h1>
       Catalogue
      </h1>
      <p>
       Filtrez et comparez les produits par marque, cat&eacute;gorie et budget.
      </p>
     </div>
     <span class="result-count" id="resultCount">
      0 produits
     </span>
    </div>
    <div class="catalogue-layout">
     <aside class="filter-panel">
      <div class="filter-title">
       <b>
        <i class="fa-solid fa-sliders">
        </i>
        Filtres
       </b>
       <button id="resetFilters">
        R&eacute;initialiser
       </button>
      </div>
      <label class="field-label" for="brandFilter">
       Marque
      </label>
      <select id="brandFilter">
       <option value="all">
        Toutes les marques
       </option>
      </select>
      <label class="field-label" for="categoryFilter">
       Cat&eacute;gorie
      </label>
      <select id="categoryFilter">
       <option value="all">
        Toutes les cat&eacute;gories
       </option>
       <option>
        Ordinateurs
       </option>
       <option>
        T&eacute;l&eacute;phones
       </option>
       <option>
        T&eacute;l&eacute;viseurs
       </option>
       <option>
        Audio
       </option>
       <option>
        &Eacute;lectrom&eacute;nager
       </option>
      </select>
      <label class="field-label" for="availabilityFilter">
       Disponibilit&eacute;
      </label>
      <select id="availabilityFilter">
       <option value="all">
        Toutes
       </option>
       <option value="in">
        En stock
       </option>
       <option value="out">
        Indisponible
       </option>
      </select>
      <label class="field-label" for="sortFilter">
       Trier par
      </label>
      <select id="sortFilter">
       <option value="featured">
        Recommand&eacute;s
       </option>
       <option value="price-asc">
        Prix croissant
       </option>
       <option value="price-desc">
        Prix d&eacute;croissant
       </option>
       <option value="name">
        Nom A&ndash;Z
       </option>
      </select>
      <div class="filter-note">
       <i class="fa-solid fa-circle-info">
       </i>
       Les prix et stocks affich&eacute;s sont fictifs pour cette maquette.
      </div>
     </aside>
     <div class="catalogue-results">
      <div class="mobile-filter-row">
       <button id="mobileFilters">
        <i class="fa-solid fa-sliders">
        </i>
        Filtres
       </button>
       <select aria-label="Trier les produits" id="mobileSort">
        <option value="featured">
         Recommand&eacute;s
        </option>
        <option value="price-asc">
         Prix croissant
        </option>
        <option value="price-desc">
         Prix d&eacute;croissant
        </option>
       </select>
      </div>
      <div class="product-grid" id="catalogueGrid">
      </div>
      <div class="empty-state hidden" id="catalogueEmpty">
       <i class="fa-solid fa-magnifying-glass">
       </i>
       <h3>
        Aucun produit trouv&eacute;
       </h3>
       <p>
        Essayez de modifier les filtres ou la recherche.
       </p>
       <button class="btn btn-outline" id="emptyReset">
        R&eacute;initialiser les filtres
       </button>
      </div>
     </div>
    </div>
   </section>
   <section class="view content-view hidden" id="productView">
    <button class="back-link" data-view="catalogue">
     <i class="fa-solid fa-arrow-left">
     </i>
     Retour au catalogue
    </button>
    <div id="productDetail">
    </div>
   </section>
   <section class="view content-view hidden" id="cartView">
    <div class="page-title-row">
     <div>
      <span class="eyebrow muted-eyebrow">
       AVANT DE COMMANDER
      </span>
      <h1>
       Mon panier
      </h1>
      <p>
       V&eacute;rifiez les variantes, les quantit&eacute;s et le montant estim&eacute;.
      </p>
     </div>
     <span class="result-count" id="cartPageCount">
      0 article
     </span>
    </div>
    <div id="cartContent">
    </div>
   </section>
   <section class="view content-view hidden" id="ordersView">
    <div class="page-title-row">
     <div>
      <span class="eyebrow muted-eyebrow">
       SUIVI TRANSPARENT
      </span>
      <h1>
       Mes commandes
      </h1>
      <p>
       La commande, le paiement et la livraison poss&egrave;dent des &eacute;tats distincts.
      </p>
     </div>
    </div>
    <div id="ordersContent">
    </div>
   </section>
   <section class="view content-view hidden" id="promotionsView">
    <div class="page-title-row">
     <div>
      <span class="eyebrow muted-eyebrow">
       OFFRES ACTIVES
      </span>
      <h1>
       Promotions
      </h1>
      <p>
       Les offres ciblent une variante et leurs prix sont clairement distingu&eacute;s.
      </p>
     </div>
    </div>
    <div class="product-grid" id="promotionsGrid">
    </div>
   </section>
   <section class="view content-view hidden" id="annoncesView">
    <div class="page-title-row">
     <div>
      <span class="eyebrow muted-eyebrow">
       INFORMATIONS VALID&Eacute;ES
      </span>
      <h1>
       Annonces
      </h1>
      <p>
       Les annonces et commentaires sont mod&eacute;r&eacute;s avant d'&ecirc;tre rendus visibles.
      </p>
     </div>
     <button class="btn btn-primary" id="newAnnouncement">
      <i class="fa-solid fa-plus">
      </i>
      Proposer une annonce
     </button>
    </div>
    <div class="announcement-list" id="announcementList">
    </div>
   </section>
   <section class="view content-view hidden" id="accountView">
    <div class="page-title-row">
     <div>
      <span class="eyebrow muted-eyebrow">
       ESPACE PERSONNEL
      </span>
      <h1>
       Mon compte
      </h1>
      <p>
       Informations de profil et historique de d&eacute;monstration.
      </p>
     </div>
    </div>
    <div id="accountContent">
    </div>
   </section>
   <!-- Espace administrateur : prototypes des outils de gestion métier. -->
   <section class="view content-view hidden" id="adminView">
    <div class="page-title-row">
     <div><span class="eyebrow muted-eyebrow">ESPACE DE GESTION · DÉMO</span><h1>Administration</h1><p>Pilotez le catalogue, les équipes, les commandes et la modération.</p></div>
     <span class="demo-badge">MODE DÉMONSTRATION</span>
    </div>
    <div class="admin-metrics" id="adminMetrics" aria-live="polite"></div>
    <div class="admin-workspace">
     <nav class="admin-tabs" aria-label="Rubriques administrateur">
      <button class="active" type="button" data-admin-tab="overview"><i class="fa-solid fa-chart-line"></i> Vue d’ensemble</button>
      <button type="button" data-admin-tab="couriers"><i class="fa-solid fa-truck-fast"></i> Livreurs</button>
      <button type="button" data-admin-tab="products"><i class="fa-solid fa-box"></i> Catalogue & stock</button>
      <button type="button" data-admin-tab="orders"><i class="fa-solid fa-clipboard-list"></i> Commandes</button>
      <button type="button" data-admin-tab="moderation"><i class="fa-solid fa-shield-halved"></i> Modération</button>
      <button type="button" data-admin-tab="payments"><i class="fa-solid fa-money-bill-transfer"></i> Paiements</button>
     </nav>
     <div class="admin-tab-panel" id="adminPanel" aria-live="polite"></div>
    </div>
   </section>
   <!-- Espace livreur : tâches liées uniquement aux livraisons qui lui sont attribuées. -->
   <section class="view content-view hidden" id="courierView">
    <div class="page-title-row"><div><span class="eyebrow muted-eyebrow">ESPACE LIVREUR · DÉMO</span><h1>Mes livraisons</h1><p>Les états de livraison restent distincts des états de commande.</p></div><span class="demo-badge">MODE DÉMONSTRATION</span></div>
    <div class="courier-tabs" aria-label="Rubriques livreur">
     <button class="active" type="button" data-courier-tab="assigned"><i class="fa-solid fa-list-check"></i> Affectations</button>
     <button type="button" data-courier-tab="active"><i class="fa-solid fa-truck-fast"></i> En cours</button>
     <button type="button" data-courier-tab="history"><i class="fa-solid fa-clock-rotate-left"></i> Historique</button>
     <button type="button" data-courier-tab="incidents"><i class="fa-solid fa-triangle-exclamation"></i> Incidents</button>
    </div>
    <div id="courierPanel" class="courier-panel" aria-live="polite"></div>
    <div class="callout"><i class="fa-solid fa-shield-halved"></i><span>Le QR est présenté par le livreur puis scanné par le client authentifié. L’OTP constitue un moyen de secours. Cette maquette ne valide aucune réception réelle.</span></div>
   </section>
  </main>
  <!-- Pied de page public. -->
  <footer class="site-footer">
   <a class="brand footer-brand" href="#landing">
    <span class="brand-mark">
     <i class="fa-solid fa-bolt">
     </i>
    </span>
    <span>
     pc
     <span class="brand-accent">
      apps
     </span>
     <small>
      STORE &middot; CAMEROUN
     </small>
    </span>
   </a>
   <p>
    Un choix technologique plus clair.
   </p>
   <div>
    <a data-public="about" href="#about">
     &Agrave; propos
    </a>
    <a data-view="annonces" href="#annonces">
     Annonces
    </a>
    <a href="#landing" id="footerHelp">
     Aide
    </a>
   </div>
   <small>
    &copy;
    <span id="yearNow">
    </span>
    Pc Apps Store &middot; Prototype frontend uniquement
   </small>
  </footer>
  <!-- Navigation inférieure du client connecté, affichée sur mobile. -->
  <nav aria-label="Navigation client mobile" class="bottom-nav hidden" id="bottomNav">
   <button class="active" data-view="client">
    <i class="fa-solid fa-house">
    </i>
    <span>
     Accueil
    </span>
   </button>
   <button data-view="catalogue">
    <i class="fa-solid fa-grip">
    </i>
    <span>
     Catalogue
    </span>
   </button>
   <button class="bottom-cart" data-view="cart">
    <i class="fa-solid fa-bag-shopping">
    </i>
    <span>
     Panier
    </span>
    <b id="bottomCartCount">
     0
    </b>
   </button>
   <button data-view="orders">
    <i class="fa-solid fa-box-open">
    </i>
    <span>
     Commandes
    </span>
   </button>
   <button data-view="account">
    <i class="fa-regular fa-user">
    </i>
    <span>
     Compte
    </span>
   </button>
  </nav>
  <div aria-atomic="true" aria-live="polite" class="toast-region" id="toastRegion">
  </div>
  <!-- Fenêtre connexion / inscription, adaptée séparément au desktop et au mobile. -->
  <dialog aria-labelledby="authTitle" class="modal auth-modal" id="authModal">
   <button aria-label="Fermer la fen&ecirc;tre de connexion" class="icon-btn auth-close" id="authClose" type="button">
    <i class="fa-solid fa-xmark">
    </i>
   </button>
   <div class="auth-layout">
    <aside class="auth-visual">
     <a aria-label="Pc Apps Store accueil" class="brand auth-visual-brand" href="#landing">
      <span class="brand-mark">
       <i class="fa-solid fa-bolt">
       </i>
      </span>
      <span>
       pc
       <span class="brand-accent">
        apps
       </span>
       <small>
        STORE &middot; CAMEROUN
       </small>
      </span>
     </a>
     <span class="auth-visual-kicker">
      VOTRE PROCHAIN CHOIX COMMENCE ICI
     </span>
     <h2>
      La technologie,
      <br/>
      <span>
       en toute confiance.
      </span>
     </h2>
     <p>
      Retrouvez vos s&eacute;lections, vos commandes et les informations essentielles au m&ecirc;me endroit.
     </p>
     <div aria-hidden="true" class="auth-visual-art">
      <span class="auth-orbit auth-orbit-one">
      </span>
      <span class="auth-orbit auth-orbit-two">
      </span>
      <i class="fa-solid fa-laptop">
      </i>
      <i class="fa-solid fa-mobile-screen-button">
      </i>
     </div>
     <div class="auth-trust">
      <i class="fa-solid fa-shield-halved">
      </i>
      Une exp&eacute;rience pens&eacute;e pour le Cameroun
     </div>
    </aside>
    <div class="auth-content">
     <div class="modal-brand auth-mobile-brand">
      <span class="brand-mark">
       <i class="fa-solid fa-bolt">
       </i>
      </span>
      <span>
       pc
       <span class="brand-accent">
        apps
       </span>
      </span>
     </div>
     <span class="eyebrow muted-eyebrow">
      VOTRE ESPACE PERSONNEL
     </span>
     <h2 id="authTitle">
      Bienvenue chez vous.
     </h2>
     <p id="authDescription">
      Connectez-vous pour acc&eacute;der &agrave; votre espace client.
     </p>
     <div aria-label="Connexion ou inscription" class="auth-tabs" role="tablist">
      <button aria-selected="true" class="active" data-auth-tab="login" role="tab" type="button">
       Connexion
      </button>
      <button aria-selected="false" data-auth-tab="signup" role="tab" type="button">
       Cr&eacute;er un compte
      </button>
     </div>
     <form id="authForm">
      <div class="form-field" id="nameField">
       <label for="authName">
        Pr&eacute;nom
       </label>
       <div class="input-with-icon">
        <i class="fa-regular fa-user">
        </i>
        <input autocomplete="given-name" id="authName" placeholder="Ex. Alex"/>
       </div>
      </div>
      <div class="form-field hidden" id="surnameField">
       <label for="authSurname">
        Nom
       </label>
       <div class="input-with-icon">
        <i class="fa-regular fa-user">
        </i>
        <input autocomplete="family-name" id="authSurname" placeholder="Ex. Mbuyi"/>
       </div>
      </div>
      <div class="form-field">
       <label for="authEmail">
        Adresse e-mail
       </label>
       <div class="input-with-icon">
        <i class="fa-regular fa-envelope">
        </i>
        <input autocomplete="email" id="authEmail" placeholder="vous@exemple.com" required="" type="email"/>
       </div>
      </div>
      <div class="form-field hidden" id="phoneField">
       <label for="authPhone">
        T&eacute;l&eacute;phone
       </label>
       <div class="input-with-icon">
        <i class="fa-solid fa-phone">
        </i>
        <input autocomplete="tel" id="authPhone" placeholder="6XX XX XX XX" type="tel"/>
       </div>
       <small>
        Renseign&eacute; lors de la cr&eacute;ation du compte.
       </small>
      </div>
      <div class="form-field hidden" id="cityField">
       <label for="authCity">
        Ville
       </label>
       <div class="input-with-icon">
        <i class="fa-solid fa-location-dot">
        </i>
        <input autocomplete="address-level2" id="authCity" placeholder="Ex. Douala"/>
       </div>
      </div>
      <div class="form-field">
       <label for="authPassword">
        Mot de passe
       </label>
       <div class="input-with-icon">
        <i class="fa-solid fa-lock">
        </i>
        <input autocomplete="current-password" id="authPassword" minlength="4" placeholder="Votre mot de passe" required="" type="password"/>
        <button aria-label="Afficher le mot de passe" class="password-toggle" id="togglePassword" type="button">
         <i class="fa-regular fa-eye">
         </i>
        </button>
       </div>
       <small>
        Prototype : ne saisissez pas un vrai mot de passe.
       </small>
      </div>
      <button class="btn btn-primary full-btn" id="authSubmit" type="submit">
       Se connecter
       <i class="fa-solid fa-arrow-right">
       </i>
      </button>
      <p class="modal-disclaimer">
       <i class="fa-solid fa-circle-info">
       </i>
       D&eacute;monstration locale : aucune authentification r&eacute;elle et aucune donn&eacute;e envoy&eacute;e &agrave; un serveur.
      </p>
     </form>
    </div>
   </div>
  </dialog>
  <!-- Formulaire de proposition d’annonce : publication soumise à modération. -->
  <dialog class="modal small-modal" id="announcementModal">
   <form class="modal-close-row" method="dialog">
    <button aria-label="Fermer" class="icon-btn">
     <i class="fa-solid fa-xmark">
     </i>
    </button>
   </form>
   <span class="eyebrow muted-eyebrow">
    COMMUNAUT&Eacute;
   </span>
   <h2>
    Proposer une annonce
   </h2>
   <p>
    Votre proposition restera en attente de mod&eacute;ration dans cette d&eacute;monstration.
   </p>
   <form id="announcementForm">
    <div class="form-field">
     <label for="announcementTitle">
      Titre
     </label>
     <input id="announcementTitle" maxlength="90" required=""/>
    </div>
    <div class="form-field">
     <label for="announcementText">
      Contenu
     </label>
     <textarea id="announcementText" maxlength="500" required="" rows="4"></textarea>
    </div>
    <button class="btn btn-primary full-btn" type="submit">
     Soumettre pour validation
     <i class="fa-solid fa-arrow-right">
     </i>
    </button>
   </form>
  </dialog>
  <script defer="" src="app.js">
    'use strict';
/* Pc Apps Store — prototype frontend. Données fictives, sans API ni paiement réel. */
const money = n => new Intl.NumberFormat('fr-FR').format(n) + ' FCFA';
const iconByCategory = { Ordinateurs: 'fa-laptop', Téléphones: 'fa-mobile-screen-button', Téléviseurs: 'fa-tv', Audio: 'fa-headphones', Électroménager: 'fa-blender' };
// Catalogue fictif : chaque produit peut posséder plusieurs variantes.
const products = [
    { id: 'pc-hp-14', brand: 'HP', name: 'HP Pavilion 14', category: 'Ordinateurs', price: 385000, oldPrice: 425000, stock: 6, badge: 'OFFRE LIMITÉE', image: 'https://images.unsplash.com/photo-1496181133206-80ce9b88a853?auto=format&fit=crop&w=720&q=78', description: 'Un ordinateur polyvalent pour les études, le travail et les usages du quotidien. Vérifiez la configuration exacte de la variante avant commande.', variants: [{ id: 'hp-8-512', label: 'Core i5 · 8 Go · 512 Go SSD', price: 385000, stock: 6, specs: { Processeur: 'Intel Core i5', RAM: '8 Go', Stockage: '512 Go SSD', Écran: '14 pouces' } }, { id: 'hp-16-512', label: 'Core i7 · 16 Go · 512 Go SSD', price: 485000, stock: 2, specs: { Processeur: 'Intel Core i7', RAM: '16 Go', Stockage: '512 Go SSD', Écran: '14 pouces' } }], specs: ['Core i5', '8 Go RAM', '512 Go SSD'], featured: true },
    { id: 'iphone-13', brand: 'Apple', name: 'iPhone 13', category: 'Téléphones', price: 325000, oldPrice: 349000, stock: 8, badge: 'POPULAIRE', image: 'https://images.unsplash.com/photo-1592750475338-74b7b21085ab?auto=format&fit=crop&w=720&q=78', description: 'Un smartphone Apple au format confortable, adapté à la photo, aux applications et à un usage quotidien.', variants: [{ id: 'ip13-128', label: '128 Go · Minuit', price: 325000, stock: 5, specs: { Stockage: '128 Go', Couleur: 'Minuit', Écran: '6,1 pouces' } }, { id: 'ip13-256', label: '256 Go · Lumière stellaire', price: 365000, stock: 3, specs: { Stockage: '256 Go', Couleur: 'Lumière stellaire', Écran: '6,1 pouces' } }], specs: ['128 Go', '6,1 pouces', 'iOS'], featured: true },
    { id: 'samsung-a55', brand: 'Samsung', name: 'Samsung Galaxy A55', category: 'Téléphones', price: 245000, oldPrice: null, stock: 12, badge: 'NOUVEAUTÉ', image: 'https://images.unsplash.com/photo-1511707171634-5f897ff02aa9?auto=format&fit=crop&w=720&q=78', description: 'Un smartphone polyvalent de la gamme Galaxy. Les détails techniques définitifs dépendront de la variante sélectionnée.', variants: [{ id: 'a55-128', label: '128 Go · 8 Go RAM', price: 245000, stock: 8, specs: { Stockage: '128 Go', RAM: '8 Go', Écran: '6,6 pouces' } }, { id: 'a55-256', label: '256 Go · 8 Go RAM', price: 275000, stock: 4, specs: { Stockage: '256 Go', RAM: '8 Go', Écran: '6,6 pouces' } }], specs: ['8 Go RAM', '128 Go', 'Galaxy'], featured: true },
    { id: 'dell-inspiron', brand: 'Dell', name: 'Dell Inspiron 15', category: 'Ordinateurs', price: 420000, oldPrice: null, stock: 4, badge: 'BON ÉQUILIBRE', image: 'https://images.unsplash.com/photo-1588872657578-7efd1f1555ed?auto=format&fit=crop&w=720&q=78', description: 'Un ordinateur portable pour le travail et les études. Comparez processeur, mémoire et stockage selon la variante.', variants: [{ id: 'dell-i5-8', label: 'Core i5 · 8 Go · 512 Go SSD', price: 420000, stock: 4, specs: { Processeur: 'Intel Core i5', RAM: '8 Go', Stockage: '512 Go SSD', Écran: '15,6 pouces' } }], specs: ['Core i5', '8 Go RAM', '15,6 pouces'], featured: true },
    { id: 'lenovo-ideapad', brand: 'Lenovo', name: 'Lenovo IdeaPad Slim', category: 'Ordinateurs', price: 365000, oldPrice: null, stock: 0, badge: 'RUPTURE', image: 'https://images.unsplash.com/photo-1496181133206-80ce9b88a853?auto=format&fit=crop&w=720&q=78', description: 'Un ordinateur portable fin conçu pour les usages courants. Cette variante est indisponible dans la démonstration.', variants: [{ id: 'lenovo-r5', label: 'Ryzen 5 · 8 Go · 512 Go SSD', price: 365000, stock: 0, specs: { Processeur: 'AMD Ryzen 5', RAM: '8 Go', Stockage: '512 Go SSD' } }], specs: ['Ryzen 5', '8 Go RAM', '512 Go SSD'], featured: false },
    { id: 'samsung-tv', brand: 'Samsung', name: 'Samsung Smart TV 55″', category: 'Téléviseurs', price: 395000, oldPrice: 435000, stock: 3, badge: 'PROMOTION', image: 'https://images.unsplash.com/photo-1593359677879-a4bb92f829d1?auto=format&fit=crop&w=720&q=78', description: 'Téléviseur grand format pour le divertissement à domicile. La connectivité et la définition sont précisées dans la variante.', variants: [{ id: 'tv55-4k', label: '55 pouces · 4K UHD', price: 395000, stock: 3, specs: { Écran: '55 pouces', Définition: '4K UHD', Connectivité: 'Smart TV' } }], specs: ['55 pouces', '4K UHD', 'Smart TV'], featured: true },
    { id: 'jbl-headphones', brand: 'JBL', name: 'Casque Bluetooth JBL', category: 'Audio', price: 65000, oldPrice: null, stock: 15, badge: 'BON PLAN', image: 'https://images.unsplash.com/photo-1505740420928-5e560c06d30e?auto=format&fit=crop&w=720&q=78', description: 'Un casque audio Bluetooth pour écouter musique et podcasts au quotidien. Les caractéristiques finales seront confirmées dans la fiche réelle.', variants: [{ id: 'jbl-black', label: 'Bluetooth · Noir', price: 65000, stock: 15, specs: { Connexion: 'Bluetooth', Couleur: 'Noir', Type: 'Casque audio' } }], specs: ['Bluetooth', 'Sans fil', 'Audio'], featured: true },
    { id: 'lg-fridge', brand: 'LG', name: 'Réfrigérateur LG', category: 'Électroménager', price: 310000, oldPrice: null, stock: 2, badge: 'STOCK LIMITÉ', image: 'https://images.unsplash.com/photo-1571175443880-49e1d25b2bc5?auto=format&fit=crop&w=720&q=78', description: 'Un appareil électroménager pour équiper la maison. Capacité et consommation doivent être vérifiées pour la variante choisie.', variants: [{ id: 'lg-fridge-300', label: 'Capacité indicative · 300 L', price: 310000, stock: 2, specs: { Capacité: '300 L (démo)', Type: 'Réfrigérateur', Couleur: 'Inox' } }], specs: ['Réfrigérateur', '300 L*', 'Inox'], featured: false }
];
const brands = [{ name: 'Apple', sub: 'Téléphones · audio', logo: 'Apple', filter: 'Apple' }, { name: 'Samsung', sub: 'Téléphones · TV · maison', logo: 'SAMSUNG', filter: 'Samsung' }, { name: 'HP', sub: 'Ordinateurs', logo: 'hp', filter: 'HP' }, { name: 'Dell', sub: 'Ordinateurs', logo: 'DELL', filter: 'Dell' }, { name: 'Lenovo', sub: 'Ordinateurs', logo: 'Lenovo', filter: 'Lenovo' }];
// État temporaire de la démonstration : il sera remplacé par les données du backend.
let cart = [], currentUser = null, authMode = 'login', currentView = 'landing', previousView = 'catalogue', activeProduct = null, activeVariant = 0, detailQty = 1, liked = new Set(), orders = [], adminTab = 'overview', courierTab = 'assigned';
// Comptes et affectations de démonstration : en production, ces données seront gérées par l'API.
let couriers = [];
let deliveryTasks = [
    { id: 'LIV-1042', client: 'Client de démonstration', city: 'Douala', address: 'Adresse de démonstration à confirmer', status: 'À accepter', note: 'Commande payée · coordonnées fictives' },
    { id: 'LIV-1038', client: 'Client de démonstration', city: 'Yaoundé', address: 'Adresse de démonstration à confirmer', status: 'En préparation', note: 'Exemple de tâche pour la maquette' }
];
let announcements = [{ title: 'Bienvenue sur Pc Apps Store', text: 'Le catalogue de démonstration illustre les catégories et les fiches produits. Les données commerciales définitives seront ajoutées depuis l’espace administrateur.', date: 'Information de démonstration', status: 'Publié' }];
const $ = s => document.querySelector(s);
const $$ = s => [...document.querySelectorAll(s)];
const viewIds = { landing: 'landingView', client: 'clientView', catalogue: 'catalogueView', product: 'productView', cart: 'cartView', orders: 'ordersView', promotions: 'promotionsView', annonces: 'annoncesView', account: 'accountView', admin: 'adminView', courier: 'courierView' };


function safe(s = '') { return String(s).replace(/[&<>"']/g, c => ({ '&': '&amp;', '<': '&lt;', '>': '&gt;', '"': '&quot;', "'": '&#39;' }[c]));
}


function icon(category) { return iconByCategory[category] || 'fa-box';
}


function toast(message, warning = false) { const el = document.createElement('div');
el.className = 'toast' + (warning ? ' warning' : '');
el.innerHTML = `<i class="fa-solid ${warning ? 'fa-circle-exclamation' : 'fa-circle-check'}"></i><span>${safe(message)}</span>`;
$('#toastRegion').append(el);
setTimeout(() => el.remove(), 3500);
}
// Navigation entre les pages publiques et les espaces réservés aux clients connectés.


function go(view, opts = {}) {
    if (!viewIds[view])
        view = 'landing';
    if (view !== 'product' && currentView === 'product')
        previousView = 'catalogue';
    if (view === 'product' && currentView !== 'product')
        previousView = currentView === 'landing' ? 'catalogue' : currentView;
    currentView = view;
    Object.values(viewIds).forEach(id => $('#' + id).classList.add('hidden'));
    $('#' + viewIds[view]).classList.remove('hidden');
    $('#bottomNav').classList.toggle('hidden', !currentUser);
    $$('.desktop-nav a').forEach(a => a.classList.toggle('active', a.dataset.view === view || (view === 'landing' && a.dataset.public === 'landing')));
    $$('.bottom-nav button').forEach(b => b.classList.toggle('active', b.dataset.view === view || (view === 'product' && b.dataset.view === previousView)));
    if (view === 'catalogue')
        renderCatalogue();
    if (view === 'cart')
        renderCart();
    if (view === 'orders')
        renderOrders();
    if (view === 'promotions')
        renderPromotions();
    if (view === 'annonces')
        renderAnnouncements();
    if (view === 'account')
        renderAccount();
    if (view === 'client')
        renderClient();
    if (view === 'admin')
        renderAdmin();
    if (view === 'courier')
        renderCourier();
    if (view === 'landing')
        renderFeatured();
    if (!opts.noScroll)
        window.scrollTo({ top: 0, behavior: window.matchMedia('(prefers-reduced-motion: reduce)').matches ? 'auto' : 'smooth' });
}


function requireClient(action) {
    if (!currentUser) {
        openAuth('login');
        toast('Connectez-vous pour accéder à cette fonctionnalité.', true);
        return false;
    }
    if (action === 'checkout') {
        toast('La création réelle de commande sera activée avec le backend et la réservation de stock.', true);
        return false;
    }
    return true;
}


function priceOf(p, variant = 0) { return p.variants[variant]?.price ?? p.price;
}


function imageMarkup(p, cls = '') { return p.image ? `<img class="${cls}" src="${safe(p.image)}" alt="${safe(p.brand + ' ' + p.name)}" loading="lazy" onerror="this.style.display='none';this.parentElement.querySelector('.product-placeholder')?.classList.remove('hidden')">` : '';
}
// Composant réutilisable pour afficher un produit dans les différentes vues.


function productCard(p) { const v = p.variants[0], out = p.stock === 0;
return `<article class="product-card"><div class="product-media" data-open-product="${p.id}">${imageMarkup(p)}<i class="fa-solid ${icon(p.category)} product-placeholder ${p.image ? 'hidden' : ''}"></i><span class="product-badge ${p.oldPrice ? 'sale' : ''}">${safe(p.badge || p.category)}</span><button class="wish-btn ${liked.has(p.id) ? 'liked' : ''}" data-like="${p.id}" aria-label="${liked.has(p.id) ? 'Retirer des favoris' : 'Ajouter aux favoris'}"><i class="fa-${liked.has(p.id) ? 'solid' : 'regular'} fa-heart"></i></button></div><div class="product-info"><span class="product-brand">${safe(p.brand)} · ${safe(p.category)}</span><button class="product-name plain-product-name" data-open-product="${p.id}">${safe(p.name)}</button><div class="product-specs">${p.specs.slice(0, 3).map(s => `<span>${safe(s)}</span>`).join('')}</div><div class="product-price-row"><strong class="product-price">${money(v.price)}</strong>${p.oldPrice ? `<span class="old-price">${money(p.oldPrice)}</span>` : ''}</div><span class="product-stock ${out ? 'out' : ''}"><i class="fa-solid ${out ? 'fa-circle-xmark' : 'fa-circle-check'}"></i> ${out ? 'Actuellement indisponible' : p.stock <= 3 ? 'Plus que ' + p.stock + ' en stock' : 'En stock · ' + p.stock + ' unités'}</span><div class="product-card-actions"><button class="btn btn-outline" data-open-product="${p.id}">Détails</button><button class="btn btn-add" data-add="${p.id}" ${out ? 'disabled' : ''}><i class="fa-solid fa-plus"></i> Ajouter</button></div></div></article>`;
}


function renderFeatured() { const featured = products.filter(p => p.featured).slice(0, 4);
$('#featuredGrid').innerHTML = featured.map(productCard).join('');
}


function renderClient() {
    if (!currentUser)
        return go('landing');
    $('#greetingTitle').textContent = 'Bonjour ' + currentUser.firstName + '.';
    $('#orderStat').textContent = orders.length + ' commande' + (orders.length === 1 ? '' : 's');
    $('#cartStat').textContent = cart.reduce((n, l) => n + l.qty, 0) + ' article' + (cart.reduce((n, l) => n + l.qty, 0) === 1 ? '' : 's');
    $('#clientFeaturedGrid').innerHTML = products.filter(p => p.featured).slice(0, 4).map(productCard).join('');
    updateCartCount();
}


function renderBrands() { $('#brandGrid').innerHTML = brands.map(b => `<button class="brand-card" data-brand="${safe(b.filter)}"><span class="brand-logo">${safe(b.logo)}</span><small>${safe(b.sub)}</small><span class="brand-arrow"><i class="fa-solid fa-arrow-up-right-from-square"></i></span></button>`).join('');
$('#brandFilter').innerHTML = '<option value="all">Toutes les marques</option>' + [...new Set(products.map(p => p.brand))].sort().map(b => `<option>${safe(b)}</option>`).join('');
}


function applySearch(query) { $('#globalSearch').value = query;
go('catalogue');
renderCatalogue();
}


function filteredProducts() {
    let q = $('#globalSearch').value.trim().toLowerCase(), brand = $('#brandFilter').value, cat = $('#categoryFilter').value, avail = $('#availabilityFilter').value, sort = $('#sortFilter').value;
    let list = products.filter(p => (!q || (p.name + ' ' + p.brand + ' ' + p.category + ' ' + p.specs.join(' ')).toLowerCase().includes(q)) && (brand === 'all' || p.brand === brand) && (cat === 'all' || p.category === cat) && (avail === 'all' || (avail === 'in' ? p.stock > 0 : p.stock === 0)));
    if (sort === 'price-asc')
        list.sort((a, b) => a.price - b.price);
    if (sort === 'price-desc')
        list.sort((a, b) => b.price - a.price);
    if (sort === 'name')
        list.sort((a, b) => a.name.localeCompare(b.name, 'fr'));
    return list;
}


function renderCatalogue() { const list = filteredProducts();
$('#catalogueGrid').innerHTML = list.map(productCard).join('');
$('#resultCount').textContent = list.length + ' produit' + (list.length === 1 ? '' : 's');
$('#catalogueEmpty').classList.toggle('hidden', list.length !== 0);
$('#catalogueGrid').classList.toggle('hidden', list.length === 0);
}


function resetFilters() { $('#globalSearch').value = '';
$('#brandFilter').value = 'all';
$('#categoryFilter').value = 'all';
$('#availabilityFilter').value = 'all';
$('#sortFilter').value = 'featured';
$('#mobileSort').value = 'featured';
renderCatalogue();
}


function openProduct(id) {
    const p = products.find(p => p.id === id);
    if (!p)
        return;
    activeProduct = p;
    activeVariant = 0;
    detailQty = 1;
    renderProduct();
    go('product');
}


function renderProduct() {
    const p = activeProduct;
    if (!p)
        return;
    const v = p.variants[activeVariant], out = v.stock === 0;
    $('#productDetail').innerHTML = `<div class="detail-layout"><div class="detail-image">${imageMarkup(p)}<i class="fa-solid ${icon(p.category)} product-placeholder ${p.image ? 'hidden' : ''}"></i></div><div class="detail-copy"><span class="product-brand">${safe(p.brand)} · ${safe(p.category)}</span><h1>${safe(p.name)}</h1><p class="detail-description">${safe(p.description)}</p><div class="detail-price">${money(v.price)} ${p.oldPrice ? `<span class="detail-old">${money(p.oldPrice)}</span>` : ''}</div><div class="detail-stock ${out ? 'out' : ''}"><i class="fa-solid ${out ? 'fa-circle-xmark' : 'fa-circle-check'}"></i> ${out ? 'Variante indisponible' : v.stock + ' unité(s) disponible(s) dans la démo'}</div><div class="variant-title">Choisissez une variante</div><div class="variant-options">${p.variants.map((x, i) => `<button class="variant-option ${i === activeVariant ? 'active' : ''}" data-variant="${i}">${safe(x.label)} · ${money(x.price)}</button>`).join('')}</div><div class="detail-specs"><b class="field-label">Caractéristiques de la variante</b>${Object.entries(v.specs).map(([k, val]) => `<div class="spec-row"><span>${safe(k)}</span><strong>${safe(val)}</strong></div>`).join('')}</div><div class="detail-actions"><div class="qty-control"><button data-qty="-" aria-label="Diminuer la quantité"><i class="fa-solid fa-minus"></i></button><span>${detailQty}</span><button data-qty="+" aria-label="Augmenter la quantité"><i class="fa-solid fa-plus"></i></button></div><button class="btn btn-primary" data-add="${p.id}" ${out ? 'disabled' : ''}><i class="fa-solid fa-bag-shopping"></i> Ajouter au panier</button></div><p class="filter-note"><i class="fa-solid fa-circle-info"></i> Maquette : variantes, prix et stocks fictifs. Les stocks réels seront contrôlés côté serveur avant toute commande.</p></div></div>`;
}


function addToCart(id) {
    const p = products.find(x => x.id === id);
    if (!p)
        return;
    const variant = activeProduct?.id === id ? activeVariant : 0;
    const v = p.variants[variant];
    if (!v || v.stock < 1) {
        toast('Cette variante est actuellement indisponible.', true);
        return;
    }
    const key = p.id + '::' + v.id;
    const line = cart.find(l => l.key === key);
    if (line) {
        if (line.qty + 1 > v.stock) {
            toast('La quantité dépasse le stock de démonstration.', true);
            return;
        }
        line.qty++;
    }
    else
        cart.push({ key, productId: p.id, variantId: v.id, variantIndex: variant, qty: 1, price: v.price });
    updateCartCount();
    toast(p.name + ' ajouté au panier.');
    if (currentView === 'cart')
        renderCart();
    if (currentView === 'client')
        renderClient();
}


function updateCartCount() { const n = cart.reduce((sum, l) => sum + l.qty, 0);
$('#cartCount').textContent = n;
$('#bottomCartCount').textContent = n;
$('#cartPageCount').textContent = n + ' article' + (n === 1 ? '' : 's');
$('#cartStat').textContent = n + ' article' + (n === 1 ? '' : 's');
}


function changeCart(key, delta) {
    const l = cart.find(l => l.key === key);
    if (!l)
        return;
    const p = products.find(p => p.id === l.productId), v = p.variants.find(v => v.id === l.variantId);
    l.qty += delta;
    if (l.qty <= 0)
        cart = cart.filter(x => x.key !== key);
    else if (l.qty > v.stock) {
        l.qty = v.stock;
        toast('Quantité limitée au stock de démonstration.', true);
    }
    updateCartCount();
    renderCart();
}


function renderCart() {
    updateCartCount();
    const root = $('#cartContent');
    if (!cart.length) {
        root.innerHTML = `<div class="empty-cart"><i class="fa-solid fa-bag-shopping"></i><h2>Votre panier est encore vide.</h2><p>Explorez le catalogue et ajoutez les produits qui vous intéressent.</p><button class="btn btn-primary" data-view="catalogue">Découvrir le catalogue <i class="fa-solid fa-arrow-right"></i></button></div>`;
        return;
    }
    const subtotal = cart.reduce((s, l) => s + l.qty * l.price, 0);
    root.innerHTML = `<div class="cart-layout"><div class="cart-lines">${cart.map(l => { const p = products.find(p => p.id === l.productId), v = p.variants.find(v => v.id === l.variantId);
return `<article class="cart-line">${imageMarkup(p)}<div><h3>${safe(p.name)}</h3><p>${safe(v.label)} · ${money(l.price)} / unité</p><div class="line-controls"><div class="qty-control"><button data-line-change="${l.key}" data-delta="-1" aria-label="Diminu
  </script>
 </body>
</html>
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Manrope:wght@400;500;600;700;800&display=swap');
:root {
    --ink:#172230;
    --muted:#6d7887;
    --line:#e5e9ef;
    --paper:#fff;
    --canvas:#f6f8fb;
    --navy:#101d31;
    --navy2:#172b47;
    --accent:#e65b35;
    --accent-dark:#c94827;
    --accent-pale:#fff0ea;
    --green:#168566;
    --radius:20px;
    --shadow:0 16px 45px rgba(20,34,53,.08);
    --font:'DM Sans',Arial,sans-serif;
    --display:'Manrope','DM Sans',sans-serif
}

* {
    box-sizing:border-box
}

html {
    scroll-behavior:smooth;
    scroll-padding-top:90px
}

body {
    margin:0;
    background:var(--paper);
    color:var(--ink);
    font-family:var(--font);
    font-size:15px;
    line-height:1.55;
    -webkit-font-smoothing:antialiased
}

button,input,select,textarea {
    font:inherit
}

button,a {
    -webkit-tap-highlight-color:transparent
}

button {
    cursor:pointer
}

a {
    color:inherit;
    text-decoration:none
}

button:focus-visible,a:focus-visible,input:focus-visible,select:focus-visible,textarea:focus-visible {
    outline:3px solid #f2a48e;
    outline-offset:3px
}

.hidden {
    display:none!important
}

.announcement {
    height:36px;
    background:var(--navy);
    color:#dfe7f1;
    display:flex;
    align-items:center;
    justify-content:center;
    gap:18px;
    font-size:11px;
    letter-spacing:.02em;
    position:relative
}

.announcement span:first-child {
    font-weight:700;
    color:#fff
}

.announcement i {
    margin-right:6px;
    color:#ff987b
}

.announcement button {
    position:absolute;
    right:20px;
    top:4px;
    color:#dfe7f1;
    background:none;
    border:0
}

.topbar {
    height:84px;
    max-width:1240px;
    margin:auto;
    padding:0 28px;
    display:flex;
    align-items:center;
    gap:36px
}

.brand {
    display:inline-flex;
    align-items:center;
    gap:10px;
    min-width:200px;
    font-family:var(--display);
    font-size:21px;
    font-weight:800;
    letter-spacing:-1px;
    line-height:1.05
}

.brand-mark {
    width:37px;
    height:37px;
    border-radius:12px;
    background:var(--accent);
    color:white;
    display:grid;
    place-items:center;
    font-size:17px;
    box-shadow:0 6px 15px #e65b3538
}

.brand-accent {
    color:var(--accent)
}

.brand small {
    display:block;
    font:700 8px var(--font);
    letter-spacing:2px;
    color:#7b8592;
    margin-top:5px
}

.searchbar {
    height:46px;
    max-width:530px;
    flex:1;
    display:flex;
    align-items:center;
    gap:12px;
    background:#f4f6f9;
    border:1px solid #eef0f4;
    border-radius:13px;
    padding:0 14px;
    color:#8b95a3
}

.searchbar input {
    border:0;
    outline:0!important;
    background:transparent;
    min-width:0;
    flex:1;
    color:var(--ink);
    font-size:13px
}

.searchbar kbd {
    border:1px solid #d9dfe6;
    border-radius:5px;
    padding:1px 6px;
    background:white;
    font-size:10px
}

.top-actions {
    display:flex;
    align-items:center;
    gap:13px;
    margin-left:auto
}

.icon-btn,.menu-toggle {
    width:42px;
    height:42px;
    border:1px solid var(--line);
    border-radius:12px;
    background:white;
    color:var(--ink);
    display:grid;
    place-items:center;
    position:relative
}

.icon-btn:hover,.menu-toggle:hover {
    border-color:#cbd3df;
    background:#f8fafc
}

.cart-top .cart-count {
    position:absolute;
    top:-5px;
    right:-5px;
    background:var(--accent);
    color:#fff;
    min-width:19px;
    height:19px;
    border-radius:20px;
    display:grid;
    place-items:center;
    font-size:10px;
    font-weight:800;
    border:2px solid white
}

.account-btn {
    height:42px;
    border:0;
    border-radius:12px;
    background:var(--accent-pale);
    color:var(--accent-dark);
    display:flex;
    align-items:center;
    gap:9px;
    padding:0 14px;
    font-size:12px;
    font-weight:700
}

.account-btn i {
    font-size:15px
}

.menu-toggle {
    display:none
}

.desktop-nav {
    max-width:1184px;
    margin:auto;
    padding:0 0 15px;
    display:flex;
    align-items:center;
    gap:30px;
    border-bottom:1px solid var(--line);
    font-size:12px;
    font-weight:600;
    color:#697584
}

.desktop-nav a {
    padding:7px 0;
    position:relative
}

.desktop-nav a.active,.desktop-nav a:hover {
    color:var(--accent)
}

.desktop-nav a.active:after {
    content:'';
    position:absolute;
    height:2px;
    background:var(--accent);
    left:0;
    right:0;
    bottom:-16px
}

.nav-spacer {
    flex:1
}

.secure-note {
    font-size:11px;
    color:#7c8795
}

.secure-note i {
    color:var(--green);
    margin-right:5px
}

main {
    min-height:60vh
}

.view {
    max-width:1184px;
    margin:auto;
    padding:0 0 64px
}

.hero-wrap {
    margin:28px 0 22px;
    min-height:470px;
    background:linear-gradient(115deg,#111f33 0%,#182d48 55%,#223a59 100%);
    border-radius:27px;
    color:white;
    display:grid;
    grid-template-columns:1fr .94fr;
    overflow:hidden;
    position:relative
}

.hero-wrap:before {
    content:'';
    position:absolute;
    width:440px;
    height:440px;
    border:1px solid #ffffff10;
    border-radius:50%;
    left:34%;
    top:-280px
}

.hero-copy {
    padding:55px 0 34px 52px;
    position:relative;
    z-index:2;
    display:flex;
    align-items:flex-start;
    flex-direction:column
}

.eyebrow {
    font-size:10px;
    letter-spacing:1.8px;
    font-weight:800;
    color:#ffb29c;
    display:inline-flex;
    align-items:center;
    gap:9px
}

.eyebrow-dot {
    width:7px;
    height:7px;
    border-radius:50%;
    background:#ff8b6c;
    box-shadow:0 0 0 5px #ff8b6c20
}

.hero-copy h1 {
    font:800 clamp(36px,4vw,54px)/1.12 var(--display);
    letter-spacing:-2.7px;
    margin:23px 0 17px;
    max-width:500px
}

.hero-copy h1 span {
    color:#ff9578
}

.hero-copy>p {
    font-size:15px;
    line-height:1.8;
    color:#c2cfdd;
    max-width:425px;
    margin:0
}

.hero-actions {
    display:flex;
    align-items:center;
    gap:24px;
    flex-wrap:wrap;
    margin-top:28px
}

.btn {
    min-height:44px;
    border-radius:12px;
    border:1px solid transparent;
    display:inline-flex;
    align-items:center;
    justify-content:center;
    gap:12px;
    padding:0 17px;
    font-size:12px;
    font-weight:800;
    transition:transform .18s,background .18s,border-color .18s
}

.btn:hover {
    transform:translateY(-1px)
}

.btn-primary {
    background:var(--accent);
    color:white;
    box-shadow:0 7px 16px #e65b3524
}

.btn-primary:hover {
    background:var(--accent-dark)
}

.text-link {
    font-size:12px;
    font-weight:700;
    color:#e6edf6
}

.text-link i {
    margin-left:5px;
    color:#ff987b
}

.hero-proof {
    display:flex;
    align-items:center;
    gap:12px;
    margin-top:auto;
    padding-top:35px;
    font-size:10px
}

.proof-avatars {
    display:flex;
    padding-left:4px
}

.proof-avatars span {
    width:30px;
    height:30px;
    border-radius:50%;
    display:grid;
    place-items:center;
    margin-left:-4px;
    border:2px solid #182d48;
    background:#e7d3c5;
    color:#29384b;
    font-size:8px;
    font-weight:800
}

.proof-avatars span:nth-child(2) {
    background:#c1d6de
}

.proof-avatars span:nth-child(3) {
    background:#e7bd9b
}

.hero-proof strong,.hero-proof small {
    display:block
}

.hero-proof strong {
    font-size:10px
}

.hero-proof small {
    color:#aebdce;
    font-size:9px;
    margin-top:3px
}

.proof-divider {
    height:27px;
    width:1px;
    background:#ffffff29;
    margin:0 4px
}

.green {
    color:#5fe0b5
}

.hero-visual {
    position:relative;
    min-height:440px;
    overflow:hidden
}

.hero-image {
    position:absolute;
    inset:32px 25px 28px 0;
    border-radius:180px 20px 20px 180px;
    background:#1c2d43 url('https://images.unsplash.com/photo-1496181133206-80ce9b88a853?auto=format&fit=crop&w=1100&q=82') center/cover;
    box-shadow:0 20px 50px #0004
}

.hero-image:after {
    content:'';
    position:absolute;
    inset:0;
    background:linear-gradient(90deg,#182d48a8 0%,transparent 50%),linear-gradient(0deg,#111f3333,transparent 65%)
}

.floating-tag {
    position:absolute;
    z-index:2;
    display:flex;
    gap:10px;
    align-items:center;
    background:white;
    color:var(--ink);
    padding:12px 15px;
    border-radius:13px;
    box-shadow:0 15px 40px #0002;
    min-width:218px
}

.tag-top {
    top:75px;
    left:-18px
}

.tag-bottom {
    bottom:75px;
    right:20px
}

.tag-icon {
    width:35px;
    height:35px;
    background:#fff0ea;
    border-radius:10px;
    display:grid;
    place-items:center;
    color:var(--accent)
}

.floating-tag b,.floating-tag small {
    display:block
}

.floating-tag b {
    font-size:11px
}

.floating-tag small {
    font-size:9px;
    color:var(--muted);
    margin-top:2px
}

.stock-pulse {
    width:10px;
    height:10px;
    border-radius:50%;
    background:#1baa7b;
    box-shadow:0 0 0 5px #1baa7b1a;
    margin:0 4px
}

.hero-index {
    position:absolute;
    bottom:19px;
    left:50%;
    z-index:2;
    color:white;
    font:700 11px var(--display);
    letter-spacing:2px
}

.hero-index span {
    color:#ff987b;
    margin:0 5px
}

.trust-strip {
    display:grid;
    grid-template-columns:repeat(4,1fr);
    border:1px solid var(--line);
    border-radius:16px;
    margin:0 0 56px;
    padding:21px 18px;
    gap:16px
}

.trust-strip>div {
    display:flex;
    align-items:center;
    gap:12px;
    padding-left:13px;
    border-right:1px solid var(--line)
}

.trust-strip>div:last-child {
    border:0
}

.trust-strip>div>i {
    font-size:19px;
    color:var(--accent)
}

.trust-strip b,.trust-strip small {
    display:block
}

.trust-strip b {
    font-size:11px
}

.trust-strip small {
    font-size:10px;
    color:var(--muted);
    margin-top:3px
}

.section-block {
    padding:0 0 57px
}

.section-heading {
    display:flex;
    align-items:flex-end;
    justify-content:space-between;
    gap:18px;
    margin-bottom:23px
}

.muted-eyebrow {
    color:#7f8997;
    font-size:9px
}

.section-heading h2,.about-strip h2 {
    font:800 29px/1.2 var(--display);
    letter-spacing:-1.2px;
    margin:9px 0
}

.section-heading p {
    color:var(--muted);
    font-size:12px;
    margin:0
}

.plain-link {
    background:none;
    border:0;
    color:var(--accent-dark);
    font-weight:800;
    font-size:11px;
    white-space:nowrap;
    padding:10px 0
}

.plain-link i {
    margin-left:7px
}

.brand-grid {
    display:grid;
    grid-template-columns:repeat(5,1fr);
    gap:13px
}

.brand-card {
    border:1px solid var(--line);
    border-radius:16px;
    min-height:115px;
    padding:17px;
    background:white;
    display:flex;
    flex-direction:column;
    justify-content:space-between;
    text-align:left;
    transition:.2s
}

.brand-card:hover {
    transform:translateY(-3px);
    border-color:#f2b5a3;
    box-shadow:var(--shadow)
}

.brand-logo {
    font:800 21px var(--display);
    letter-spacing:-1px;
    color:#23344a
}

.brand-card:nth-child(2) .brand-logo {
    color:#1e65bd
}

.brand-card:nth-child(3) .brand-logo {
    color:#3a7a54
}

.brand-card:nth-child(4) .brand-logo {
    color:#bb3929
}

.brand-card:nth-child(5) .brand-logo {
    color:#a92128
}

.brand-card small {
    font-size:10px;
    color:var(--muted)
}

.brand-card .brand-arrow {
    align-self:flex-end;
    color:#a2acb9;
    font-size:12px
}

.tinted-section {
    background:var(--canvas);
    max-width:none;
    padding:46px max(calc((100% - 1184px)/2),24px) 55px;
    margin:0 calc((1184px - 100vw)/2);
}

.tinted-section .section-heading {
    max-width:1184px;
    margin-left:auto;
    margin-right:auto
}

.product-grid {
    display:grid;
    grid-template-columns:repeat(4,minmax(0,1fr));
    gap:17px
}

.tinted-section .product-grid {
    max-width:1184px;
    margin:auto
}

.product-card {
    border:1px solid var(--line);
    border-radius:17px;
    background:white;
    overflow:hidden;
    min-width:0;
    display:flex;
    flex-direction:column;
    transition:transform .2s,box-shadow .2s,border-color .2s
}

.product-card:hover {
    transform:translateY(-3px);
    box-shadow:0 15px 34px #1b2b4310;
    border-color:#dbe1e9
}

.product-media {
    height:175px;
    background:#f3f5f8;
    position:relative;
    overflow:hidden;
    display:grid;
    place-items:center
}

.product-media img {
    width:100%;
    height:100%;
    object-fit:cover;
    display:block;
    transition:transform .4s
}

.product-card:hover .product-media img {
    transform:scale(1.035)
}

.product-placeholder {
    font-size:58px;
    color:#b5c0cd
}

.product-badge {
    position:absolute;
    left:12px;
    top:12px;
    background:#fff;
    border:1px solid #e9edf2;
    border-radius:7px;
    padding:5px 8px;
    font-size:8px;
    font-weight:800;
    color:#4c5a6a;
    letter-spacing:.5px
}

.product-badge.sale {
    background:var(--accent-pale);
    border-color:#ffe0d5;
    color:var(--accent-dark)
}

.wish-btn {
    position:absolute;
    right:11px;
    top:11px;
    width:31px;
    height:31px;
    border-radius:50%;
    border:1px solid #e8ebef;
    background:#ffffffed;
    color:#6f7a88;
    display:grid;
    place-items:center
}

.wish-btn.liked {
    color:var(--accent);
    background:#fff0ea
}

.product-info {
    padding:15px;
    display:flex;
    flex-direction:column;
    flex:1
}

.product-brand {
    font-size:9px;
    letter-spacing:1px;
    color:#8b96a4;
    font-weight:800;
    text-transform:uppercase
}

.product-name {
    font:700 14px/1.35 var(--display);
    letter-spacing:-.25px;
    margin:6px 0 8px;
    min-height:37px
}

.product-specs {
    display:flex;
    flex-wrap:wrap;
    gap:5px;
    margin-bottom:13px
}

.product-specs span {
    background:#f3f5f8;
    border-radius:5px;
    padding:4px 6px;
    font-size:9px;
    color:#667283
}

.product-price-row {
    display:flex;
    align-items:baseline;
    gap:7px;
    flex-wrap:wrap;
    margin-top:auto
}

.product-price {
    font:800 16px var(--display);
    letter-spacing:-.4px
}

.old-price {
    font-size:10px;
    text-decoration:line-through;
    color:#9aa3af
}

.product-stock {
    font-size:9px;
    color:var(--green);
    margin-top:5px
}

.product-stock.out {
    color:#c24a43
}

.product-card-actions {
    display:flex;
    gap:7px;
    margin-top:14px
}

.product-card-actions .btn {
    flex:1;
    min-height:38px;
    font-size:10px;
    padding:0 9px
}

.btn-outline {
    border-color:#dbe1e8;
    color:#26364a;
    background:white
}

.btn-outline:hover {
    background:#f8fafc;
    border-color:#c4ceda
}

.btn-add {
    background:var(--navy);
    color:white
}

.btn-add:hover {
    background:#223b5d
}

.btn-add:disabled {
    background:#e5e9ee;
    color:#8993a0;
    cursor:not-allowed;
    box-shadow:none
}

.promo-banner {
    margin:54px 0;
    background:var(--accent);
    border-radius:22px;
    color:white;
    padding:38px 47px;
    display:grid;
    grid-template-columns:1.1fr .9fr;
    align-items:center;
    overflow:hidden;
    position:relative;
    min-height:290px
}

.light-eyebrow {
    color:#ffe3da
}

.promo-banner h2 {
    font:800 32px/1.2 var(--display);
    letter-spacing:-1.2px;
    margin:13px 0
}

.promo-banner p {
    font-size:12px;
    line-height:1.8;
    color:#ffe6df;
    max-width:410px;
    margin:0 0 21px
}

.btn-light {
    background:white;
    color:var(--accent-dark)
}

.promo-art {
    height:210px;
    position:relative;
    display:grid;
    place-items:center
}

.promo-orbit {
    position:absolute;
    border:1px solid #ffffff4a;
    border-radius:50%;
    width:235px;
    height:235px
}

.orbit-two {
    width:175px;
    height:175px
}

.promo-device {
    height:125px;
    width:175px;
    border:8px solid #f4f1ed;
    border-bottom-width:15px;
    border-radius:11px;
    background:linear-gradient(145deg,#e4ebf0,#9eacbb);
    display:grid;
    place-items:center;
    color:#32485e;
    font-size:48px;
    transform:rotate(-8deg);
    box-shadow:0 22px 35px #862d1b30;
    z-index:1
}

.promo-percent {
    position:absolute;
    right:0;
    top:14px;
    z-index:2;
    background:#15233a;
    border-radius:12px;
    padding:13px 16px;
    font-size:9px;
    letter-spacing:1px;
    transform:rotate(6deg);
    box-shadow:0 12px 25px #8a2d1e30
}

.promo-percent b {
    font-size:18px
}

.community-block {
    padding-top:3px
}

.notice-card {
    border:1px solid var(--line);
    border-radius:17px;
    padding:22px;
    display:flex;
    align-items:center;
    gap:17px
}

.notice-icon {
    width:48px;
    height:48px;
    display:grid;
    place-items:center;
    background:#eef2fa;
    color:#4b6388;
    border-radius:14px;
    font-size:20px;
    flex-shrink:0
}

.notice-card>div {
    flex:1
}

.notice-card b {
    font-size:13px
}

.notice-card p {
    font-size:11px;
    color:var(--muted);
    margin:4px 0 0
}

.about-strip {
    background:#f8f9fb;
    border-radius:20px;
    padding:31px;
    display:grid;
    grid-template-columns:1fr 1.15fr auto;
    align-items:center;
    gap:28px
}

.about-strip h2 {
    font-size:25px;
    margin-bottom:0
}

.about-strip h2 span {
    color:var(--accent)
}

.about-strip p {
    font-size:12px;
    color:var(--muted);
    line-height:1.8;
    margin:0
}

.site-footer {
    border-top:1px solid var(--line);
    padding:29px max(calc((100% - 1184px)/2),24px) 25px;
    display:grid;
    grid-template-columns:1fr auto;
    align-items:center;
    gap:12px 30px;
    color:var(--muted)
}

.footer-brand {
    color:var(--ink);
    font-size:18px
}

.footer-brand .brand-mark {
    width:32px;
    height:32px;
    border-radius:10px
}

.site-footer>p {
    font-size:11px;
    margin:0
}

.site-footer>div {
    grid-column:1/-1;
    display:flex;
    gap:22px;
    font-size:11px;
    border-top:1px solid var(--line);
    padding-top:16px
}

.site-footer>small {
    grid-column:1/-1;
    font-size:10px
}

.app-view,.content-view {
    padding-top:34px
}

.app-greeting {
    display:flex;
    justify-content:space-between;
    align-items:center;
    gap:20px;
    background:#f7f8fb;
    border-radius:20px;
    padding:28px 31px
}

.app-greeting h1,.page-title-row h1 {
    font:800 30px/1.2 var(--display);
    letter-spacing:-1.2px;
    margin:7px 0
}

.app-greeting p,.page-title-row p {
    color:var(--muted);
    font-size:12px;
    margin:0
}

.quick-stats {
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:14px;
    margin:20px 0 36px
}

.quick-stats>button {
    display:flex;
    align-items:center;
    gap:12px;
    border:1px solid var(--line);
    border-radius:15px;
    background:white;
    text-align:left;
    padding:17px
}

.quick-stats>button>span:nth-child(2) {
    flex:1
}

.quick-stats small,.quick-stats b {
    display:block
}

.quick-stats small {
    font-size:10px;
    color:var(--muted)
}

.quick-stats b {
    font-size:13px;
    margin-top:3px
}

.quick-stats>button>i {
    font-size:11px;
    color:#9aa4b0
}

.stat-icon {
    width:43px;
    height:43px;
    border-radius:13px;
    display:grid;
    place-items:center;
    flex-shrink:0
}

.lavender {
    background:#eeefff;
    color:#6366c7
}

.peach {
    background:#fff0e9;
    color:#dc633f
}

.mint {
    background:#e3f7f0;
    color:#168566
}

.compact-block {
    padding-bottom:32px
}

.member-note {
    display:flex;
    gap:13px;
    align-items:flex-start;
    border:1px solid #e2e9f3;
    border-radius:14px;
    padding:17px;
    color:#5c6e84;
    background:#f9fbfd
}

.member-note>i {
    color:#7184a0;
    margin-top:3px
}

.member-note b {
    font-size:11px
}

.member-note p {
    font-size:10px;
    margin:3px 0 0
}

.page-title-row {
    display:flex;
    align-items:flex-end;
    justify-content:space-between;
    gap:20px;
    margin-bottom:25px
}

.result-count,.demo-badge {
    font-size:10px;
    co
