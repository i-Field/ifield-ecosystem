<!DOCTYPE html> 
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>X-Field // iField Ecosystem</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&family=Syne:wght@400;700;800&display=swap');

  :root {
    --void: #020408;
    --deep: #060d14;
    --panel: #0a1520;
    --border: rgba(0,200,255,0.12);
    --cyan: #00c8ff;
    --bio: #00ff9d;
    --warn: #ff6b35;
    --dim: rgba(255,255,255,0.35);
    --text: rgba(255,255,255,0.85);
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    background: var(--void);
    color: var(--text);
    font-family: 'Space Mono', monospace;
    overflow-x: hidden;
    min-height: 100vh;
  }

  /* NOISE OVERLAY */
  body::before {
    content: '';
    position: fixed; inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E");
    pointer-events: none; z-index: 9999; opacity: 0.5;
  }

  /* HEADER */
  header {
    display: flex; align-items: center; justify-content: space-between;
    padding: 24px 40px;
    border-bottom: 1px solid var(--border);
    position: sticky; top: 0; z-index: 100;
    background: rgba(2,4,8,0.9);
    backdrop-filter: blur(20px);
  }

  .logo {
    font-family: 'Syne', sans-serif;
    font-weight: 800; font-size: 20px;
    letter-spacing: -0.5px;
  }
  .logo span { color: var(--cyan); }

  .status-pill {
    display: flex; align-items: center; gap: 8px;
    font-size: 11px; color: var(--bio);
    border: 1px solid rgba(0,255,157,0.25);
    padding: 6px 14px; border-radius: 20px;
  }
  .pulse-dot {
    width: 6px; height: 6px; border-radius: 50%;
    background: var(--bio);
    animation: pulse 1.5s ease-in-out infinite;
  }
  @keyframes pulse {
    0%,100% { opacity: 1; transform: scale(1); }
    50% { opacity: 0.4; transform: scale(0.7); }
  }

  /* HERO */
  .hero {
    display: grid;
    grid-template-columns: 1fr 420px;
    gap: 60px;
    padding: 80px 40px 60px;
    max-width: 1200px; margin: 0 auto;
    align-items: center;
  }

  .hero-label {
    font-size: 11px; letter-spacing: 4px;
    color: var(--cyan); margin-bottom: 20px;
    text-transform: uppercase;
  }

  h1 {
    font-family: 'Syne', sans-serif;
    font-size: clamp(42px, 6vw, 80px);
    font-weight: 800; line-height: 0.95;
    letter-spacing: -3px;
    margin-bottom: 24px;
  }

  h1 .accent { color: var(--cyan); }
  h1 .bio-accent { color: var(--bio); }

  .hero-desc {
    font-size: 13px; line-height: 1.8;
    color: var(--dim); max-width: 420px;
    margin-bottom: 40px;
  }

  .hero-tags {
    display: flex; flex-wrap: wrap; gap: 8px;
  }
  .tag {
    font-size: 10px; letter-spacing: 2px;
    padding: 5px 12px; border-radius: 3px;
    border: 1px solid var(--border);
    color: var(--dim); text-transform: uppercase;
  }
  .tag.active { border-color: var(--cyan); color: var(--cyan); }

  /* BODY SCANNER */
  .scanner-wrap {
    position: relative;
    display: flex; align-items: center; justify-content: center;
  }

  .body-svg-container {
    position: relative;
    width: 220px; height: 380px;
  }

  .scan-line {
    position: absolute; left: 0; right: 0;
    height: 2px;
    background: linear-gradient(90deg, transparent, var(--cyan), transparent);
    top: 0;
    animation: scanBody 3s ease-in-out infinite;
    box-shadow: 0 0 12px var(--cyan);
  }
  @keyframes scanBody {
    0% { top: 0; opacity: 0; }
    10% { opacity: 1; }
    90% { opacity: 1; }
    100% { top: 100%; opacity: 0; }
  }

  .body-svg { width: 100%; height: 100%; }

  /* Data points */
  .data-point {
    position: absolute;
    width: 8px; height: 8px;
    border-radius: 50%;
    cursor: pointer;
    transition: all 0.3s;
  }
  .data-point::before {
    content: '';
    position: absolute; inset: -4px;
    border-radius: 50%;
    border: 1px solid currentColor;
    animation: ring 2s ease-in-out infinite;
    opacity: 0;
  }
  @keyframes ring {
    0% { transform: scale(0.8); opacity: 0.8; }
    100% { transform: scale(2); opacity: 0; }
  }
  .data-point:hover { transform: scale(1.5); }

  .dp-heart { background: var(--bio); color: var(--bio); top: 38%; left: 28%; }
  .dp-brain { background: var(--cyan); color: var(--cyan); top: 8%; left: 40%; }
  .dp-lung { background: #9d6fff; color: #9d6fff; top: 34%; left: 62%; }
  .dp-gut { background: var(--warn); color: var(--warn); top: 52%; left: 45%; }
  .dp-hrv  { background: var(--bio); color: var(--bio); top: 44%; left: 30%; }

  .dp-label {
    position: absolute;
    font-size: 9px; letter-spacing: 1px;
    white-space: nowrap;
    pointer-events: none;
  }
  .dp-label-left { right: calc(100% + 12px); text-align: right; top: -2px; }
  .dp-label-right { left: calc(100% + 12px); top: -2px; }

  /* METRICS GRID */
  .metrics-section {
    padding: 0 40px 60px;
    max-width: 1200px; margin: 0 auto;
  }

  .section-header {
    display: flex; align-items: center; gap: 16px;
    margin-bottom: 28px;
  }
  .section-line { flex: 1; height: 1px; background: var(--border); }
  .section-title {
    font-size: 10px; letter-spacing: 3px;
    color: var(--dim); text-transform: uppercase;
  }

  .metrics-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 12px;
    margin-bottom: 12px;
  }

  .metric-card {
    background: var(--panel);
    border: 1px solid var(--border);
    border-radius: 6px;
    padding: 20px;
    cursor: pointer;
    transition: all 0.3s;
    position: relative; overflow: hidden;
  }
  .metric-card::before {
    content: '';
    position: absolute; bottom: 0; left: 0; right: 0;
    height: 2px;
    background: var(--accent-color, var(--cyan));
    transform: scaleX(0);
    transition: transform 0.3s;
    transform-origin: left;
  }
  .metric-card:hover::before { transform: scaleX(1); }
  .metric-card:hover { border-color: rgba(0,200,255,0.3); transform: translateY(-2px); }

  .metric-label {
    font-size: 9px; letter-spacing: 2px;
    color: var(--dim); text-transform: uppercase;
    margin-bottom: 12px;
  }

  .metric-value {
    font-family: 'Syne', sans-serif;
    font-size: 32px; font-weight: 800;
    letter-spacing: -1px;
    line-height: 1;
    margin-bottom: 4px;
  }

  .metric-unit {
    font-size: 10px; color: var(--dim);
    margin-bottom: 14px;
  }

  .mini-bar {
    height: 3px;
    background: rgba(255,255,255,0.08);
    border-radius: 2px; overflow: hidden;
  }
  .mini-bar-fill {
    height: 100%; border-radius: 2px;
    background: var(--accent-color, var(--cyan));
    transition: width 1.5s cubic-bezier(0.16, 1, 0.3, 1);
  }

  .metric-trend {
    font-size: 9px; margin-top: 8px;
    display: flex; align-items: center; gap: 4px;
  }
  .trend-up { color: var(--bio); }
  .trend-down { color: var(--warn); }
  .trend-stable { color: var(--dim); }

  /* BIOFILED WAVE */
  .biofield-section {
    padding: 0 40px 60px;
    max-width: 1200px; margin: 0 auto;
  }

  .wave-container {
    background: var(--panel);
    border: 1px solid var(--border);
    border-radius: 6px;
    padding: 30px;
    position: relative; overflow: hidden;
  }

  .wave-header {
    display: flex; justify-content: space-between; align-items: center;
    margin-bottom: 24px;
  }
  .wave-title {
    font-family: 'Syne', sans-serif;
    font-weight: 700; font-size: 16px;
  }
  .wave-badge {
    font-size: 9px; letter-spacing: 2px;
    color: var(--bio); border: 1px solid rgba(0,255,157,0.3);
    padding: 4px 10px; border-radius: 2px;
  }

  canvas#waveCanvas {
    width: 100%; height: 120px; display: block;
  }

  .wave-labels {
    display: flex; justify-content: space-between;
    margin-top: 12px;
    font-size: 9px; color: var(--dim); letter-spacing: 1px;
  }

  /* MODULES */
  .modules-section {
    padding: 0 40px 80px;
    max-width: 1200px; margin: 0 auto;
  }

  .modules-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 12px;
  }

  .module-card {
    background: var(--panel);
    border: 1px solid var(--border);
    border-radius: 6px;
    padding: 28px;
    transition: all 0.3s;
    cursor: default;
    position: relative; overflow: hidden;
  }

  .module-card::after {
    content: '';
    position: absolute; top: 0; left: 0; right: 0;
    height: 1px;
    background: linear-gradient(90deg, transparent, var(--m-color, var(--cyan)), transparent);
    opacity: 0;
    transition: opacity 0.3s;
  }
  .module-card:hover::after { opacity: 1; }
  .module-card:hover { transform: translateY(-3px); border-color: rgba(0,200,255,0.2); }

  .module-icon {
    width: 40px; height: 40px;
    border-radius: 8px;
    display: flex; align-items: center; justify-content: center;
    font-size: 18px;
    margin-bottom: 16px;
    background: rgba(0,200,255,0.08);
  }

  .module-name {
    font-family: 'Syne', sans-serif;
    font-weight: 700; font-size: 14px;
    margin-bottom: 8px;
  }

  .module-desc {
    font-size: 11px; line-height: 1.7;
    color: var(--dim);
  }

  .module-status {
    margin-top: 16px;
    font-size: 9px; letter-spacing: 2px;
    text-transform: uppercase;
  }

  /* BOTTOM CTA */
  .cta-section {
    text-align: center;
    padding: 0 40px 80px;
    max-width: 600px; margin: 0 auto;
  }

  .cta-text {
    font-size: 11px; color: var(--dim);
    letter-spacing: 1px; margin-bottom: 8px;
  }

  .cta-big {
    font-family: 'Syne', sans-serif;
    font-size: 28px; font-weight: 800;
    letter-spacing: -1px; margin-bottom: 24px;
  }

  .btn-primary {
    display: inline-block;
    padding: 14px 36px;
    background: var(--cyan);
    color: var(--void);
    font-family: 'Space Mono', monospace;
    font-size: 11px; letter-spacing: 2px;
    font-weight: 700; text-transform: uppercase;
    border: none; border-radius: 3px;
    cursor: pointer;
    transition: all 0.3s;
    text-decoration: none;
  }
  .btn-primary:hover {
    background: var(--bio);
    transform: translateY(-2px);
    box-shadow: 0 8px 24px rgba(0,200,255,0.3);
  }

  /* TOOLTIP */
  .tooltip {
    position: fixed;
    background: var(--deep);
    border: 1px solid var(--border);
    border-radius: 4px;
    padding: 10px 14px;
    font-size: 10px; line-height: 1.6;
    max-width: 180px;
    pointer-events: none;
    z-index: 1000;
    opacity: 0; transition: opacity 0.2s;
  }
  .tooltip.visible { opacity: 1; }
  .tooltip-title { color: var(--cyan); font-weight: 700; margin-bottom: 4px; }

  @media (max-width: 768px) {
    .hero { grid-template-columns: 1fr; padding: 40px 20px; }
    .scanner-wrap { display: none; }
    .metrics-grid { grid-template-columns: repeat(2, 1fr); }
    .modules-grid { grid-template-columns: 1fr; }
    header { padding: 16px 20px; }
    .metrics-section, .biofield-section, .modules-section { padding-left: 20px; padding-right: 20px; }
  }
