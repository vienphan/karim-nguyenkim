
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Karim Noui | President of Nguyễn Kim</title>
  <meta name="description" content="Leadership profile of Karim Noui – President of Nguyễn Kim Vietnam: vision, transformation, customer experience, measurable results, and leadership philosophy.">
  <meta property="og:title" content="Karim Noui | President of Nguyễn Kim">
  <meta property="og:description" content="Leading the transformation of Vietnam’s electronics retail landscape.">
  <meta property="og:type" content="website">
  <style>
    :root {
      --bg:#ffffff;
      --fg:#000000;
      --muted:#444;
      --brand:#e11d48;
      --card:#fff;
      --line:#e5e5e5;
      --pill:#f8f8f8;
      --shadow:0 4px 14px rgba(0,0,0,.1);
    }

    /* ==== GLOBAL RESET ==== */
    * {
      box-sizing:border-box;
      margin:0;
      padding:0;
      max-width:100%;
      overflow-wrap:break-word;
    }
    html, body {
      width:100%;
      height:100%;
      overflow-x:hidden;
      background:var(--bg);
      color:var(--fg);
      font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,"Helvetica Neue",Arial,"Noto Sans",sans-serif;
      scroll-behavior:smooth;
      line-height:1.6;
    }
    img, video {
      max-width:100%;
      height:auto;
      display:block;
    }
    a { color:inherit; text-decoration:none; }

    .container {
      width:100%;
      max-width:1080px;
      margin:0 auto;
      padding:0 20px;
    }

    /* ==== HEADER ==== */
    header {
      position:relative;
      display:flex;
      justify-content:center;
      align-items:center;
      min-height:68vh;
      overflow:hidden;
      background:
        linear-gradient(180deg,rgba(255,255,255,.85),rgba(255,255,255,.95)),
        url('hero.jpg') center/cover no-repeat;
    }
    header::after {
      content:"";
      position:absolute;
      inset:0;
      background:radial-gradient(60% 60% at 30% 30%,rgba(225,29,72,.25),transparent 60%);
    }
    .hero {
      position:relative;
      text-align:center;
      z-index:1;
      padding:56px 0;
      display:grid;
      gap:16px;
    }
    .badge {
      display:inline-flex;
      align-items:center;
      gap:8px;
      background:var(--pill);
      border:1px solid var(--line);
      padding:8px 12px;
      border-radius:999px;
      font-size:12px;
      color:var(--muted);
    }
    .title {
      font-size:clamp(28px,6vw,56px);
      font-weight:800;
      line-height:1.05;
    }
    .subtitle {
      color:var(--muted);
      font-size:clamp(14px,3vw,18px);
    }
    .cta {
      display:flex;
      flex-wrap:wrap;
      justify-content:center;
      gap:12px;
      margin-top:10px;
    }
    .btn {
      background:var(--brand);
      color:#fff;
      border:none;
      border-radius:12px;
      padding:12px 18px;
      font-weight:700;
      box-shadow:var(--shadow);
      cursor:pointer;
      transition:all .3s ease;
      white-space:nowrap;
    }
    .btn:hover { opacity:.9; transform:translateY(-2px); }
    .btn.alt { background:transparent; border:1px solid var(--brand); color:var(--brand); }

    /* ==== SECTIONS ==== */
    section {
      width:100%;
      border-top:1px solid var(--line);
      padding:60px 0;
    }
    section h2 {
      font-size:clamp(22px,4vw,34px);
      margin-bottom:12px;
    }
    section p.lead {
      color:var(--muted);
      font-size:18px;
      margin-bottom:16px;
    }

    /* ==== GRID / CARD ==== */
    .grid {
      display:grid;
      gap:18px;
      width:100%;
    }
    @media(min-width:720px){ .grid.cols-2{grid-template-columns:1fr 1fr;} }
    @media(min-width:980px){ .grid.cols-3{grid-template-columns:repeat(3,1fr);} }

    .card {
      background:var(--card);
      border:1px solid var(--line);
      border-radius:18px;
      padding:22px;
      box-shadow:var(--shadow);
    }
    .card h3 { margin-bottom:10px; font-size:18px; }
    .meta {
      display:flex;
      flex-wrap:wrap;
      gap:10px;
      margin-top:8px;
    }
    .pill {
      background:var(--pill);
      border:1px solid var(--line);
      border-radius:999px;
      padding:6px 10px;
      font-size:12px;
      color:var(--muted);
    }

    /* ==== KPI ==== */
    .kpis {
      display:grid;
      gap:14px;
      grid-template-columns:repeat(auto-fit,minmax(140px,1fr));
      margin-top:14px;
    }
    .kpi {
      background:var(--card);
      border:1px solid var(--line);
      border-radius:16px;
      padding:18px;
      text-align:center;
    }
    .kpi .num { font-size:28px; font-weight:800; color:var(--brand); }
    .kpi .lbl { font-size:12px; color:var(--muted); }

    /* ==== QUOTE ==== */
    blockquote {
      margin-top:24px;
      padding:18px 22px;
      border-left:4px solid var(--brand);
      background:var(--pill);
      color:var(--muted);
      border-radius:8px;
      font-size:15px;
    }

    /* ==== FOOTER ==== */
    footer {
      padding:36px 0;
      color:var(--muted);
      text-align:center;
      border-top:1px solid var(--line);
      font-size:14px;
    }

    /* ==== MOBILE OPTIMIZATION ==== */
    @media(max-width:720px) {
      .container { padding:0 16px; }
      .hero { padding:40px 0; gap:12px; }
      .badge { font-size:11px; padding:6px 10px; }
      .btn { width:90%; max-width:280px; padding:12px; font-size:15px; }
      .cta { flex-direction:column; align-items:center; gap:10px; }
      .card { padding:18px; }
      .card h3 { font-size:17px; }
      section { padding:40px 0; }
      blockquote { font-size:14px; padding:14px 18px; }
    }

    /* ==== PRINT ==== */
    @media print {
      header { min-height:auto; background:none; }
      .btn,.cta { display:none; }
      section { padding:24px 0; }
      .card, .kpi { break-inside:avoid; }
    }
  </style>
