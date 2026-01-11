# -M5SUKA-CHEBRA-
22
<!doctype html>
<html lang="lt">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>🔥❤ M5SUKA Chebra ❤🔥 — Shop</title>
  <style>
    :root{
      --yellow:#ffe600;
      --text:#111;
      --muted: rgba(0,0,0,.65);
      --panel: rgba(255,255,255,.18);
      --border: 1px solid rgba(0,0,0,.12);
      --shadow: 0 20px 55px rgba(0,0,0,.18);
      --r: 22px;
      --max: 1200px;
    }
    *{ box-sizing:border-box; }
    body{
      margin:0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      background: var(--yellow);
      color: var(--text);
    }
    a{ color:inherit; }

    header{
      position: sticky; top:0; z-index: 20;
      background: var(--yellow);
    }
    .topbar{
      max-width: var(--max);
      margin: 0 auto;
      padding: 18px 18px 8px;
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap: 14px;
    }
    .brand{
      display:flex; align-items:center; gap: 10px;
      font-weight: 1000;
      letter-spacing:.4px;
      text-transform: uppercase;
      font-size: clamp(18px, 2.3vw, 28px);
      line-height:1.05;
      white-space: nowrap;
    }
    .brand .mark{
      width: 42px; height: 42px;
      border-radius: 12px;
      display:grid; place-items:center;
      background: rgba(0,0,0,.14);
      box-shadow: 0 10px 20px rgba(0,0,0,.12);
      font-size: 20px;
    }
    nav{ display:flex; align-items:center; gap: 18px; flex-wrap: wrap; justify-content:flex-end; }
    nav a{
      text-decoration:none;
      font-size: 13px;
      text-transform: uppercase;
      letter-spacing:.8px;
      padding: 8px 4px;
      border-bottom: 2px solid transparent;
    }
    nav a:hover{ border-bottom-color: rgba(0,0,0,.45); }
    nav a.active{ border-bottom-color: rgba(0,0,0,.85); }

    .cartBtn{
      display:inline-flex; align-items:center; gap: 8px;
      padding: 8px 10px;
      border-radius: 999px;
      background: rgba(0,0,0,.08);
    }
    .cartBtn svg{ width:18px; height:18px; }
    .badge{
      display:inline-grid; place-items:center;
      min-width: 20px; height: 20px;
      padding: 0 6px;
      border-radius: 999px;
      background: rgba(0,0,0,.78);
      color: #fff;
      font-size: 12px;
      font-weight: 900;
    }
    .divider{
      max-width: var(--max);
      margin: 0 auto;
      border-bottom: 1px solid var(--border);
    }

    .wrap{ max-width: var(--max); margin: 0 auto; padding: 18px; }

    /* HOMEPAGE SECTIONS */
    .section{
      margin-top: 18px;
      border-radius: 18px;
      background: rgba(255,255,255,.16);
      border: 1px solid rgba(0,0,0,.10);
      box-shadow: 0 18px 40px rgba(0,0,0,.12);
      overflow: hidden;
    }
    .section .inner{ padding: 18px; }
    .section h2{
      margin:0;
      text-transform: uppercase;
      letter-spacing:.6px;
      font-size: 16px;
    }
    .section p{ color: rgba(0,0,0,.72); line-height: 1.6; }

    .hero{
      display:grid;
      grid-template-columns: 1.1fr 1fr;
      gap: 16px;
      align-items:center;
      padding: 18px;
    }
    .heroCard{
      border-radius: 18px;
      padding: 18px;
      background: rgba(0,0,0,.12);
      box-shadow: 0 18px 40px rgba(0,0,0,.18);
    }
    .heroTitle{
      margin:0;
      font-weight: 1000;
      text-transform: uppercase;
      letter-spacing: .6px;
      font-size: clamp(22px, 3.2vw, 42px);
      line-height: 1.05;
    }
    .heroSub{
      margin-top: 10px;
      color: rgba(0,0,0,.78);
      font-size: 15px;
      line-height: 1.6;
      max-width: 52ch;
    }
    .ctaRow{ display:flex; gap: 10px; flex-wrap: wrap; margin-top: 14px; }
    .btn{
      border: 1px solid rgba(0,0,0,.22);
      background: rgba(255,255,255,.22);
      padding: 10px 12px;
      border-radius: 999px;
      font-weight: 900;
      cursor: pointer;
      text-decoration: none;
      display:inline-flex; align-items:center; gap: 8px;
    }
    .btn:hover{ background: rgba(255,255,255,.30); }
    .btn.primary{
      background: rgba(0,0,0,.82);
      color:#fff;
      border-color: rgba(0,0,0,.82);
    }
    .btn.primary:hover{ background: rgba(0,0,0,.9); }

    .heroImg{
      border-radius: 18px;
      overflow:hidden;
      box-shadow: 0 18px 40px rgba(0,0,0,.22);
    }
    .heroImg img{
      width:100%;
      height: 320px;
      object-fit: cover;
      display:block;
    }

    .twoCol{
      display:grid;
      grid-template-columns: 1fr 1fr;
      gap: 16px;
    }

    .embedBox{
      border-radius: 16px;
      background: rgba(0,0,0,.10);
      padding: 14px;
      border: 1px solid rgba(0,0,0,.12);
    }
    .embedHint{
      font-size: 12px;
      color: rgba(0,0,0,.72);
      margin-top: 6px;
    }

    .stats{
      display:grid;
      grid-template-columns: repeat(3, minmax(0,1fr));
      gap: 10px;
      margin-top: 10px;
    }
    .stat{
      border-radius: 14px;
      background: rgba(0,0,0,.10);
      padding: 12px;
      border: 1px solid rgba(0,0,0,.10);
      font-weight: 900;
    }
    .stat small{
      display:block;
      font-weight: 800;
      color: rgba(0,0,0,.70);
      margin-top: 4px;
    }

    .iconGrid{
      display:grid;
      grid-template-columns: repeat(5, minmax(0,1fr));
      gap: 10px;
      margin-top: 12px;
    }
    .iconItem{
      border-radius: 14px;
      background: rgba(0,0,0,.10);
      padding: 12px;
      border: 1px solid rgba(0,0,0,.10);
      font-weight: 900;
      font-size: 12px;
      text-transform: uppercase;
      letter-spacing:.3px;
      line-height: 1.3;
    }

    /* SHOP */
    .toolbar{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap: 12px;
      margin: 8px 0 12px;
    }
    .count{ font-size: 13px; color: var(--muted); }
    .search{
      width: min(320px, 100%);
      border: 1px solid var(--border);
      background: rgba(255,255,255,.22);
      padding: 10px 12px;
      border-radius: 999px;
      outline: none;
    }

    .grid{
      display:grid;
      gap: 22px;
      grid-template-columns: repeat(4, minmax(0, 1fr));
    }
    .card{
      border-radius: var(--r);
      overflow:hidden;
      box-shadow: var(--shadow);
      background: rgba(0,0,0,.14);
      position: relative;
      cursor: pointer;
      transition: transform .12s ease;
    }
    .card:hover{ transform: translateY(-2px); }
    .card img{ width:100%; height: 210px; object-fit: cover; display:block; }
    .card .info{
      padding: 12px 12px 14px;
      background: rgba(0,0,0,.10);
    }
    .card h3{
      margin:0;
      font-size: 13px;
      text-transform: uppercase;
      letter-spacing: .4px;
      line-height: 1.2;
    }
    .card .sub{ margin-top: 6px; font-size: 12px; color: rgba(0,0,0,.75); }
    .card .row{
      margin-top: 10px;
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap: 10px;
    }
    .price{ font-weight: 1000; }

    /* Product badges */
    .badges{
      position:absolute;
      left: 10px;
      top: 10px;
      display:flex;
      gap: 8px;
      flex-wrap: wrap;
    }
    .tagBadge{
      font-size: 11px;
      font-weight: 1000;
      padding: 6px 10px;
      border-radius: 999px;
      background: rgba(0,0,0,.82);
      color: #fff;
      text-transform: uppercase;
      letter-spacing:.4px;
    }

    /* MODAL */
    .modal, .drawer{
      position: fixed; inset: 0;
      display:none;
      z-index: 50;
    }
    .modal.show, .drawer.show{ display:block; }
    .backdrop{
      position:absolute; inset:0;
      background: rgba(0,0,0,.55);
    }
    .sheet{
      position: absolute;
      left: 50%;
      top: 50%;
      transform: translate(-50%, -50%);
      width: min(920px, calc(100% - 28px));
      background: rgba(255,255,255,.20);
      border: 1px solid rgba(255,255,255,.35);
      backdrop-filter: blur(12px);
      border-radius: 18px;
      box-shadow: 0 30px 80px rgba(0,0,0,.35);
      overflow: hidden;
    }
    .sheetHead{
      display:flex; align-items:center; justify-content:space-between; gap: 10px;
      padding: 14px 14px;
      background: rgba(0,0,0,.10);
      border-bottom: 1px solid rgba(255,255,255,.18);
    }
    .close{
      width: 40px; height: 40px;
      border-radius: 12px;
      border: 1px solid rgba(0,0,0,.18);
      background: rgba(255,255,255,.22);
      cursor: pointer;
      font-size: 18px;
    }
    .sheetBody{ padding: 14px; }
    .productView{
      display:grid;
      grid-template-columns: 1.1fr 1fr;
      gap: 14px;
    }
    .productView img{
      width:100%;
      height: 380px;
      object-fit: cover;
      border-radius: 16px;
      box-shadow: 0 18px 40px rgba(0,0,0,.22);
    }
    .muted{ color: rgba(0,0,0,.72); }
    .pill{
      display:inline-block;
      margin-top: 8px;
      padding: 6px 10px;
      border-radius: 999px;
      border: 1px solid rgba(0,0,0,.16);
      background: rgba(255,255,255,.20);
      font-size: 12px;
      font-weight: 800;
    }
    .qtyRow{
      display:flex; align-items:center; gap: 10px;
      margin-top: 14px;
    }
    .qty{
      display:inline-flex; align-items:center; gap: 8px;
      border: 1px solid rgba(0,0,0,.18);
      background: rgba(255,255,255,.22);
      border-radius: 999px;
      padding: 6px 10px;
    }
    .qty button{
      width: 34px; height: 34px;
      border-radius: 999px;
      border: 1px solid rgba(0,0,0,.16);
      background: rgba(255,255,255,.22);
      cursor:pointer;
      font-size: 16px;
      font-weight: 900;
    }
    .qty span{ min-width: 18px; text-align:center; font-weight: 900; }

    /* CART DRAWER */
    .drawerPanel{
      position:absolute;
      right: 0; top: 0; bottom: 0;
      width: min(430px, 92vw);
      background: rgba(255,255,255,.20);
      border-left: 1px solid rgba(255,255,255,.35);
      backdrop-filter: blur(12px);
      box-shadow: -30px 0 80px rgba(0,0,0,.25);
      display:flex;
      flex-direction: column;
    }
    .drawerBody{ padding: 14px; overflow:auto; flex: 1; }
    .line{
      display:grid;
      grid-template-columns: 64px 1fr auto;
      gap: 10px;
      padding: 10px;
      border-radius: 14px;
      background: rgba(0,0,0,.10);
      margin-bottom: 10px;
    }
    .line img{ width: 64px; height: 54px; object-fit: cover; border-radius: 12px; }
    .line h4{ margin:0; font-size: 12px; text-transform: uppercase; letter-spacing: .3px; }
    .line .small{ font-size: 12px; color: rgba(0,0,0,.7); margin-top: 4px; }
    .line .right{ text-align:right; }
    .drawerFoot{
      padding: 14px;
      border-top: 1px solid rgba(255,255,255,.22);
      background: rgba(0,0,0,.08);
    }
    .totals{
      display:flex; align-items:center; justify-content:space-between;
      margin-bottom: 10px;
      font-weight: 1000;
    }
    .form{
      display:grid;
      gap: 10px;
      margin-top: 10px;
    }
    .input{
      border: 1px solid rgba(0,0,0,.18);
      background: rgba(255,255,255,.22);
      padding: 10px 12px;
      border-radius: 12px;
      outline:none;
    }
    textarea.input{ resize: vertical; min-height: 90px; }

    footer{
      max-width: var(--max);
      margin: 28px auto 40px;
      padding: 0 18px;
      color: rgba(0,0,0,.65);
      font-size: 13px;
    }
    .footerLinks{
      display:flex;
      gap: 12px;
      flex-wrap: wrap;
      margin-top: 10px;
    }
    .footerLinks a{
      text-decoration:none;
      border-bottom: 1px solid rgba(0,0,0,.25);
      padding-bottom: 2px;
    }

    @media (max-width: 1100px){
      .grid{ grid-template-columns: repeat(3, minmax(0, 1fr)); }
      .iconGrid{ grid-template-columns: repeat(3, minmax(0,1fr)); }
    }
    @media (max-width: 900px){
      .grid{ grid-template-columns: repeat(2, minmax(0, 1fr)); }
      .productView{ grid-template-columns: 1fr; }
      .productView img{ height: 300px; }
      .brand{ white-space: normal; }
      .hero{ grid-template-columns: 1fr; }
      .heroImg img{ height: 260px; }
      .twoCol{ grid-template-columns: 1fr; }
      .stats{ grid-template-columns: 1fr; }
    }
    @media (max-width: 520px){
      .grid{ grid-template-columns: 1fr; }
      .iconGrid{ grid-template-columns: 1fr; }
    }
  </style>