</style>
</head>
<body>

<div class="tooltip" id="tooltip">
  <div class="tooltip-title" id="tt-title"></div>
  <div id="tt-body"></div>
</div>

<header>
  <div class="logo">i<span>Field</span> <span style="color:var(--dim);font-weight:400">// X-FIELD</span></div>
  <div class="status-pill"><div class="pulse-dot"></div> SCANNING ACTIVE</div>
</header>

<!-- HERO -->
<section class="hero">
  <div>
    <div class="hero-label">// Concept v0.1 — iField Ecosystem</div>
    <h1>
      DECODE<br>YOUR <span class="accent">BIO</span><br><span class="bio-accent">FIELD</span>
    </h1>
    <p class="hero-desc">
      Non-invasive multi-sensor module for iPhone. Reads energetic and physiological markers through light, micro-vibrations, and thermal fields. No blood. No pain. No labs.
    </p>
    <div class="hero-tags">
      <span class="tag active">LiDAR</span>
      <span class="tag active">Infrared</span>
      <span class="tag active">Spectral</span>
      <span class="tag">EM Sensors</span>
      <span class="tag">Air Quality</span>
      <span class="tag active">AI Core</span>
    </div>
  </div>

  <!-- BODY SCANNER VIZ -->
  <div class="scanner-wrap">
    <div class="body-svg-container">
      <div class="scan-line"></div>
      <svg class="body-svg" viewBox="0 0 200 380" fill="none" xmlns="http://www.w3.org/2000/svg">
        <!-- Body outline -->
        <path d="M100 20 C115 20 128 30 130 45 C132 55 128 65 125 70 L130 100 C145 105 160 118 162 135 L165 200 L155 205 L152 260 L148 340 L140 345 L138 280 L130 280 L128 345 L120 345 L115 265 L100 260 L85 265 L80 345 L72 345 L70 280 L62 280 L60 265 L55 205 L45 200 L48 135 C50 118 65 105 80 100 L85 70 C82 65 78 55 80 45 C82 30 85 20 100 20Z"
          stroke="rgba(0,200,255,0.2)" stroke-width="1.5" fill="rgba(0,200,255,0.03)"/>
        <!-- Spine -->
        <line x1="100" y1="70" x2="100" y2="260" stroke="rgba(0,200,255,0.08)" stroke-width="1" stroke-dasharray="4,6"/>
        <!-- Ribs suggestion -->
        <path d="M80 130 Q100 125 120 130" stroke="rgba(0,200,255,0.1)" stroke-width="1" fill="none"/>
        <path d="M78 145 Q100 140 122 145" stroke="rgba(0,200,255,0.1)" stroke-width="1" fill="none"/>
        <path d="M77 160 Q100 155 123 160" stroke="rgba(0,200,255,0.1)" stroke-width="1" fill="none"/>
        <!-- Energy aura -->
        <ellipse cx="100" cy="190" rx="90" ry="170" stroke="rgba(0,200,255,0.05)" stroke-width="1" stroke-dasharray="3,8" fill="none">
          <animateTransform attributeName="transform" type="scale" values="1;1.02;1" dur="4s" repeatCount="indefinite" additive="sum"/>
        </ellipse>
        <ellipse cx="100" cy="190" rx="102" ry="182" stroke="rgba(0,255,157,0.04)" stroke-width="1" stroke-dasharray="2,12" fill="none">
          <animateTransform attributeName="transform" type="scale" values="1.01;1;1.01" dur="5s" repeatCount="indefinite" additive="sum"/>
        </ellipse>
      </svg>

      <!-- DATA POINTS -->
      <div class="data-point dp-brain"
        data-title="Neural Field" data-body="Alpha/Beta wave coherence: 87% | Cognitive load: Low">
        <span class="dp-label dp-label-right" style="color:var(--cyan)">NEURAL</span>
      </div>
      <div class="data-point dp-heart"
        data-title="Cardiac Field" data-body="HRV: 68ms | BPM: 62 | Coherence: High">
        <span class="dp-label dp-label-left" style="color:var(--bio)">HRV ↑</span>
      </div>
      <div class="data-point dp-hrv"
        data-title="Resonance Zone" data-body="Heart-brain sync: 0.1Hz | Field intensity: +12%">
        <span class="dp-label dp-label-left" style="color:var(--bio)">SYNC</span>
      </div>
      <div class="data-point dp-lung"
        data-title="Pulmonary Field" data-body="SpO2: 98% | Breath rate: 14/min">
        <span class="dp-label dp-label-right" style="color:#9d6fff">O₂ 98%</span>
      </div>
      <div class="data-point dp-gut"
        data-title="Gut Microbiome Marker" data-body="Inflammation index: 0.3 | Motility: Normal">
        <span class="dp-label dp-label-right" style="color:var(--warn)">GUT</span>
      </div>
    </div>
  </div>
