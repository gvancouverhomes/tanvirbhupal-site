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
        
        /* Navigation Bar */
        header {
            display: flex; justify-content: space-between; align-items: center;
            padding: 30px 10%; background: var(--bg); border-bottom: 1px solid rgba(0,0,0,0.05);
        }
        .logo { font-size: 1.1rem; letter-spacing: 3px; text-transform: uppercase; font-weight: bold; color: var(--dark); text-decoration: none; }
        nav a { text-decoration: none; color: var(--soft); margin-left: 30px; font-size: 0.75rem; text-transform: uppercase; letter-spacing: 2px; transition: 0.3s; }
        nav a:hover { color: var(--dark); border-bottom: 1px solid var(--dark); }

        /* Hero Section */
        .hero-split { display: flex; min-height: 85vh; align-items: center; flex-wrap: wrap; }
        .hero-text { width: 50%; padding: 0 10%; box-sizing: border-box; }
        .hero-text h1 { font-size: 3rem; font-weight: normal; line-height: 1.1; color: var(--dark); margin-bottom: 30px; }
        .hero-image { 
            width: 50%; height: 85vh; 
            /* THE FIX IS HERE: Pointing to your specific folder */
            background: url('./assets/images/hero.png') center/cover no-repeat; 
            filter: grayscale(10%) contrast(1.02); 
            background-color: #eee;
        }

        /* Pillars */
        .section-pad { padding: var(--spacing) 10%; }
        .grid-3 { display: grid; grid-template-columns: repeat(3, 1fr); gap: 60px; }
        .pillar h3 { font-size: 1rem; text-transform: uppercase; letter-spacing: 2px; border-bottom: 1px solid #ddd; padding-bottom: 15px; margin-bottom: 20px; color: var(--dark); }
        
        .portfolio-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px; margin-top: 40px; }
        .enclave-card { padding: 40px 20px; border: 1px solid rgba(0,0,0,0.1); text-align: center; text-decoration: none; color: var(--text); transition: 0.4s; font-size: 0.8rem; letter-spacing: 2px; }
        .enclave-card:hover { background: #fff; border-color: var(--dark); transform: translateY(-2px); }

        footer { padding: 80px 10%; border-top: 1px solid #eee; background: #fff; font-size: 0.8rem; line-height: 2; }

        @media (max-width: 900px) { 
            header { flex-direction: column; gap: 20px; padding: 40px 5%; text-align: center; }
            nav { display: flex; flex-direction: column; gap: 10px; margin: 0; }
            nav a { margin: 0; }
            .hero-split { flex-direction: column; } 
            .hero-text, .hero-image { width: 100%; height: auto; padding: 60px 20px; } 
            .hero-image { height: 450px; }
            .grid-3 { grid-template-columns: 1fr; gap: 40px; } 
        }
    </style>
</head>
<body>

<header>
    <a href="/" class="logo">TANVIR BHUPAL</a>
    <nav>
        <a href="/">Advisory</a>
        <a href="/intelligence">The Briefing</a>
        <a href="mailto:tanvir@realeasy.info">Contact</a>
    </nav>
</header>

<section class="hero-split">
  <div class="hero-text">
    <h1>Your move is a logistical undertaking.<br>I make it a strategic one.</h1>
    <p>Private relocation and real estate advisory for families moving with intention. Every decision is filtered for risk, lifestyle fit, and long-term value before a single offer is written.</p>
    <a href="/intelligence" style="display: inline-block; margin-top: 20px; text-decoration: underline; color: #1a1a1a; font-weight: bold; font-size: 0.8rem; letter-spacing: 1px;">ACCESS THE STRATEGIC BRIEFING</a>
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
  <div style="max-width: 1100px; margin: 0 auto;">
    <h2 style="font-weight: normal; margin-bottom: 10px; text-align: center; font-size: 2rem;">The Neighborhood Portfolio</h2>
    <p style="text-align: center; color: var(--soft); margin-bottom: 50px;">Strategic enclaves analyzed for lifestyle fit and long-term value.</p>
    <div class="portfolio-grid">
      <div class="enclave-card">ELGIN CHANTRELL</div>
      <div class="enclave-card">OCEAN PARK</div>
      <div class="enclave-card">MORGAN CREEK</div>
      <div class="enclave-card">PANORAMA RIDGE</div>
      <div class="enclave-card">FRASER HEIGHTS</div>
    </div>
  </div>
</section>

<footer>
  <div style="display: flex; justify-content: space-between; flex-wrap: wrap; gap: 40px;">
    <div>
      <p><strong>© 2026 Tanvir Bhupal. Real Estate Advisor.</strong></p>
      <p>eXp Realty – 701 W Georgia St #1500, Vancouver, BC V7Y 1G5</p>
      <p>604-897-7826</p>
    </div>
    <div style="color: #888; text-align: right;">
      <p>This website is not intended to solicit buyers or sellers currently under contract.</p>
      <p>All information is deemed reliable but not guaranteed.</p>
      <div style="margin-top: 20px; letter-spacing: 3px;">
        <a href="#" style="color: #888; text-decoration: none;">LINKEDIN</a> // 
        <a href="#" style="color: #888; text-decoration: none;">INSTAGRAM</a> // 
        <a href="#" style="color: #888; text-decoration: none;">SPOTIFY</a> // 
        <a href="#" style="color: #888; text-decoration: none;">GOOGLE</a>
      </div>
    </div>
  </div>
</footer>

</body>
</html>