</head>
<body>
  <header>
    <div class="hero container">
      <span class="badge">Leadership Profile • President of Nguyễn Kim</span>
      <h1 class="title">Karim Noui</h1>
      <p class="subtitle">Leading the transformation of Vietnam’s electronics retail landscape</p>
      <div class="cta">
        <a class="btn" href="#vision">Read Profile</a>
        <a class="btn alt" href="#results">Key Results</a>
      </div>
    </div>
  </header>

  <main class="container">
    <section id="vision">
      <h2>Visionary Leadership for a New Era of Retail</h2>
      <p class="lead">Under Karim Noui’s leadership, Nguyễn Kim (NK) is positioned to become Vietnam’s leading home-electronics retailer by delivering the best customer experience through innovation and trust. NK connects technology, service, and emotion in every home.</p>
      <div class="grid cols-2">
        <div class="card">
          <h3>Ambition</h3>
          <p>Be the benchmark for customer experience in Vietnam’s electronics retail—online and offline—powered by data, AI, and trusted service.</p>
          <div class="meta">
            <span class="pill">Customer-centric</span>
            <span class="pill">Data-driven</span>
            <span class="pill">Innovation</span>
          </div>
        </div>
        <div class="card">
          <h3>One NK Experience</h3>
          <p>Seamless journeys across website, marketplace, telesales, and stores, with consistent pricing, installation quality, and after-sales care.</p>
          <div class="meta">
            <span class="pill">Omnichannel</span>
            <span class="pill">Installation & Warranty</span>
            <span class="pill">4.8★ Reviews</span>
          </div>
        </div>
      </div>
    </section>

    <section id="transformation">
      <h2>Strategic Transformation 2024–2028</h2>
      <div class="grid cols-2">
        <div class="card"><h3>Rebuilding Profitability</h3><p>Closed non-performing stores, renovated key locations, optimized assortment and cost structure, and focused resources on front-line impact.</p></div>
        <div class="card"><h3>Omnichannel Expansion</h3><p>Integrated offline & online. Drove Marketplace and Telesales—achieving <em>Top 1 in Shopee Mall (Home Appliances, 2025)</em>.</p></div>
        <div class="card"><h3>AI & Data-Driven Management</h3><p>Real-time control via Power BI and R&amp;D projects in AI to elevate customer experience and supply-chain efficiency.</p></div>
        <div class="card"><h3>Operational Excellence</h3><p>Lean organization, streamlined logistics across three DCs, and disciplined back-office optimization.</p></div>
        <div class="card"><h3>Partnership Synergy</h3><p>360° collaborations with global brands and exploration of M&amp;A synergies to build national scale and efficiency.</p></div>
      </div>
    </section>

    <section id="results">
      <h2>Driving Measurable Results</h2>
      <p class="lead">Tangible outcomes of NK’s transformation under Karim’s leadership.</p>
      <div class="kpis">
        <div class="kpi"><div class="num">+140%</div><div class="lbl">EBITDA YoY (to 6.4%)</div></div>
        <div class="kpi"><div class="num">+1.1 pts</div><div class="lbl">Gross Profit Margin</div></div>
        <div class="kpi"><div class="num">−23%</div><div class="lbl">Stock YoY (81-day turn)</div></div>
        <div class="kpi"><div class="num">+83%</div><div class="lbl">Online Sales YoY (18% mix)</div></div>
      </div>
      <div class="grid cols-2" style="margin-top:16px">
        <div class="card"><h3>Customer Experience</h3>
          <ul>
            <li>Premium service & curated design for A–B segments</li>
            <li>Affordable offers & flexible payment for C–D</li>
            <li>Livestream & KOC content to engage younger audiences</li>
            <li>Trusted after-sales & responsive call center</li>
          </ul>
        </div>
        <div class="card"><h3>Healthy Merchandise Mix</h3>
          <p>CE | DIG = <strong>89 | 11</strong>, supporting margin uplift and sustainable growth.</p>
        </div>
      </div>
    </section>

    <section id="leadership">
      <h2>Leadership & Philosophy</h2>
      <div class="grid cols-2">
        <div class="card"><h3>Leadership through Synergy</h3>
          <p>“1 + 1 &gt; 2” when people, brands, and ideas work in harmony. Teams think analytically and act creatively—balancing discipline with empathy.</p>
          <div class="meta">
            <span class="pill">Visionary & Pragmatic</span>
            <span class="pill">Empowers Talent</span>
            <span class="pill">Innovation Mindset</span>
          </div>
        </div>
        <div class="card"><h3>Execution Principles</h3>
          <ul>
            <li>Clarity of strategy, rigor in finance</li>
            <li>Operational excellence & continuous improvement</li>
            <li>Partner ecosystem built on long-term trust</li>
          </ul>
        </div>
      </div>
      <blockquote>“Retail leadership is not only about selling products—it’s about building trust, inspiring teams, and bringing innovation to every household.” — <strong>Karim Noui</strong></blockquote>
    </section>

    <section id="outlook">
      <h2>Legacy & Forward Outlook</h2>
      <p class="lead">NK’s next growth cycle toward 2030 aims to set the benchmark for modern Vietnamese retail—combining scale, intelligence, and humanity.</p>
    </section>
  </main>

  <footer>
  <div class="container">
    <small>
      © <span id="year"></span> Nguyễn Kim • 
      <a href="https://vienphan.github.io/karim-profile/" target="_blank" rel="noopener noreferrer">Karim Noui</a> • 
      <a href="https://vienphan.github.io/karim-profile/" target="_blank" rel="noopener noreferrer">Leadership Profile</a> •
    </small>
  </div>
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>