</section>

<!-- METRICS -->
<section class="metrics-section">
  <div class="section-header">
    <div class="section-line"></div>
    <div class="section-title">Live Bio-Metrics</div>
    <div class="section-line"></div>
  </div>

  <div class="metrics-grid">
    <div class="metric-card" style="--accent-color: var(--bio)">
      <div class="metric-label">Heart Rate Variability</div>
      <div class="metric-value" style="color:var(--bio)" id="hrv-val">68</div>
      <div class="metric-unit">ms RMSSD</div>
      <div class="mini-bar"><div class="mini-bar-fill" style="--accent-color:var(--bio);width:72%"></div></div>
      <div class="metric-trend trend-up">↑ +8ms from baseline</div>
    </div>

    <div class="metric-card" style="--accent-color: var(--cyan)">
      <div class="metric-label">Neural Coherence</div>
      <div class="metric-value" style="color:var(--cyan)" id="nc-val">87</div>
      <div class="metric-unit">% alpha-theta sync</div>
      <div class="mini-bar"><div class="mini-bar-fill" style="width:87%"></div></div>
      <div class="metric-trend trend-up">↑ Focus state active</div>
    </div>

    <div class="metric-card" style="--accent-color: #9d6fff">
      <div class="metric-label">Stress Index</div>
      <div class="metric-value" style="color:#9d6fff" id="stress-val">18</div>
      <div class="metric-unit">/ 100 composite</div>
      <div class="mini-bar"><div class="mini-bar-fill" style="--accent-color:#9d6fff;width:18%"></div></div>
      <div class="metric-trend trend-up trend-stable">◆ Optimal zone</div>
    </div>

    <div class="metric-card" style="--accent-color: var(--warn)">
      <div class="metric-label">Inflammation Marker</div>
      <div class="metric-value" style="color:var(--warn)" id="infl-val">0.3</div>
      <div class="metric-unit">optical index</div>
      <div class="mini-bar"><div class="mini-bar-fill" style="--accent-color:var(--warn);width:15%"></div></div>
      <div class="metric-trend trend-up">↓ Below threshold</div>
    </div>
  </div>

  <div class="metrics-grid">
    <div class="metric-card" style="--accent-color: var(--bio)">
      <div class="metric-label">Oxygen Saturation</div>
      <div class="metric-value" style="color:var(--bio)">98<span style="font-size:14px">%</span></div>
      <div class="metric-unit">SpO2</div>
      <div class="mini-bar"><div class="mini-bar-fill" style="--accent-color:var(--bio);width:98%"></div></div>
      <div class="metric-trend trend-stable">◆ Nominal</div>
    </div>

    <div class="metric-card" style="--accent-color: var(--cyan)">
      <div class="metric-label">Biofield Intensity</div>
      <div class="metric-value" style="color:var(--cyan)">+12<span style="font-size:14px">%</span></div>
      <div class="metric-unit">vs 30-day avg</div>
      <div class="mini-bar"><div class="mini-bar-fill" style="width:62%"></div></div>
      <div class="metric-trend trend-up">↑ Expanding</div>
    </div>

    <div class="metric-card" style="--accent-color: #ffd700">
      <div class="metric-label">Recovery Score</div>
      <div class="metric-value" style="color:#ffd700">84</div>
      <div class="metric-unit">/ 100</div>
      <div class="mini-bar"><div class="mini-bar-fill" style="--accent-color:#ffd700;width:84%"></div></div>
      <div class="metric-trend trend-stable">◆ Ready</div>
    </div>

    <div class="metric-card" style="--accent-color: #ff6b9d">
      <div class="metric-label">Immune Resilience</div>
      <div class="metric-value" style="color:#ff6b9d">76</div>
      <div class="metric-unit">composite index</div>
      <div class="mini-bar"><div class="mini-bar-fill" style="--accent-color:#ff6b9d;width:76%"></div></div>
      <div class="metric-trend trend-up">↑ Strengthening</div>
    </div>
  </div>
