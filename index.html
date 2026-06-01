<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Netflix Intelligence & Audience Segmentation Matrix — README</title>
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=DM+Mono:wght@300;400;500&family=DM+Sans:ital,wght@0,300;0,400;0,600;1,300&display=swap" rel="stylesheet"/>
<style>
  :root {
    --red: #E50914;
    --red-dim: #8b0000;
    --red-glow: rgba(229,9,20,0.18);
    --bg: #0a0a0a;
    --surface: #111111;
    --surface2: #181818;
    --border: rgba(229,9,20,0.22);
    --text: #e8e8e8;
    --muted: #888;
    --mono: 'DM Mono', monospace;
    --display: 'Bebas Neue', sans-serif;
    --body: 'DM Sans', sans-serif;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: var(--body);
    font-weight: 300;
    line-height: 1.7;
    min-height: 100vh;
    overflow-x: hidden;
  }

  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background: repeating-linear-gradient(0deg, transparent, transparent 2px, rgba(0,0,0,0.08) 2px, rgba(0,0,0,0.08) 4px);
    pointer-events: none;
    z-index: 1000;
  }

  /* ── HERO ── */
  .hero {
    position: relative;
    padding: 80px 60px 60px;
    border-bottom: 1px solid var(--border);
    overflow: hidden;
  }
  .hero::after {
    content: 'N';
    position: absolute;
    right: -20px; top: -40px;
    font-family: var(--display);
    font-size: 420px;
    color: rgba(229,9,20,0.04);
    line-height: 1;
    pointer-events: none;
    user-select: none;
  }

  .badge {
    display: inline-block;
    font-family: var(--mono);
    font-size: 11px;
    letter-spacing: 0.18em;
    color: var(--red);
    border: 1px solid var(--border);
    padding: 4px 12px;
    margin-bottom: 24px;
    text-transform: uppercase;
    animation: fadeUp 0.6s ease both;
  }

  h1 {
    font-family: var(--display);
    font-size: clamp(42px, 7vw, 88px);
    line-height: 0.95;
    letter-spacing: 0.04em;
    color: #fff;
    max-width: 800px;
    animation: fadeUp 0.7s 0.1s ease both;
  }
  h1 span { color: var(--red); }

  .hero-sub {
    margin-top: 24px;
    max-width: 560px;
    color: var(--muted);
    font-size: 15px;
    font-weight: 300;
    animation: fadeUp 0.7s 0.2s ease both;
  }

  .meta-row {
    display: flex;
    gap: 32px;
    flex-wrap: wrap;
    margin-top: 40px;
    animation: fadeUp 0.7s 0.3s ease both;
  }
  .meta-item { display: flex; flex-direction: column; gap: 4px; }
  .meta-label {
    font-family: var(--mono);
    font-size: 10px;
    letter-spacing: 0.15em;
    color: var(--red);
    text-transform: uppercase;
  }
  .meta-value { font-size: 14px; color: var(--text); }

  /* ── LAYOUT ── */
  .container { max-width: 1100px; margin: 0 auto; padding: 0 60px; }

  section {
    padding: 64px 0;
    border-bottom: 1px solid rgba(255,255,255,0.05);
    animation: fadeUp 0.6s ease both;
  }

  .section-eyebrow {
    font-family: var(--mono);
    font-size: 11px;
    letter-spacing: 0.2em;
    color: var(--red);
    text-transform: uppercase;
    margin-bottom: 12px;
  }

  h2 {
    font-family: var(--display);
    font-size: clamp(28px, 4vw, 46px);
    letter-spacing: 0.05em;
    color: #fff;
    margin-bottom: 28px;
  }

  h3 {
    font-family: var(--display);
    font-size: clamp(18px, 2.5vw, 28px);
    letter-spacing: 0.06em;
    color: #fff;
    margin: 36px 0 12px;
  }

  p {
    color: #bbb;
    font-size: 15px;
    max-width: 720px;
    margin-bottom: 16px;
  }

  /* ── PANELS GRID ── */
  .panels {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 1px;
    background: var(--border);
    border: 1px solid var(--border);
    margin-top: 40px;
  }
  .panel { background: var(--surface); padding: 32px 28px; transition: background 0.2s; }
  .panel:hover { background: var(--surface2); }
  .panel-num { font-family: var(--display); font-size: 48px; color: var(--red); line-height: 1; margin-bottom: 12px; opacity: 0.7; }
  .panel-title { font-family: var(--mono); font-size: 11px; letter-spacing: 0.15em; color: var(--red); text-transform: uppercase; margin-bottom: 10px; }
  .panel-desc { font-size: 13.5px; color: #999; line-height: 1.6; }

  /* ── STAT STRIP ── */
  .stat-strip { display: grid; grid-template-columns: repeat(4, 1fr); border: 1px solid var(--border); margin-top: 40px; }
  .stat-cell { padding: 28px 24px; border-right: 1px solid var(--border); position: relative; }
  .stat-cell:last-child { border-right: none; }
  .stat-cell::before {
    content: ''; position: absolute; top: 0; left: 0; right: 0; height: 2px;
    background: var(--red); transform: scaleX(0); transition: transform 0.3s;
  }
  .stat-cell:hover::before { transform: scaleX(1); }
  .stat-number { font-family: var(--display); font-size: 42px; color: #fff; line-height: 1; }
  .stat-unit { font-family: var(--mono); font-size: 13px; color: var(--red); margin-left: 4px; }
  .stat-label { font-family: var(--mono); font-size: 10px; letter-spacing: 0.14em; color: var(--muted); text-transform: uppercase; margin-top: 6px; }

  /* ── INSIGHTS LIST ── */
  .insights { list-style: none; margin-top: 32px; display: flex; flex-direction: column; }
  .insights li {
    display: flex; align-items: flex-start; gap: 20px;
    padding: 20px 0; border-bottom: 1px solid rgba(255,255,255,0.05);
    font-size: 14.5px; color: #bbb;
  }
  .insights li:last-child { border-bottom: none; }
  .insight-icon {
    flex-shrink: 0; width: 32px; height: 32px;
    background: var(--red-glow); border: 1px solid var(--border);
    display: flex; align-items: center; justify-content: center;
    font-size: 14px; margin-top: 2px;
  }
  .insight-strong { display: block; color: #fff; font-weight: 600; font-size: 13px; letter-spacing: 0.02em; margin-bottom: 4px; }

  /* ── STRATEGIC CARDS ── */
  .strat-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
    gap: 16px;
    margin-top: 36px;
  }
  .strat-card {
    background: var(--surface);
    border: 1px solid var(--border);
    padding: 28px 24px;
    position: relative;
    overflow: hidden;
    transition: border-color 0.25s, background 0.25s;
  }
  .strat-card:hover { background: var(--surface2); border-color: rgba(229,9,20,0.5); }
  .strat-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; width: 3px; height: 100%;
    background: var(--red);
  }
  .strat-num {
    font-family: var(--mono);
    font-size: 10px;
    letter-spacing: 0.2em;
    color: var(--red);
    margin-bottom: 10px;
  }
  .strat-title {
    font-family: var(--display);
    font-size: 20px;
    letter-spacing: 0.05em;
    color: #fff;
    margin-bottom: 10px;
    line-height: 1.15;
  }
  .strat-body { font-size: 13px; color: #999; line-height: 1.65; }

  /* ── IMPACT BULLETS ── */
  .impact-list {
    list-style: none;
    margin-top: 28px;
    border: 1px solid var(--border);
  }
  .impact-list li {
    display: flex;
    align-items: flex-start;
    gap: 18px;
    padding: 18px 24px;
    border-bottom: 1px solid rgba(255,255,255,0.04);
    font-size: 14.5px;
    color: #bbb;
    transition: background 0.2s;
  }
  .impact-list li:last-child { border-bottom: none; }
  .impact-list li:hover { background: var(--surface); }
  .impact-dot {
    flex-shrink: 0;
    width: 8px; height: 8px;
    background: var(--red);
    border-radius: 50%;
    margin-top: 8px;
  }

  /* ── SUMMARY BOX ── */
  .summary-box {
    margin-top: 40px;
    border: 1px solid var(--border);
    padding: 40px 36px;
    background: linear-gradient(135deg, rgba(229,9,20,0.05) 0%, transparent 60%);
    position: relative;
  }
  .summary-box::before {
    content: '📌';
    position: absolute;
    top: -14px; left: 32px;
    font-size: 22px;
    background: var(--bg);
    padding: 0 8px;
  }
  .summary-box p {
    color: #ccc;
    font-size: 15.5px;
    max-width: 100%;
    line-height: 1.8;
    margin-bottom: 0;
  }
  .summary-box p + p { margin-top: 14px; }

  /* ── TECH STACK ── */
  .tech-grid { display: flex; flex-wrap: wrap; gap: 10px; margin-top: 28px; }
  .tech-tag {
    font-family: var(--mono); font-size: 11.5px; letter-spacing: 0.1em;
    color: var(--text); background: var(--surface2);
    border: 1px solid rgba(255,255,255,0.1); padding: 6px 14px;
    transition: border-color 0.2s, color 0.2s;
  }
  .tech-tag:hover { border-color: var(--red); color: #fff; }
  .tech-tag.red { border-color: var(--border); color: var(--red); background: rgba(229,9,20,0.07); }

  /* ── DIVIDER ── */
  .red-rule { border: none; border-top: 1px solid var(--border); margin: 0; }

  /* ── FOOTER ── */
  footer {
    padding: 48px 60px;
    display: flex; align-items: center; justify-content: space-between;
    flex-wrap: wrap; gap: 16px;
    border-top: 1px solid var(--border);
  }
  .footer-brand { font-family: var(--display); font-size: 22px; letter-spacing: 0.06em; color: var(--red); }
  .footer-note { font-family: var(--mono); font-size: 11px; color: var(--muted); letter-spacing: 0.1em; }

  /* ── ANIMATIONS ── */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(18px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  ::-webkit-scrollbar { width: 4px; }
  ::-webkit-scrollbar-track { background: var(--bg); }
  ::-webkit-scrollbar-thumb { background: var(--red-dim); }

  @media (max-width: 700px) {
    .hero, .container, footer { padding-left: 24px; padding-right: 24px; }
    .stat-strip { grid-template-columns: repeat(2,1fr); }
    .stat-cell:nth-child(2) { border-right: none; }
    .stat-cell:nth-child(3) { border-right: 1px solid var(--border); }
    .meta-row { gap: 20px; }
    footer { flex-direction: column; gap: 8px; }
  }
</style>
</head>
<body>

<!-- ══ HERO ══ -->
<header class="hero">
  <div class="badge">Intelligence Report · v1.0</div>
  <h1>Netflix <span>Intelligence</span><br>& Audience<br>Segmentation<br>Matrix</h1>
  <p class="hero-sub">A multi-dimensional analysis of catalog composition, content quality, demographic reach, and genre distribution across a global streaming ecosystem.</p>
  <div class="meta-row">
    <div class="meta-item"><span class="meta-label">Domain</span><span class="meta-value">Streaming / OTT Analytics</span></div>
    <div class="meta-item"><span class="meta-label">Scope</span><span class="meta-value">Global Catalog · 2000–2023</span></div>
    <div class="meta-item"><span class="meta-label">Panels</span><span class="meta-value">6 Analytical Modules</span></div>
    <div class="meta-item"><span class="meta-label">Rating Source</span><span class="meta-value">IMDb</span></div>
  </div>
</header>

<main>

<!-- ══ 01 OVERVIEW ══ -->
<div class="container">
  <section>
    <div class="section-eyebrow">01 — Overview</div>
    <h2>What Is This Dashboard?</h2>
    <p>This dashboard delivers a structured intelligence view of a major streaming platform's content catalog. Six analytical panels surface how content is distributed across format, runtime, quality rating, demographic classification, and genre — translating raw catalog data into a coherent strategic picture.</p>
    <p>The goal is to reveal structural patterns: where quality clusters, how the catalog has scaled over time, which rating categories dominate, and where genre volume concentrates.</p>
    <div class="stat-strip">
      <div class="stat-cell"><div class="stat-number">6<span class="stat-unit">panels</span></div><div class="stat-label">Analytical Modules</div></div>
      <div class="stat-cell"><div class="stat-number">64<span class="stat-unit">%</span></div><div class="stat-label">Movies in Catalog</div></div>
      <div class="stat-cell"><div class="stat-number">2914</div><div class="stat-label">Unrated / Unknown Titles</div></div>
      <div class="stat-cell"><div class="stat-number">~6.5</div><div class="stat-label">Avg IMDb Score (Recent)</div></div>
    </div>
  </section>
</div>

<!-- ══ 02 PANELS ══ -->
<div class="container">
  <section>
    <div class="section-eyebrow">02 — Dashboard Panels</div>
    <h2>Six-Module Breakdown</h2>
    <p>Each panel isolates a distinct dimension of catalog intelligence. Together they form a complete picture of content strategy.</p>
    <div class="panels">
      <div class="panel">
        <div class="panel-num">I</div>
        <div class="panel-title">Content Volume · Quality · Runtime Density</div>
        <div class="panel-desc">A hexbin density map plotting IMDb score against runtime (minutes). High-density zones at 80–120 min runtimes correspond to strong ratings, suggesting a structural runtime sweet spot for audience satisfaction.</div>
      </div>
      <div class="panel">
        <div class="panel-num">II</div>
        <div class="panel-title">Portfolio Mix · Global Libraries</div>
        <div class="panel-desc">Donut chart showing the format split: <strong style="color:#fff">64% Movies</strong> vs <strong style="color:#fff">36% Shows</strong>. The heavier movie weighting reflects the catalog's roots as a film distributor before episodic originals scaled.</div>
      </div>
      <div class="panel">
        <div class="panel-num">III</div>
        <div class="panel-title">Production Volume Scale Trajectory</div>
        <div class="panel-desc">Area chart of titles released per year 2000–2023. Exponential growth from ~2010 peaks at ~700+ titles/year around 2019–2020, followed by a measured contraction consistent with post-pandemic recalibration.</div>
      </div>
      <div class="panel">
        <div class="panel-num">IV</div>
        <div class="panel-title">Maturity Classification & Reach Profile</div>
        <div class="panel-desc">Bar chart across 8 rating categories. "Unrated" dominates at 2,914 titles; TV-MA leads among classified content at 810. Content skews heavily mature, reflecting the primary adult demographic.</div>
      </div>
      <div class="panel">
        <div class="panel-num">V</div>
        <div class="panel-title">Top 10 Demand Genres by Distribution Volume</div>
        <div class="panel-desc">Horizontal bar ranking genres by total volume. Drama leads (~2,500+ titles), followed by Comedy and Thriller. A clear power-law pattern — top 3 genres hold a commanding share while remaining genres fill niche demand roles.</div>
      </div>
      <div class="panel">
        <div class="panel-num">VI</div>
        <div class="panel-title">Annual Quality Trend Variation (IMDb)</div>
        <div class="panel-desc">Dual-layer chart tracking average IMDb score vs catalog historic mean (~6.6). Scores held ~6.8–7.0 from 2001–2018 before drifting toward ~6.5 in recent years, correlating with peak volume output periods.</div>
      </div>
    </div>
  </section>
</div>

<!-- ══ 03 KEY INSIGHTS ══ -->
<div class="container">
  <section>
    <div class="section-eyebrow">03 — Key Insights</div>
    <h2>Derived Business Signals</h2>
    <ul class="insights">
      <li>
        <div class="insight-icon">◈</div>
        <div>
          <span class="insight-strong">Dual-Format Consumption Architecture</span>
          The 64/36 movie-to-show split enables the platform to serve both passive lean-back viewing (films) and habitual episodic engagement (series) — two fundamentally different consumption behaviors within a single product.
        </div>
      </li>
      <li>
        <div class="insight-icon">◈</div>
        <div>
          <span class="insight-strong">Runtime–Quality Clustering</span>
          The hexbin map reveals a non-random relationship between content length and audience rating. The 80–120 minute band corresponds to the highest-density, highest-rated clusters — a structural signal with direct implications for acquisition and greenlighting decisions.
        </div>
      </li>
      <li>
        <div class="insight-icon">◈</div>
        <div>
          <span class="insight-strong">Mature Demographic Concentration</span>
          TV-MA and R-rated content collectively dominate the classified catalog. The platform's audience skews adult, and the investment strategy reflects this — adult drama, thriller, and mature comedy occupy the top genre slots.
        </div>
      </li>
      <li>
        <div class="insight-icon">◈</div>
        <div>
          <span class="insight-strong">Genre Power-Law Distribution</span>
          Drama alone accounts for a disproportionate share of catalog volume. The top 3 genres (Drama, Comedy, Thriller) form a dominant core, while 7 additional genres serve as supporting catalog depth — a classic long-tail structure.
        </div>
      </li>
      <li>
        <div class="insight-icon">◈</div>
        <div>
          <span class="insight-strong">Volume–Quality Trade-Off Signal</span>
          The post-2018 IMDb score drift coincides with peak catalog expansion — suggesting diminishing average quality returns during hypergrowth phases, a known risk in content-volume scaling strategies.
        </div>
      </li>
    </ul>
  </section>
</div>

<!-- ══ 04 STRATEGIC CATALOG INSIGHTS ══ -->
<div class="container">
  <section>
    <div class="section-eyebrow">04 — Strategic Catalog Insights</div>
    <h2>Portfolio Observations</h2>

    <h3>🎞️ The Core Library Split</h3>
    <p>The catalog maintains a highly intentional distribution matrix, balancing quick-turnaround episodic series with high-impact feature films across its global content ecosystem. This dual-structure approach is designed not only to diversify audience touchpoints but also to stabilize long-term engagement cycles across different viewing behaviors.</p>
    <p>Episodic content serves as the primary retention engine — ensuring frequent user return and sustained watch-time continuity — while feature films act as high-impact acquisition and branding assets that elevate perceived platform value. Together, this structured imbalance creates a healthy content economy supporting both short-form engagement loops and long-form consumption depth.</p>

    <h3>⭐ The Audience Quality Sweet Spot</h3>
    <p>Runtime distribution analysis reveals a clearly defined performance concentration zone where the highest-rated content consistently clusters. Within this optimal runtime band, titles demonstrate stronger audience retention, higher completion rates, and improved IMDb scoring stability.</p>
    <p>Content falling below this threshold often lacks sufficient narrative depth to sustain engagement, while overly extended runtimes introduce fatigue-related drop-offs and increased rating variability — suggesting audience satisfaction is strongly correlated with structural pacing efficiency, not just storytelling quality.</p>

    <h3>👥 The Mature Demographic Driver</h3>
    <p>Maturity-rating segmentation indicates that adult and young-adult audiences form the foundational consumption base of the catalog. These segments account for the largest volume of available titles and represent the most reliable drivers of consistent global engagement.</p>
    <p>This demographic dominance is structural, not incidental — reflecting long-term viewing behavior patterns where mature content generates higher retention, stronger emotional investment, and repeat consumption cycles. These segments remain central to both acquisition strategy and original production planning.</p>

    <h3>🎭 Genre Penetration & Market Dominance</h3>
    <p>Genre distribution exhibits a layered hierarchy that defines both stability and growth potential. Core genres function as the baseline demand engine, ensuring consistent and predictable viewership across time. Niche and secondary genres operate as exploratory vectors, capturing fragmented audience interests and enabling platform differentiation.</p>
    <p>This dual-layer genre architecture allows the catalog to maintain both mass appeal and specialized depth, ensuring resilience in an increasingly competitive streaming landscape.</p>
  </section>
</div>

<!-- ══ 05 BUSINESS IMPACT ══ -->
<div class="container">
  <section>
    <div class="section-eyebrow">05 — Business Impact</div>
    <h2>Derived From Observed Patterns</h2>
    <p>The observed catalog structure highlights several measurable characteristics of the content ecosystem:</p>
    <ul class="impact-list">
      <li><div class="impact-dot"></div><div>A <strong style="color:#fff">dual-format system</strong> (episodic vs feature films) that supports multiple consumption behaviors across divergent audience segments.</div></li>
      <li><div class="impact-dot"></div><div>A <strong style="color:#fff">defined runtime-performance clustering pattern</strong> linked with higher audience ratings and improved engagement outcomes.</div></li>
      <li><div class="impact-dot"></div><div>A <strong style="color:#fff">strong concentration of content in mature demographic categories</strong>, reflecting structural audience composition and long-term viewing behavior patterns.</div></li>
      <li><div class="impact-dot"></div><div>A <strong style="color:#fff">genre distribution hierarchy</strong> with a few dominant categories and a wider set of supporting niches — enabling both mass appeal and catalog depth.</div></li>
    </ul>
    <p style="margin-top: 24px;">Together, these patterns provide a structured view of how content is distributed and how different attributes — format, runtime, rating category, genre — collectively shape the catalog's overall composition and engagement profile.</p>
    <p>This analysis transforms raw catalog composition into structured strategic intelligence, enabling more precise decision-making across content development, acquisition strategy, audience segmentation, and long-term portfolio planning. By aligning runtime efficiency, demographic targeting, and genre optimization, the catalog strengthens its ability to scale sustainably while maintaining high engagement quality across a diverse global audience 🌍.</p>
  </section>
</div>

<!-- ══ 07 SUMMARY ══ -->
<div class="container">
  <section>
    <div class="section-eyebrow">06 — Summary</div>
    <h2>Project Synopsis</h2>
    <div class="summary-box">
      <p>This analysis provides a structured overview of catalog composition across format, runtime, demographic segmentation, and genre distribution. It focuses on identifying observable structural patterns within the dataset and translating them into a coherent view of content organization within a global streaming ecosystem 🌍.</p>
      <p>The result is a more predictive, efficient, and strategically aligned content intelligence framework — one that supports both immediate performance gains and long-term platform resilience. The six-panel matrix collectively demonstrates how data-driven catalog visibility can inform every layer of a streaming platform's strategic decision-making.</p>
    </div>
  </section>
</div>

<!-- ══ 08 STACK ══ -->
<div class="container">
  <section>
    <div class="section-eyebrow">07 — Stack & Methods</div>
    <h2>Tools & Techniques</h2>
    <p>This analysis combines statistical visualization with catalog metadata enrichment. The following tools and methods were used across data preparation, analysis, and visualization stages.</p>
    <div class="tech-grid">
      <span class="tech-tag red">Python</span>
      <span class="tech-tag red">Pandas</span>
      <span class="tech-tag red">Matplotlib</span>
      <span class="tech-tag red">Seaborn</span>
      <span class="tech-tag">IMDb Dataset</span>
      <span class="tech-tag">Netflix Catalog Metadata</span>
      <span class="tech-tag">Hexbin Density Mapping</span>
      <span class="tech-tag">Time-Series Analysis</span>
      <span class="tech-tag">Maturity Rating Taxonomy</span>
      <span class="tech-tag">Genre Frequency Distribution</span>
    </div>
  </section>
</div>

<!-- ══ 09 USAGE ══ -->
<div class="container">
  <section>
    <div class="section-eyebrow">08 — Usage</div>
    <h2>Who Is This For?</h2>
    <p>This dashboard is designed for analysts, product strategists, and researchers interested in streaming catalog intelligence. Potential use cases include:</p>
    <ul class="insights">
      <li>
        <div class="insight-icon">→</div>
        <div><span class="insight-strong">Content Strategy Teams</span>Informing acquisition, greenlighting, and portfolio balancing decisions based on quality–volume trade-offs and genre distribution data.</div>
      </li>
      <li>
        <div class="insight-icon">→</div>
        <div><span class="insight-strong">Data Analysts & Scientists</span>A reference dataset and visualization framework for exploring catalog composition patterns in OTT platforms.</div>
      </li>
      <li>
        <div class="insight-icon">→</div>
        <div><span class="insight-strong">Academic & Industry Research</span>Benchmark analysis of how a global streaming library is structured across format, rating, runtime, and genre dimensions.</div>
      </li>
    </ul>
  </section>
</div>

</main>

<footer>
  <div class="footer-brand">NETFLIX · INTELLIGENCE MATRIX</div>
  <div class="footer-note">Analytical Dashboard — 6 Panels · IMDb-Rated · Global Catalog · v1.0</div>
</footer>

</body>
</html>
