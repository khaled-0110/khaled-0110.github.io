<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Khaled Nasser • Data Engineering Portfolio</title>
  <meta name="description" content="Data cleaning, SQL analysis, and beginner-friendly data engineering projects by Khaled Nasser." />
  <meta property="og:title" content="Khaled Nasser • Data Engineering Portfolio">
  <meta property="og:description" content="Data cleaning, SQL analysis, and beginner-friendly data engineering projects by Khaled Nasser.">
  <meta property="og:type" content="website">
  <meta name="theme-color" content="#0ea5e9">
  <link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><rect width='100' height='100' rx='16' fill='%230ea5e9'/><text x='50' y='62' font-family='Verdana' font-size='54' text-anchor='middle' fill='white'>K</text></svg>">
  <style>
    :root{
      --bg:#0b1220; --card:#0f172a; --muted:#94a3b8; --text:#e2e8f0; --accent:#0ea5e9; --ring:#38bdf8;
      --shadow:0 10px 30px rgba(2,8,23,.35);
      --radius:18px;
    }
    *{box-sizing:border-box}
    html{scroll-behavior:smooth}
    body{margin:0;font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,Cantarell,'Helvetica Neue',Arial,sans-serif;background:linear-gradient(180deg,#0b1220 0%,#0a0f1a 100%);color:var(--text)}
    a{color:inherit;text-decoration:none}
    .container{max-width:1100px;margin:0 auto;padding:24px}
    header{position:sticky;top:0;backdrop-filter:blur(10px);background:rgba(11,18,32,.55);border-bottom:1px solid rgba(148,163,184,.15);z-index:20}
    .nav{display:flex;align-items:center;gap:16px;justify-content:space-between}
    .brand{display:flex;align-items:center;gap:10px;font-weight:700}
    .brand .logo{width:36px;height:36px;border-radius:12px;background:var(--accent);display:grid;place-items:center;box-shadow:var(--shadow)}
    .brand .logo span{font-weight:900;color:#001018}
    .nav a{padding:10px 12px;border-radius:10px;color:var(--muted)}
    .nav a:hover{background:rgba(56,189,248,.08);color:var(--text)}
    .btn{display:inline-flex;align-items:center;gap:10px;background:var(--accent);color:#05121a;padding:12px 16px;border:none;border-radius:14px;font-weight:700;box-shadow:var(--shadow);cursor:pointer}
    .btn:is(:hover,:focus){outline:none;box-shadow:0 0 0 4px rgba(56,189,248,.25), var(--shadow)}
    .grid{display:grid;gap:22px}
    .hero{padding:56px 0 22px}
    .hero-card{border:1px solid rgba(148,163,184,.15);background:linear-gradient(160deg,rgba(14,165,233,.06),transparent 40%),var(--card);border-radius:var(--radius);padding:30px;display:grid;grid-template-columns:1.2fr .8fr;gap:24px;align-items:center}
    .hero h1{font-size:42px;line-height:1.1;margin:0}
    .hero p{color:var(--muted);margin:10px 0 24px}
    .pill{display:inline-flex;gap:8px;align-items:center;font-size:13px;color:#7dd3fc;background:rgba(14,165,233,.15);border:1px solid rgba(56,189,248,.35);padding:6px 10px;border-radius:999px}
    .avatar{width:160px;height:160px;border-radius:22px;background:linear-gradient(160deg,#0ea5e9 0%,#22d3ee 100%);padding:4px}
    .avatar img{width:100%;height:100%;object-fit:cover;border-radius:18px;display:block}
    section{padding:26px 0}
    h2{font-size:28px;margin:0 0 14px}
    .card{background:var(--card);border:1px solid rgba(148,163,184,.15);border-radius:var(--radius);padding:20px;box-shadow:var(--shadow)}
    .skills{grid-template-columns:repeat(auto-fit,minmax(220px,1fr))}
    .chip{display:inline-flex;gap:8px;align-items:center;border:1px solid rgba(148,163,184,.25);padding:8px 12px;border-radius:999px;margin:6px 6px 0 0;color:var(--muted)}
    .projects{grid-template-columns:repeat(auto-fit,minmax(260px,1fr))}
    .project{display:flex;flex-direction:column;gap:12px}
    .project h3{margin:0}
    .project .meta{font-size:13px;color:var(--muted)}
    .project .actions{margin-top:auto;display:flex;gap:10px;flex-wrap:wrap}
    .services{grid-template-columns:repeat(auto-fit,minmax(260px,1fr))}
    .service h3{margin:0 0 8px}
    .service ul{margin:0;padding-left:18px;color:var(--muted)}
    .contact{display:grid;grid-template-columns:1fr 1fr;gap:22px}
    .list{margin:0;padding-left:18px;color:var(--muted)}
    footer{padding:30px 0;color:var(--muted);text-align:center}
    .kbd{font-family:ui-monospace, SFMono-Regular, Menlo, Consolas, monospace;background:#0b1220;border:1px solid rgba(148,163,184,.2);border-bottom-width:3px;padding:2px 6px;border-radius:8px}

    @media (max-width:900px){
      .hero-card{grid-template-columns:1fr}
      .contact{grid-template-columns:1fr}
    }
  </style>
  <script>
    // Simple theme memory (future-proof for adding light mode)
    (function(){
      const saved = localStorage.getItem('theme');
      if(saved === 'light'){document.documentElement.style.setProperty('--bg','#f8fafc');}
    })();
    function copyEmail(){
      const email = 'khalednasser602@gmail.com';
      navigator.clipboard.writeText(email).then(()=>{
        const el = document.getElementById('copied');
        el.textContent = 'Copied!';
        setTimeout(()=> el.textContent = 'Copy', 1200);
      })
    }
  </script>
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Khaled Nasser",
    "jobTitle": "Data Engineering Student & Freelancer",
    "url": "https://khaled-0110.github.io/",
    "sameAs": [
      "https://www.upwork.com/](https://www.upwork.com/freelancers/~01f46ef7187c8ddb2d?mp_source=share",
      "https://github.com/khaled-0110"
    ],
    "knowsAbout": ["SQL","Python","Pandas","Data Cleaning","ETL","Dashboards"]
  }
  </script>
</head>
<body>
  <header>
    <div class="container nav">
      <a class="brand" href="#top">
  <div class="logo">
    <img src="https://i.ibb.co/0jbJsWmW/Chat-GPT-Image-Aug-9-2025-06-02-38-PM-Small.png" alt="Khaled Nasser Logo">
  </div>
  <span>Khaled Nasser</span>
</a>
      <nav>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main id="top" class="container">
    <!-- HERO -->
    <section class="hero">
      <div class="hero-card">
        <div>
          <span class="pill">Data Cleaning • SQL • Python</span>
          <h1>Turning messy data into usable insights.</h1>
          <p>
            I’m <strong>Khaled</strong>, a BIS student in Egypt and a beginner data engineer. I help with
            <em>data cleaning, SQL analysis, outlier handling</em>, and simple ETL tasks. Practical, fast, affordable.
          </p>
          <div class="grid" style="grid-template-columns:repeat(auto-fit,minmax(180px,1fr));">
            <a class="btn" href="#services">Hire for a small task</a>
            <a class="btn" style="background:#22d3ee;color:#00202a" href="#projects">View projects</a>
          </div>
        </div>
        <div style="justify-self:center">
          <div class="avatar">
            <!-- Replace with your own photo if you like -->
            <img alt="Abstract banner" src="https://images.unsplash.com/photo-1542831371-d531d36971e6?q=80&w=800&auto=format&fit=crop"/>
          </div>
        </div>
      </div>
    </section>

    <!-- PROJECTS -->
    <section id="projects">
      <h2>Projects</h2>
      <div class="grid projects">
        <article class="card project">
          <h3>Outlier Cleaning (SQL & Python)</h3>
          <p class="meta">3σ rule • replace/flag outliers • reproducible scripts</p>
          <p>Demo of calculating averages, detecting outliers, and adjusting values using SQL and Pandas. Includes README and sample data.</p>
          <div class="actions">
            <a class="btn" href="https://github.com/khaled-0110/data-cleaning-examples" target="_blank" rel="noopener">GitHub Repo</a>
          </div>
        </article>
        <article class="card project">
          <h3>CSV → SQLite Mini ETL</h3>
          <p class="meta">ingest • transform • load • simple reporting</p>
          <p>Small ETL pipeline: load CSVs, clean types, write to SQLite, and run SQL reports. Great for small business data.</p>
          <div class="actions">
            <a class="btn" href="https://github.com/khaled-0110/mini-etl-sqlite" target="_blank" rel="noopener">GitHub Repo</a>
          </div>
        </article>
        <article class="card project">
          <h3>Web Scraping Basics</h3>
          <p class="meta">requests • BeautifulSoup • Pandas</p>
          <p>Beginner scraper to collect tabular data, validate, and export to CSV for analysis. Includes polite scraping checklist.</p>
          <div class="actions">
            <a class="btn" href="https://github.com/khaled-0110/web-scraping-basics" target="_blank" rel="noopener">GitHub Repo</a>
          </div>
        </article>
      </div>
    </section>

    <!-- SKILLS -->
    <section id="skills">
      <h2>Skills</h2>
      <div class="grid skills">
        <div class="card">
          <h3>Core</h3>
          <p>
            <span class="chip">SQL (SELECT • JOIN • GROUP BY)</span>
            <span class="chip">Python (Pandas, NumPy)</span>
            <span class="chip">Data Cleaning</span>
            <span class="chip">Outlier Detection</span>
            <span class="chip">CSV/Excel Processing</span>
          </p>
        </div>
        <div class="card">
          <h3>Tools</h3>
          <p>
            <span class="chip">Jupyter Notebook</span>
            <span class="chip">SQLite / SQL Server</span>
            <span class="chip">Git & GitHub</span>
            <span class="chip">Power BI (basics)</span>
          </p>
        </div>
        <div class="card">
          <h3>Soft Skills</h3>
          <p>
            <span class="chip">Clear Communication</span>
            <span class="chip">Documentation</span>
            <span class="chip">Client-Focused</span>
            <span class="chip">Fast Iteration</span>
          </p>
        </div>
      </div>
    </section>

    <!-- SERVICES / PLANS -->
    <section id="services">
      <h2>Services</h2>
      <div class="grid services">
        <div class="card service">
          <h3>Starter — Basic Cleaning</h3>
          <ul>
            <li>Remove duplicates & fix formats</li>
            <li>Up to 10k rows</li>
            <li>Delivery: 1 day • 1 revision</li>
          </ul>
          <p><strong>$20</strong></p>
        </div>
        <div class="card service">
          <h3>Standard — Cleaning + Outliers</h3>
          <ul>
            <li>3σ or IQR outlier handling</li>
            <li>SQL or Python scripts included</li>
            <li>Up to 50k rows • 2 revisions</li>
          </ul>
          <p><strong>$40</strong></p>
        </div>
        <div class="card service">
          <h3>Advanced — Custom Scripts</h3>
          <ul>
            <li>Automation scripts + docs</li>
            <li>100k+ rows support</li>
            <li>Delivery: 3 days • 3 revisions</li>
          </ul>
          <p><strong>$70</strong></p>
        </div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact">
      <h2>Contact</h2>
      <div class="contact">
        <div class="card">
          <p>Let’s work on your data. Email me or reach me on Upwork/GitHub.</p>
          <p>
            <button class="btn" onclick="copyEmail()">Email: khalednasser602@gmail.com <span id="copied" class="kbd" style="margin-left:8px">Copy</span></button>
          </p>
          <p class="grid" style="grid-template-columns:repeat(auto-fit,minmax(160px,1fr));gap:12px">
            <a class="btn" href="https://github.com/khaled-0110" target="_blank" rel="noopener">GitHub</a>
            <a class="btn" href="https://www.upwork.com/freelancers/~01f46ef7187c8ddb2d?mp_source=share" target="_blank" rel="noopener">Upwork</a>
          </p>
        </div>
  </main>

  <footer>
    © <span id="yr"></span> Khaled Nasser • Built with HTML/CSS
  </footer>

  <script>document.getElementById('yr').textContent = new Date().getFullYear()</script>
</body>
</html>