</section>

<!-- BIOFIELD WAVE -->
<section class="biofield-section">
  <div class="section-header">
    <div class="section-line"></div>
    <div class="section-title">Biofield Wave Analysis</div>
    <div class="section-line"></div>
  </div>
  <div class="wave-container">
    <div class="wave-header">
      <div class="wave-title">Real-Time Energy Field Map</div>
      <div class="wave-badge">LIVE FEED</div>
    </div>
    <canvas id="waveCanvas"></canvas>
    <div class="wave-labels">
      <span>Delta 0.5–4Hz</span>
      <span>Theta 4–8Hz</span>
      <span>Alpha 8–13Hz</span>
      <span>Beta 13–30Hz</span>
      <span>Gamma 30Hz+</span>
    </div>
  </div>
</section>

<!-- MODULES -->
<section class="modules-section">
  <div class="section-header">
    <div class="section-line"></div>
    <div class="section-title">System Architecture</div>
    <div class="section-line"></div>
  </div>
  <div class="modules-grid">
    <div class="module-card" style="--m-color: var(--cyan)">
      <div class="module-icon">⬡</div>
      <div class="module-name">X-Field Module</div>
      <div class="module-desc">MagSafe hardware adapter. LiDAR + IR + spectral + EM sensors. Non-invasive continuous biometric capture.</div>
      <div class="module-status" style="color:var(--cyan)">// HARDWARE — Phase 2</div>
    </div>
    <div class="module-card" style="--m-color: var(--bio)">
      <div class="module-icon">◈</div>
      <div class="module-name">AI Core Engine</div>
      <div class="module-desc">On-device CoreML + cloud inference. Predictive analytics, anomaly detection, personalized recovery protocols.</div>
      <div class="module-status" style="color:var(--bio)">// SOFTWARE — Phase 1</div>
    </div>
    <div class="module-card" style="--m-color: #9d6fff">
      <div class="module-icon">◎</div>
      <div class="module-name">3D Body Map</div>
      <div class="module-desc">Interactive digital twin. Energy flows, immune markers, stress layers. Real-time AR overlay for iPhone.</div>
      <div class="module-status" style="color:#9d6fff">// UX — Phase 1</div>
    </div>
    <div class="module-card" style="--m-color: var(--warn)">
      <div class="module-icon">⬡</div>
      <div class="module-name">Self-Regulation</div>
      <div class="module-desc">Adaptive breathing protocols. Binaural audio, haptic feedback, photobiomodulation. Neuro-endocrine balance.</div>
      <div class="module-status" style="color:var(--warn)">// BIOFEEDBACK — Phase 1</div>
    </div>
    <div class="module-card" style="--m-color: #ffd700">
      <div class="module-icon">◈</div>
      <div class="module-name">iField Wallet & Token</div>
      <div class="module-desc">Health behavior rewards. Verifiable wellness credentials. NFT biofield profile — immutable health history.</div>
      <div class="module-status" style="color:#ffd700">// WEB3 — Phase 3</div>
    </div>
    <div class="module-card" style="--m-color: #ff6b9d">
      <div class="module-icon">◎</div>
      <div class="module-name">Bio-Aware Community</div>
      <div class="module-desc">Privacy-first social layer. Aggregate insights. Peer wisdom exchange. Zero manipulation, zero fear-selling.</div>
      <div class="module-status" style="color:#ff6b9d">// SOCIAL — Phase 3</div>
    </div>
  </div>
