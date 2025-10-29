
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Karim Noui | President of Nguyễn Kim</title>
  <meta name="description" content="Leadership profile of Karim Noui – President of Nguyễn Kim Vietnam: vision, transformation, customer experience, measurable results, and leadership philosophy."/>
  <meta property="og:title" content="Karim Noui | President of Nguyễn Kim" />
  <meta property="og:description" content="Leading the transformation of Vietnam’s electronics retail landscape." />
  <meta property="og:type" content="website" />
  <style>
    :root{
      --bg:#ffffff;
      --fg:#000000;
      --muted:#444444;
      --brand:#e11d48;
      --card:#ffffff;
      --line:#e5e5e5;
      --pill:#f8f8f8;
      --shadow:0 4px 14px rgba(0,0,0,.1);
    }

    html,body{
      margin:0;
      height:100%;
      scroll-behavior:smooth;
      background:var(--bg);
      color:var(--fg);
      font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,"Helvetica Neue",Arial,"Noto Sans",sans-serif;
      max-width:100%;
      overflow-x:hidden; /* ✅ chặn tràn ngang */
    }

    a{color:inherit;text-decoration:none}
    .container{
      max-width:1080px;
      margin:0 auto;
      padding:0 20px;
      box-sizing:border-box;
      overflow-x:hidden; /* ✅ an toàn cho grid */
    }

    /* Header / Hero */
    header{
      position:relative;
      min-height:68vh;
      display:grid;
      place-items:center;
      overflow:hidden;
      background:linear-gradient(180deg,rgba(255,255,255,.85),rgba(255,255,255,.95)),url('hero.jpg') center/cover no-repeat;
      width:100%;
      box-sizing:border-box;
    }

    header .overlay{
      position:absolute;inset:0;
      background:radial-gradient(60% 60% at 30% 30%,rgba(225,29,72,.25),transparent 60%);
    }

    .hero{
      position:relative;
      z-index:2;
      display:grid;
      gap:16px;
      text-align:center;
      padding:56px 0;
      width:100%;
      box-sizing:border-box;
    }

    .badge{
      display:inline-flex;
      align-items:center;
      gap:8px;
      background:var(--pill);
      border:1px solid var(--line);
      padding:8px 12px;
      border-radius:999px;
      font-size:12px;
      color:var(--muted);
      flex-shrink:0;
    }

    .title{
      font-weight:800;
      line-height:1.05;
      letter-spacing:.3px;
      font-size:clamp(28px,5vw,56px);
    }

    .subtitle{
      font-size:clamp(14px,2.4vw,18px);
      color:var(--muted);
    }

    .cta{
      display:flex;
      gap:12px;
      justify-content:center;
      margin-top:10px;
      flex-wrap:wrap;
      width:100%;
      max-width:100%;
      box-sizing:border-box;
      overflow-x:hidden;
    }

    .btn{
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

    .btn:hover{opacity:.9;transform:translateY(-2px)}
    .btn.alt{
      background:transparent;
      border:1px solid var(--brand);
      color:var(--brand)
    }

    /* Section */
    section{
      padding:60px 0;
      border-top:1px solid var(--line);
      width:100%;
      box-sizing:border-box;
      overflow-x:hidden;
    }

    section h2{
      font-size:clamp(22px,4vw,34px);
      margin:0 0 12px;
    }

    section p.lead{
      color:var(--muted);
      font-size:18px;
    }

    /* Grid cards */
    .grid{
      display:grid;
      gap:18px;
      width:100%;
      max-width:100%;
      box-sizing:border-box;
      overflow-x:hidden;
    }

    @media(min-width:720px){.grid.cols-2{grid-template-columns:1fr 1fr}}
    @media(min-width:980px){.grid.cols-3{grid-template-columns:repeat(3,1fr)}}

    .card{
      background:var(--card);
      border:1px solid var(--line);
      border-radius:18px;
      padding:22px;
      box-shadow:var(--shadow);
      box-sizing:border-box;
      overflow:hidden;
    }

    .card h3{margin:0 0 10px;font-size:18px}
    .meta{display:flex;gap:10px;flex-wrap:wrap;margin:8px 0 0}
    .pill{
      background:var(--pill);
      border:1px solid var(--line);
      border-radius:999px;
      padding:6px 10px;
      font-size:12px;
      color:var(--muted);
      flex-shrink:0;
    }

    /* KPI band */
    .kpis{
      display:grid;
      gap:14px;
      grid-template-columns:repeat(2,1fr);
      width:100%;
      box-sizing:border-box;
      overflow-x:hidden;
    }

    @media(min-width:820px){.kpis{grid-template-columns:repeat(4,1fr)}}

    .kpi{
      background:var(--card);
      border:1px solid var(--line);
      padding:18px;
      border-radius:16px;
      text-align:center;
      box-sizing:border-box;
    }

    .kpi .num{font-size:28px;font-weight:800;color:var(--brand)}
    .kpi .lbl{font-size:12px;color:var(--muted)}

    /* Quote */
    blockquote{
      margin:0;
      padding:18px 22px;
      border-left:4px solid var(--brand);
      background:var(--pill);
      color:var(--muted);
      border-radius:8px;
      box-sizing:border-box;
    }

    /* Footer */
    footer{
      padding:36px 0;
      color:var(--muted);
      text-align:center;
      border-top:1px solid var(--line);
      width:100%;
      box-sizing:border-box;
      overflow-x:hidden;
    }

    /* ---------- MOBILE OPTIMIZATION ---------- */
    @media(max-width:720px){
      body{font-size:15px;line-height:1.5}
      .container{padding:0 16px}
      header{min-height:60vh;background-position:center}
      .hero{padding:40px 0;gap:12px}
      .badge{font-size:11px;padding:6px 10px}
      .title{font-size:clamp(26px,7vw,42px)}
      .subtitle{font-size:15px;padding:0 10px}
      .cta{flex-direction:column;align-items:center;gap:10px}
      .btn{width:90%;max-width:280px;padding:12px;font-size:15px}
      section{padding:40px 0}
      .grid.cols-2,.grid.cols-3{grid-template-columns:1fr}
      .kpis{grid-template-columns:1fr 1fr}
      .card{padding:18px}
      .card h3{font-size:17px}
      .lead{font-size:16px}
      blockquote{font-size:14px;padding:14px 18px}
      footer small{font-size:12px;line-height:1.4;display:block;padding:0 8px}
    }

    /* Print */
    @media print{
      header{min-height:auto;background:none}
      .btn,.cta{display:none}
      section{padding:24px 0}
      .card, .kpi{break-inside:avoid}
    }

    /* ✅ Fix overflow cho toàn site */
    img, video {
      max-width:100%;
      height:auto;
      display:block;
    }
  </style>
</head>
<body>
  <header>
    <div class="overlay" aria-hidden="true"></div>
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
    <!-- Vision -->
    <section id="vision" aria-labelledby="vision-title">
      <h2 id="vision-title">Visionary Leadership for a New Era of Retail</h2>
      <p class="lead">Under Karim Noui’s leadership, Nguyễn Kim (NK) is positioned to become Vietnam’s leading home-electronics retailer by delivering the best customer experience through innovation and trust. NK connects technology, service, and emotion in every home.</p>
      <div class="grid cols-2" style="margin-top:16px">
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

    <!-- Strategic Transformation -->
    <section id="transformation" aria-labelledby="transform-title">
      <h2 id="transform-title">Strategic Transformation 2024–2028</h2>
      <div class="grid cols-2">
        <div class="card"><h3>Rebuilding Profitability</h3><p>Closed non-performing stores, renovated key locations, optimized assortment and cost structure, and focused resources on front-line impact.</p></div>
        <div class="card"><h3>Omnichannel Expansion</h3><p>Integrated offline & online. Drove Marketplace and Telesales—achieving <em>Top 1 in Shopee Mall (Home Appliances, 2025)</em>.</p></div>
        <div class="card"><h3>AI & Data-Driven Management</h3><p>Real-time control via Power BI and R&amp;D projects in AI to elevate customer experience and supply-chain efficiency.</p></div>
        <div class="card"><h3>Operational Excellence</h3><p>Lean organization, streamlined logistics across three DCs, and disciplined back-office optimization.</p></div>
        <div class="card"><h3>Partnership Synergy</h3><p>360° collaborations with global brands and exploration of M&amp;A synergies to build national scale and efficiency.</p></div>
      </div>
    </section>

    <!-- KPIs / Results -->
    <section id="results" aria-labelledby="results-title">
      <h2 id="results-title">Driving Measurable Results</h2>
      <p class="lead">Tangible outcomes of NK’s transformation under Karim’s leadership.</p>
      <div class="kpis" style="margin-top:14px">
        <div class="kpi"><div class="num">+140%</div><div class="lbl">EBITDA YoY (to 6.4%)</div></div>
        <div class="kpi"><div class="num">+1.1 pts</div><div class="lbl">Gross Profit Margin</div></div>
        <div class="kpi"><div class="num">−23%</div><div class="lbl">Stock YoY (81-day turn)</div></div>
        <div class="kpi"><div class="num">+83%</div><div class="lbl">Online Sales YoY (18% mix)</div></div>
      </div>
      <div class="grid cols-2" style="margin-top:16px">
        <div class="card"><h3>Customer Experience</h3><ul><li>Premium service & curated design for A–B segments</li><li>Affordable offers & flexible payment for C–D</li><li>Livestream & KOC content to engage younger audiences</li><li>Trusted after-sales & responsive call center</li></ul></div>
        <div class="card"><h3>Healthy Merchandise Mix</h3><p>CE | DIG = <strong>89 | 11</strong>, supporting margin uplift and sustainable growth.</p></div>
      </div>
    </section>

    <!-- Leadership & Philosophy -->
    <section id="leadership" aria-labelledby="leader-title">
      <h2 id="leader-title">Leadership & Philosophy</h2>
      <div class="grid cols-2">
        <div class="card"><h3>Leadership through Synergy</h3><p>“1 + 1 &gt; 2” when people, brands, and ideas work in harmony. Teams think analytically and act creatively—balancing discipline with empathy.</p><div class="meta"><span class="pill">Visionary & Pragmatic</span><span class="pill">Empowers Talent</span><span class="pill">Innovation Mindset</span></div></div>
        <div class="card"><h3>Execution Principles</h3><ul><li>Clarity of strategy, rigor in finance</li><li>Operational excellence & continuous improvement</li><li>Partner ecosystem built on long-term trust</li></ul></div>
      </div>
      <blockquote>“Retail leadership is not only about selling products—it’s about building trust, inspiring teams, and bringing innovation to every household.” — <strong>Karim Noui</strong></blockquote>
    </section>

    <!-- Outlook -->
    <section id="outlook" aria-labelledby="outlook-title">
      <h2 id="outlook-title">Legacy & Forward Outlook</h2>
      <p class="lead">NK’s next growth cycle toward 2030 aims to set the benchmark for modern Vietnamese retail—combining scale, intelligence, and humanity.</p>
    </section>
  </main>

  <footer>
    <div class="container">
      <small>© <span id="year"></span> Nguyễn Kim • Leadership Profile • Designed for single-file hosting (GitHub Pages, Netlify, Vercel). Replace <code>hero.jpg</code> with your banner image.</small>
    </div>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
