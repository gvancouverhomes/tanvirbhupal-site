---
layout: null
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tanvir Bhupal | Strategic Real Estate Advisory</title>
    <style>
        :root {
            --bg: #fdfcf9; --text: #333; --dark: #1a1a1a; --soft: #666; --spacing: 80px;
        }
        body {
            background: var(--bg); color: var(--text); font-family: "Georgia", serif;
            line-height: 1.8; margin: 0; padding: 0; -webkit-font-smoothing: antialiased;
        }
        .hero-split { display: flex; min-height: 90vh; align-items: center; flex-wrap: wrap; }
        .hero-text { width: 50%; padding: 0 10%; box-sizing: border-box; }
        .hero-text h1 { font-size: 2.8rem; font-weight: normal; line-height: 1.2; color: var(--dark); margin-bottom: 30px; }
        .hero-image { width: 50%; height: 90vh; background: url('/hero.png') center/cover no-repeat; filter: grayscale(15%) contrast(1.05); }
        .section-pad { padding: var(--spacing) 10%; }
        .grid-3 { display: grid; grid-template-columns: repeat(3, 1fr); gap: 50px; }
        .pillar h3 { font-size: 1.1rem; text-transform: uppercase; letter-spacing: 2px; border-bottom: 1px solid var(--text); padding-bottom: 15px; margin-bottom: 20px; }
        .portfolio-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 15px; margin-top: 40px; }
        .enclave-card { padding: 30px; border: 1px solid rgba(0,0,0,0.1); text-align: center; text-decoration: none; color: var(--text); transition: 0.3s; font-size: 0.8rem; letter-spacing: 1.5px; }
        .enclave-card:hover { background: #fff; border-color: var(--dark); }
        .calendar-item { border-left: 2px solid #ddd; padding-left: 25px; margin-bottom: 40px; }
        .calendar-tag { font-size: 0.7rem; text-transform: uppercase; color: #999; letter-spacing: 1px; }
        footer { padding: 60px 10%; border-top: 1px solid #eee; background: #fff; font-size: 0.8rem; }
        @media (max-width: 900px) { 
            .hero-split { flex-direction: column; } 
            .hero-text, .hero-image { width: 100%; height: auto; padding: 60px 20px; } 
            .hero-image { height: 400px; }
            .grid-3 { grid-template-columns: 1fr; } 
        }
    </style>
</head>
<body>

<section class="hero-split">
  <div class="hero-text">
    <h1>Your move is a logistical undertaking. I make it a strategic one.</h1>
    <p>Private relocation and real estate advisory for families moving with intention. Every decision is filtered for risk, lifestyle fit, and long-term value before a single offer is written.</p>
    <a href="#calendar" style="text-decoration: underline; color: #1a1a1a; font-weight: bold; font-size: 0.8rem; letter-spacing: 1px;">VIEW THE INTELLIGENCE CALENDAR</a>
  </div>
  <div class="hero-image"></div>
</section>

<section class="section-pad">
  <div class="grid-3">
    <div class="pillar">
      <h3>Clarity</h3>
      <p>Locations, properties, and numbers are filtered until only the most viable fiduciary paths remain. You don’t see everything; you see what matters.</p>
    </div>
    <div class="pillar">
      <h3>Privacy</h3>
      <p>Discreet searches, controlled exposure, and quiet negotiations. Your intentions stay private until action is intentional.</p>
    </div>
    <div class="pillar">
      <h3>Legacy</h3>
      <p>Decisions are anchored in land utility, school trajectory, and resale protection—focused on the next decade, not the next showing.</p>
    </div>
  </div>
</section>

<section class="section-pad" style="background: #f8f7f2;">
  <div style="max-width: 1000px; margin: 0 auto;">
    <h2 style="font-weight: normal; margin-bottom: 40px; text-align: center;">The Neighborhood Portfolio</h2>
    <div class="portfolio-grid">
      <div class="enclave-card">ELGIN CHANTRELL</div>
      <div class="enclave-card">OCEAN PARK</div>
      <div class="enclave-card">MORGAN CREEK</div>
      <div class="enclave-card">PANORAMA RIDGE</div>
      <div class="enclave-card">FRASER HEIGHTS</div>
    </div>
  </div>
</section>

<section id="calendar" class="section-pad">
  <h2 style="font-weight: normal; margin-bottom: 50px;">The 2026 Intelligence Calendar</h2>
  <div class="calendar-item">
    <span class="calendar-tag">Feb 2026 • Video Briefing</span>
    <h4 style="margin: 5px 0;">The Elgin Chantrell Land Shift: Decoupling Equity from Structure</h4>
  </div>
  <div class="calendar-item">
    <span class="calendar-tag">March 2026 • Podcast Episode 01</span>
    <h4 style="margin: 5px 0;">The Privacy Protocol: Managing a $3M+ Transition Discreetly</h4>
  </div>
  <div class="calendar-item">
    <span class="calendar-tag">April 2026 • Strategic Analysis</span>
    <h4 style="margin: 5px 0;">The Relocation Friction Map: Commute vs. Community in Ocean Park</h4>
  </div>
</section>

<footer>
  <div style="display: flex; justify-content: space-between; flex-wrap: wrap; gap: 30px;">
    <div>
      <p><strong>© 2026 Tanvir Bhupal. Real Estate Advisor.</strong></p>
      <p>eXp Realty – 701 W Georgia St #1500, Vancouver, BC V7Y 1G5</p>
      <p>604-897-7826</p>
    </div>
    <div style="color: #888; text-align: right;">
      <p>This website is not intended to solicit buyers or sellers currently under contract.</p>
      <p>All information is deemed reliable but not guaranteed.</p>
      <p style="margin-top: 15px; letter-spacing: 2px;">LINKEDIN // INSTAGRAM // SPOTIFY // GOOGLE</p>
    </div>
  </div>
</footer>

</body>
</html>