</section>

<!-- CTA -->
<section class="cta-section">
  <div class="cta-text">// CONCEPT STAGE — IFIELD ECOSYSTEM</div>
  <div class="cta-big">Built by Roman.<br>Powered by iField.</div>
  <a class="btn-primary" href="https://i-field.github.io/ifield-studio/" target="_blank">VIEW STUDIO →</a>
</section>

<script>
// LIVE METRICS ANIMATION
function animateVal(id, min, max, decimals=0, interval=3000) {
  setInterval(() => {
    const el = document.getElementById(id);
    if (!el) return;
    const v = (Math.random()*(max-min)+min).toFixed(decimals);
    el.textContent = v;
  }, interval);
}
animateVal('hrv-val', 58, 78);
animateVal('nc-val', 80, 94);
animateVal('stress-val', 12, 28);
animateVal('infl-val', 0.2, 0.5, 1, 4000);

// WAVE CANVAS
const canvas = document.getElementById('waveCanvas');
const ctx = canvas.getContext('2d');

function resizeCanvas() {
  canvas.width = canvas.offsetWidth * window.devicePixelRatio;
  canvas.height = canvas.offsetHeight * window.devicePixelRatio;
  ctx.scale(window.devicePixelRatio, window.devicePixelRatio);
}
resizeCanvas();
window.addEventListener('resize', resizeCanvas);