</head>

<body>
  <header>
    <div class="topbar">
      <div class="brand">
        <span class="mark">🔥❤</span>
        <div>🔥❤ M5SUKA Chebra ❤🔥</div>
      </div>

      <!-- HEADER: Parduotuvė / Kolekcijos / Community / Discord -->
      <nav>
        <a class="active" href="#home">PAGRINDINIS</a>
        <a href="#shop">PARDUOTUVĖ</a>
        <a href="#kolekcijos">KOLEKCIJOS</a>
        <a href="#community">COMMUNITY</a>
        <a href="https://discord.gg/7ZM55bfe" target="_blank" rel="noreferrer">DISCORD 🔥</a>

        <a class="cartBtn" href="#krepselis" id="openCart" aria-label="Krepšelis">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M6 6h15l-1.5 9h-13z"></path>
            <path d="M6 6l-2-3H1"></path>
            <circle cx="9" cy="20" r="1.6"></circle>
            <circle cx="18" cy="20" r="1.6"></circle>
          </svg>
          <span>KREPŠELIS</span>
          <span class="badge" id="cartCount">0</span>
        </a>
      </nav>
    </div>
    <div class="divider"></div>
  </header>

  <main class="wrap" id="home">

    <!-- 🔥 HERO SEKCIJA -->
    <section class="section" aria-label="Hero">
      <div class="hero">
        <div class="heroCard">
          <h1 class="heroTitle">Žaisk ilgiau. Sėdėk rimčiau.</h1>
          <div class="heroSub">
            Visos dienos gaming komfortas, sukurtas M5SUKA chebrai.
          </div>

          <div class="ctaRow">
            <a class="btn primary" href="#shop">🛒 Pirkti dabar</a>
            <a class="btn" href="https://discord.gg/7ZM55bfe" target="_blank" rel="noreferrer">🔥 Prisijunk prie chebros</a>
          </div>
        </div>

        <div class="heroImg" aria-label="Baneris">
          <!-- Pakeisk į savo banerį -->
          <img src="https://images.unsplash.com/photo-1542751110-97427bbecf20?auto=format&fit=crop&w=1600&q=80" alt="M5SUKA baneris">
        </div>
      </div>
    </section>

    <!-- 🎥 VIDEO SEKCIJA (TikTok + YouTube) -->
    <section class="section" id="video" aria-label="Video">
      <div class="inner">
        <h2>Kaip sėdi M5SUKA chebra</h2>
        <p>
          Tikri setup’ai. Tikros reakcijos.<br>
          Jokių fake reklamų – tik chebros patirtis.
        </p>

        <div class="twoCol">
          <div class="embedBox">
            <strong>TikTok video embed</strong>
            <div class="embedHint">
              Įkelk TikTok embed kodą vietoje šito bloko.
            </div>
            <!-- ĮKLIJUOK TIKTOK EMBED ČIA -->
          </div>

          <div class="embedBox">
            <strong>YouTube Shorts / video</strong>
            <div class="embedHint">
              Įkelk YouTube iframe embed vietoje šito bloko.
            </div>
            <!-- ĮKLIJUOK YOUTUBE EMBED ČIA -->
          </div>
        </div>
      </div>
    </section>

    <!-- 👥 COMMUNITY SEKCIJA -->
    <section class="section" id="community" aria-label="Community">
      <div class="inner">
        <h2>M5SUKA Chebra</h2>
        <p>
          Tai ne šiaip parduotuvė.<br>
          Tai bendruomenė, kur renkasi žaidėjai, streameriai ir tie,
          kurie sėdi ilgai ir rimtai.
        </p>

        <!-- Skaičiai (jei turi) — pakeisk XXX į tikrą -->
        <div class="stats">
          <div class="stat">🔥 XXX+ <small>narių Discorde</small></div>
          <div class="stat">🎮 Kasdien <small>pokalbiai + setup’ai</small></div>
          <div class="stat">🎁 Išskirtiniai <small>deal’ai ir drop’ai</small></div>
        </div>

        <div class="ctaRow" style="margin-top: 14px;">
          <a class="btn primary" href="https://discord.gg/7ZM55bfe" target="_blank" rel="noreferrer">🔥 Prisijungti prie Discord</a>
        </div>
      </div>
    </section>

    <!-- 🪑 PRODUKTŲ SEKCIJA -->
    <section class="section" id="shop" aria-label="Parduotuvė">
      <div class="inner">
        <h2>Chebros pasirinkimas</h2>

        <div class="toolbar">
          <div class="count"><span id="countText">8</span> produktai</div>
          <input class="search" id="search" placeholder="Paieška (pvz. kilimėlis, hoodie)..." />
        </div>

        <div class="grid" id="grid"></div>
      </div>
    </section>

    <!-- KOLEKCIJOS -->
    <section class="section" id="kolekcijos" aria-label="Kolekcijos">
      <div class="inner">
        <h2>Kolekcijos</h2>
        <p>
          Čia gali dėti kolekcijas: <b>Merch</b>, <b>Setup</b>, <b>Limited</b> ir t.t.
          (vėliau galim padaryti filtrus arba atskirus puslapius).
        </p>
      </div>
    </section>

    <!-- ⚙️ KODĖL M5SUKA? -->
    <section class="section" id="kodel" aria-label="Kodėl M5SUKA">
      <div class="inner">
        <h2>Kodėl M5SUKA?</h2>

        <div class="iconGrid">
          <div class="iconItem">Visos dienos žaidimų komfortas</div>
          <div class="iconItem">Lanksti nugaros atrama</div>
          <div class="iconItem">Nuolatinė nugaros atrama</div>
          <div class="iconItem">Premium medžiagos</div>
          <div class="iconItem">Sukurta ilgoms sesijoms</div>
        </div>
      </div>
    </section>

    <!-- 📱 SOCIAL FEED -->
    <section class="section" id="social" aria-label="Social feed">
      <div class="inner">
        <h2>M5SUKA gyvai</h2>
        <p>
          Sek mus TikTok, YouTube ir Discord – ten vyksta visas veiksmas.
        </p>

        <div class="twoCol">
          <div class="embedBox">
            <strong>TikTok klipai</strong>
            <div class="embedHint">Įkelk TikTok feed / embed.</div>
            <!-- TIKTOK FEED EMBED -->
          </div>
          <div class="embedBox">
            <strong>YouTube preview</strong>
            <div class="embedHint">Įkelk YouTube kanalo ar video embed.</div>
            <!-- YOUTUBE PREVIEW EMBED -->
          </div>
        </div>

        <div class="embedBox" style="margin-top: 14px;">
          <strong>Community momentai</strong>
          <div class="embedHint">Čia gali rodyti Discord screenshot’us, UGC nuotraukas, atsiliepimus.</div>
        </div>
      </div>
    </section>

    <!-- 🔥 FINAL CTA -->
    <section class="section" aria-label="Final CTA">
      <div class="inner">
        <h2>Pakelk komfortą į kitą lygį</h2>
        <div class="ctaRow">
          <a class="btn primary" href="#shop">🛒 Pirkti dabar</a>
          <a class="btn" href="https://discord.gg/7ZM55bfe" target="_blank" rel="noreferrer">🎮 Prisijunk prie chebros</a>
        </div>
      </div>
    </section>

    <!-- KONTAKTAI -->
    <section class="section" id="kontaktai" aria-label="Kontaktai">
      <div class="inner">
        <h2>Kontaktai</h2>
        <p>
          El. paštas:
          <a href="mailto:lukendzo95@gmail.com">lukendzo95@gmail.com</a><br>
          Discord:
          <a href="https://discord.gg/7ZM55bfe" target="_blank" rel="noreferrer">discord.gg/7ZM55bfe</a>
        </p>
      </div>
    </section>

    <!-- FOOTER -->
    <footer>
      © 2026 🔥❤ M5SUKA Chebra ❤🔥
      <div class="footerLinks">
        <a href="https://discord.gg/7ZM55bfe" target="_blank" rel="noreferrer">Discord</a>
        <a href="https://www.tiktok.com/@boycherry.1234" target="_blank" rel="noreferrer">TikTok</a>
        <a href="https://www.youtube.com/" target="_blank" rel="noreferrer">YouTube</a>
        <a href="#kontaktai">Kontaktai</a>
        <a href="#pristatymas">Pristatymas &amp; garantija</a>
      </div>
    </footer>

    <section class="section" id="pristatymas" aria-label="Pristatymas ir garantija">
      <div class="inner">
        <h2>Pristatymas & garantija</h2>
        <p>
          Prekes pristatome visoje Lietuvoje patikimų kurjerių pagalba.
          Užsakymas paruošiamas ir išsiunčiamas per <strong>1–3 darbo dienas</strong> nuo apmokėjimo gavimo.
        </p>
        <p>
          <strong>Pristatymas:</strong>
          <ul>
            <li>Pristatymas į namus arba paštomatą</li>
            <li>Pristatymo kaina nurodoma užsakymo metu</li>
            <li>Užsakymams virš <strong>30 €</strong> – pristatymas <strong>nemokamas</strong></li>
          </ul>
        </p>
        <p>
          <strong>Garantija:</strong> Visoms prekėms suteikiama <strong>24 mėnesių garantija</strong>, jei nenurodyta kitaip. Garantija galioja gamykliniams defektams ir netaikoma gedimams dėl netinkamo naudojimo.
        </p>
      </div>
    </section>

  </main>

  <!-- PRODUCT MODAL -->
  <div class="modal" id="productModal" aria-hidden="true">
    <div class="backdrop" data-close></div>
    <div class="sheet" role="dialog" aria-modal="true" aria-label="Produktas">
      <div class="sheetHead">
        <strong id="pmTitle">Produktas</strong>
        <button class="close" type="button" data-close aria-label="Uždaryti">✕</button>
      </div>
      <div class="sheetBody" id="pmBody"></div>
    </div>
  </div>

  <!-- CART DRAWER -->
  <div class="drawer" id="cartDrawer" aria-hidden="true">
    <div class="backdrop" data-close></div>
    <aside class="drawerPanel" aria-label="Krepšelis">
      <div class="sheetHead">
        <strong>🛒 Krepšelis</strong>
        <button class="close" type="button" data-close aria-label="Uždaryti">✕</button>
      </div>
      <div class="drawerBody" id="cartLines"></div>
      <div class="drawerFoot">
        <div class="totals">
          <span>Viso</span>
          <span id="cartTotal">€0.00</span>
        </div>

        <button class="btn primary" type="button" id="checkoutBtn" style="width:100%;">Checkout (užsakymas)</button>

        <form class="form" id="checkoutForm" style="display:none;">
          <input class="input" id="cName" placeholder="Vardas" required />
          <input class="input" id="cEmail" type="email" placeholder="El. paštas" required />
          <input class="input" id="cDiscord" placeholder="Discord (nebūtina)" />
          <textarea class="input" id="cNote" placeholder="Pastaba (spalva, dydis, pristatymas ir t.t.)"></textarea>
          <button class="btn primary" type="submit" style="width:100%;">Siųsti užsakymą</button>
          <button class="btn" type="button" id="backToCart" style="width:100%;">Atgal</button>
          <small style="color:rgba(0,0,0,.7);">
            Užsakymas bus išsiųstas į el. paštą (atsidarys tavo mail app) — be backend’o.
          </small>
        </form>
      </div>
    </aside>
  </div>

  <script>
    // ==== CONFIG (TAVO KONTAKTAI) ====
    const SHOP_EMAIL = "lukendzo95@gmail.com";

    // ==== PRODUCTS (8 vnt) ====
    const PRODUCTS = [
      { id:"p1", title:"Kilimėlis M5SUKA (ART)", price:19.99, tag:"900×400", img:"https://images.unsplash.com/photo-1527864550417-7fd91fc51a46?auto=format&fit=crop&w=1600&q=80", desc:"Didelis pelės kilimėlis su M5SUKA vibe.", badges:["Patvirtinta chebros","Matyta TikTok’e"] },
      { id:"p2", title:"Kilimėlis M5SUKA (GTA)", price:19.99, tag:"900×400", img:"https://images.unsplash.com/photo-1517336714731-489689fd1ca8?auto=format&fit=crop&w=1600&q=80", desc:"Klasika ant stalo — ryškus printas.", badges:["Patvirtinta chebros","Matyta TikTok’e"] },
      { id:"p3", title:"Hoodie M5SUKA", price:39.99, tag:"S–XXL", img:"https://images.unsplash.com/photo-1520975958225-8d3f9c3c0b31?auto=format&fit=crop&w=1600&q=80", desc:"Šiltas hoodie, normalus fit.", badges:["Patvirtinta chebros"] },
      { id:"p4", title:"Marškinėliai M5SUKA", price:24.99, tag:"S–XXL", img:"https://images.unsplash.com/photo-1520975661595-6453be3f7070?auto=format&fit=crop&w=1600&q=80", desc:"Basic tee su logo/printu.", badges:["Patvirtinta chebros"] },
      { id:"p5", title:"Kepurė M5SUKA", price:17.99, tag:"One size", img:"https://images.unsplash.com/photo-1520975693412-35a37d5a2c04?auto=format&fit=crop&w=1600&q=80", desc:"Kepurė su siuvinėtu ženklu.", badges:["Matyta TikTok’e"] },
      { id:"p6", title:"Lipdukų pack", price:6.99, tag:"10 vnt", img:"https://images.unsplash.com/photo-1520975867597-0f8a09a9b6f6?auto=format&fit=crop&w=1600&q=80", desc:"Lipdukai laptopui/telefonui.", badges:["Patvirtinta chebros"] },
      { id:"p7", title:"Puodelis M5SUKA", price:12.99, tag:"330ml", img:"https://images.unsplash.com/photo-1511920170033-f8396924c348?auto=format&fit=crop&w=1600&q=80", desc:"Puodelis su printu.", badges:["Matyta TikTok’e"] },
      { id:"p8", title:"Tote bag M5SUKA", price:14.99, tag:"Canvas", img:"https://images.unsplash.com/photo-1593032457866-5c6f4f7a9c3a?auto=format&fit=crop&w=1600&q=80", desc:"Tote bag — patogu kasdienai.", badges:["Patvirtinta chebros"] },
    ];

    // ==== STATE ====
    const cart = JSON.parse(localStorage.getItem("m5_cart") || "{}"); // {id: qty}

    const $ = (q, el=document) => el.querySelector(q);
    const $$ = (q, el=document) => [...el.querySelectorAll(q)];

    const grid = $("#grid");
    const search = $("#search");
    const countText = $("#countText");

    const productModal = $("#productModal");
    const pmTitle = $("#pmTitle");
    const pmBody = $("#pmBody");

    const cartDrawer = $("#cartDrawer");
    const cartLines = $("#cartLines");
    const cartTotal = $("#cartTotal");
    const cartCount = $("#cartCount");
    const openCart = $("#openCart");

    const checkoutBtn = $("#checkoutBtn");
    const checkoutForm = $("#checkoutForm");
    const backToCart = $("#backToCart");

    function money(n){ return "€" + n.toFixed(2); }

    function saveCart(){
      localStorage.setItem("m5_cart", JSON.stringify(cart));
      renderCartBadge();
    }

    function getQty(id){ return cart[id] || 0; }
    function setQty(id, qty){
      if(qty <= 0) delete cart[id];
      else cart[id] = qty;
      saveCart();
    }

    function renderCartBadge(){
      const totalItems = Object.values(cart).reduce((a,b)=>a+b,0);
      cartCount.textContent = totalItems;
    }

    function filteredProducts(){
      const q = (search.value || "").trim().toLowerCase();
      const list = PRODUCTS.filter(p =>
        (p.title + " " + p.tag + " " + p.desc).toLowerCase().includes(q)
      );
      countText.textContent = list.length;
      return list;
    }

    function renderGrid(){
      const list = filteredProducts();
      grid.innerHTML = list.map(p => `
        <article class="card" data-open="${p.id}" tabindex="0" role="button" aria-label="${p.title}">
          <div class="badges">
            ${(p.badges || []).slice(0,2).map(b => `<span class="tagBadge">${b}</span>`).join("")}
          </div>
          <img src="${p.img}" alt="${p.title}">
          <div class="info">
            <h3>${p.title}</h3>
            <div class="sub">${p.tag}</div>
            <div class="row">
              <div class="price">${money(p.price)}</div>
              <button class="btn" type="button" data-add="${p.id}">Į krepšelį</button>
            </div>
          </div>
        </article>
      `).join("");
    }

    function openProduct(id){
      const p = PRODUCTS.find(x=>x.id===id);
      if(!p) return;
      let qty = getQty(id) || 1;

      pmTitle.textContent = p.title;
      pmBody.innerHTML = `
        <div class="productView">
          <img src="${p.img}" alt="${p.title}">
          <div>
            <div style="font-weight:1000;font-size:20px; text-transform:uppercase;">${p.title}</div>
            <div class="pill">${p.tag}</div>
            <p class="muted" style="line-height:1.6; margin-top: 10px;">${p.desc}</p>
            <div class="muted" style="font-size:12px; margin-top: 6px;">
              ${(p.badges||[]).map(b=>`<span class="pill" style="margin-right:6px;">${b}</span>`).join("")}
            </div>
            <div style="font-size:22px; font-weight:1000; margin-top: 10px;">${money(p.price)}</div>

            <div class="qtyRow">
              <div class="qty" aria-label="Kiekis">
                <button type="button" id="dec">−</button>
                <span id="qv">${qty}</span>
                <button type="button" id="inc">+</button>
              </div>
              <button class="btn primary" type="button" id="addNow">Pridėti į krepšelį</button>
            </div>

            <p class="muted" style="margin-top: 10px; font-size: 12px;">
              Pastabos (dydis/spalva/pristatymas) — įrašysi checkout’e.
            </p>
          </div>
        </div>
      `;

      productModal.classList.add("show");
      productModal.setAttribute("aria-hidden","false");

      const qv = $("#qv", pmBody);
      $("#dec", pmBody).onclick = () => { qty = Math.max(1, qty-1); qv.textContent = qty; };
      $("#inc", pmBody).onclick = () => { qty = qty+1; qv.textContent = qty; };
      $("#addNow", pmBody).onclick = () => {
        setQty(id, getQty(id) + qty);
        closeModal();
        openCartDrawer();
      };
    }

    function closeModal(){
      productModal.classList.remove("show");
      productModal.setAttribute("aria-hidden","true");
    }

    function openCartDrawer(){
      renderCart();
      cartDrawer.classList.add("show");
      cartDrawer.setAttribute("aria-hidden","false");
    }
    function closeCartDrawer(){
      cartDrawer.classList.remove("show");
      cartDrawer.setAttribute("aria-hidden","true");
      checkoutForm.style.display = "none";
      checkoutBtn.style.display = "block";
    }

    function renderCart(){
      const ids = Object.keys(cart);
      if(ids.length === 0){
        cartLines.innerHTML = `<p class="muted">Krepšelis tuščias.</p>`;
        cartTotal.textContent = money(0);
        return;
      }

      let total = 0;
      cartLines.innerHTML = ids.map(id => {
        const p = PRODUCTS.find(x=>x.id===id);
        const qty = cart[id];
        const lineTotal = (p?.price || 0) * qty;
        total += lineTotal;

        return `
          <div class="line">
            <img src="${p.img}" alt="${p.title}">
            <div>
              <h4>${p.title}</h4>
              <div class="small">${p.tag}</div>
              <div class="small">${money(p.price)} × ${qty} = <b>${money(lineTotal)}</b></div>
            </div>
            <div class="right">
              <button class="btn" type="button" data-minus="${id}" aria-label="Minus">−</button>
              <button class="btn" type="button" data-plus="${id}" aria-label="Plus">+</button>
              <button class="btn" type="button" data-remove="${id}" aria-label="Ištrinti">✕</button>
            </div>
          </div>
        `;
      }).join("");

      cartTotal.textContent = money(total);
    }

    function cartSummaryText(customer){
      const ids = Object.keys(cart);
      let lines = [];
      let total = 0;

      for(const id of ids){
        const p = PRODUCTS.find(x=>x.id===id);
        const qty = cart[id];
        const lineTotal = p.price * qty;
        total += lineTotal;
        lines.push(`- ${p.title} (${p.tag}) x${qty} = ${money(lineTotal)}`);
      }

      return [
        "🔥❤ M5SUKA Chebra ❤🔥 — UŽSAKYMAS",
        "",
        `Vardas: ${customer.name}`,
        `El. paštas: ${customer.email}`,
        `Discord: ${customer.discord || "-"}`,
        "",
        "Prekės:",
        ...lines,
        "",
        `Viso: ${money(total)}`,
        "",
        `Pastaba: ${customer.note || "-"}`,
      ].join("\n");
    }

    // ==== EVENTS ====
    search.addEventListener("input", renderGrid);

    grid.addEventListener("click", (e) => {
      const add = e.target.closest("[data-add]")?.getAttribute("data-add");
      if(add){
        setQty(add, getQty(add) + 1);
        return;
      }
      const open = e.target.closest("[data-open]")?.getAttribute("data-open");
      if(open) openProduct(open);
    });

    grid.addEventListener("keydown", (e) => {
      if(e.key !== "Enter") return;
      const open = e.target.closest("[data-open]")?.getAttribute("data-open");
      if(open) openProduct(open);
    });

    $$(".modal [data-close], .drawer [data-close]").forEach(el=>{
      el.addEventListener("click", () => { closeModal(); closeCartDrawer(); });
    });

    document.addEventListener("keydown", (e)=>{
      if(e.key === "Escape"){ closeModal(); closeCartDrawer(); }
    });

    openCart.addEventListener("click", (e)=>{ e.preventDefault(); openCartDrawer(); });

    cartDrawer.addEventListener("click", (e)=>{
      const minus = e.target.closest("[data-minus]")?.getAttribute("data-minus");
      const plus  = e.target.closest("[data-plus]")?.getAttribute("data-plus");
      const rem   = e.target.closest("[data-remove]")?.getAttribute("data-remove");
      if(minus){ setQty(minus, getQty(minus) - 1); renderCart(); }
      if(plus){ setQty(plus, getQty(plus) + 1); renderCart(); }
      if(rem){ setQty(rem, 0); renderCart(); }
    });

    checkoutBtn.addEventListener("click", ()=>{
      if(Object.keys(cart).length === 0) return alert("Krepšelis tuščias.");
      checkoutForm.style.display = "grid";
      checkoutBtn.style.display = "none";
    });

    backToCart.addEventListener("click", ()=>{
      checkoutForm.style.display = "none";
      checkoutBtn.style.display = "block";
    });

    checkoutForm.addEventListener("submit", (e)=>{
      e.preventDefault();
      const customer = {
        name: $("#cName").value.trim(),
        email: $("#cEmail").value.trim(),
        discord: $("#cDiscord").value.trim(),
        note: $("#cNote").value.trim(),
      };
      if(!customer.name || !customer.email) return;

      const subject = encodeURIComponent("M5SUKA užsakymas: " + customer.name);
      const body = encodeURIComponent(cartSummaryText(customer));
      window.location.href = `mailto:${SHOP_EMAIL}?subject=${subject}&body=${body}`;
    });

    // init
    renderGrid();
    renderCartBadge();
  </script>
</body>
</html>