let t = 0;
const waves = [
  { freq: 0.5, amp: 15, color: '#9d6fff', speed: 0.008 },
  { freq: 1.2, amp: 22, color: '#00c8ff', speed: 0.015 },
  { freq: 2.1, amp: 14, color: '#00ff9d', speed: 0.022 },
  { freq: 3.5, amp: 8,  color: '#ffd700', speed: 0.035 },
  { freq: 6.0, amp: 5,  color: '#ff6b9d', speed: 0.055 },
];

function drawWaves() {
  const w = canvas.offsetWidth;
  const h = canvas.offsetHeight;
  ctx.clearRect(0, 0, w, h);

  ctx.fillStyle = 'rgba(6,13,20,0)';
  ctx.fillRect(0,0,w,h);

  waves.forEach((wave, i) => {
    ctx.beginPath();
    for (let x = 0; x <= w; x += 2) {
      const y = h/2 +
        Math.sin(x * wave.freq * 0.015 + t * wave.speed * 60) * wave.amp +
        Math.sin(x * wave.freq * 0.008 + t * wave.speed * 40 + i) * wave.amp * 0.5;
      x === 0 ? ctx.moveTo(x, y) : ctx.lineTo(x, y);
    }
    ctx.strokeStyle = wave.color;
    ctx.lineWidth = i === 1 ? 2 : 1;
    ctx.globalAlpha = i === 1 ? 0.8 : 0.4;
    ctx.stroke();
    ctx.globalAlpha = 1;

    // Glow for main wave
    if (i === 1) {
      ctx.shadowBlur = 12;
      ctx.shadowColor = wave.color;
      ctx.stroke();
      ctx.shadowBlur = 0;
    }
  });

  t++;
  requestAnimationFrame(drawWaves);
}
drawWaves();

// TOOLTIP
const tooltip = document.getElementById('tooltip');
const ttTitle = document.getElementById('tt-title');
const ttBody = document.getElementById('tt-body');

document.querySelectorAll('.data-point').forEach(dp => {
  dp.addEventListener('mouseenter', e => {
    ttTitle.textContent = dp.dataset.title;
    ttBody.textContent = dp.dataset.body;
    tooltip.classList.add('visible');
  });
  dp.addEventListener('mousemove', e => {
    tooltip.style.left = (e.clientX + 16) + 'px';
    tooltip.style.top = (e.clientY - 30) + 'px';
  });
  dp.addEventListener('mouseleave', () => tooltip.classList.remove('visible'));
});
</script>
</body>
</html>
