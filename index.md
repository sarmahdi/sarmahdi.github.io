---
layout: default
title: Home
description: Welcome to Syed A Mahdi's professional portfolio.
nav_order: 1
---

<style>
@import url("https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,500;12..96,700;12..96,800&family=Figtree:wght@400;500;600&display=swap");
.home { --bg:#f4f7f6; --surface:#ffffff; --ink:#0c2233; --muted:#51667a; --line:#d5dfe0; --accent:#067a46; --soft:#dff5e9; --mark:#03ef62; --deep:#0c2233; --on-deep:#e8f0f2; --on-deep-muted:#9bb0bf; --focus:#0b57d0; background:var(--bg); color:var(--ink); font-family:"Figtree",system-ui,-apple-system,"Segoe UI",sans-serif; font-size:1.0625rem; line-height:1.6; box-sizing:border-box; }
@media (prefers-color-scheme: dark) { .home { --bg:#08141e; --surface:#0e1f2d; --ink:#e8f0f2; --muted:#9bb0bf; --line:#223748; --accent:#4ee08c; --soft:#11382a; --deep:#0e1f2d; --focus:#8ab4ff; } }
.home *, .home *::before, .home *::after { box-sizing:inherit; }
.home h1, .home h2, .home h3 { font-family:"Bricolage Grotesque","Figtree",system-ui,sans-serif; margin:0; }
.home-wrap { max-width:1080px; margin:0 auto; padding:0 1.5rem; }
.home a:focus-visible { outline:3px solid var(--focus); outline-offset:3px; border-radius:3px; }
.home-hero { padding:5rem 0 4rem; border-bottom:1px solid var(--line); }
.home-hero .home-wrap { display:grid; grid-template-columns:minmax(0,1.5fr) minmax(0,1fr); gap:4rem; align-items:end; }
.home-hero h1 { font-weight:800; font-size:clamp(2.6rem,6.4vw,4.75rem); line-height:1; letter-spacing:-0.035em; margin-bottom:1.5rem; }
.home-hero p { color:var(--muted); max-width:60ch; margin:0 0 1rem; }
.home-hero p strong { color:var(--ink); }
.home-actions { display:flex; flex-wrap:wrap; gap:0.75rem; margin-top:2rem; }
.home-btn { display:inline-block; padding:0.8rem 1.4rem; border-radius:8px; font-weight:600; text-decoration:none; border:2px solid var(--ink); color:var(--ink); }
.home-btn--primary { background:var(--mark); border-color:var(--mark); color:#06210f; }
.home-btn--primary:hover { background:#2cf67f; border-color:#2cf67f; }
.home-btn--secondary:hover { background:var(--soft); }
.home-facts { margin:0; background:var(--surface); border:1px solid var(--line); border-top:4px solid var(--mark); border-radius:6px; padding:1.25rem 1.5rem; }
.home-facts div { padding:0.8rem 0; border-bottom:1px solid var(--line); }
.home-facts div:last-child { border-bottom:0; }
.home-facts dt { font-size:0.9rem; font-weight:600; color:var(--accent); }
.home-facts dd { margin:0.1rem 0 0; }
.home-section { display:grid; grid-template-columns:260px minmax(0,1fr); gap:3rem; padding:3.5rem 0; border-bottom:1px solid var(--line); }
.home-side { position:sticky; top:1.5rem; align-self:start; }
.home-side h2 { font-weight:700; font-size:1.75rem; line-height:1.15; letter-spacing:-0.02em; margin-bottom:0.5rem; }
.home-side p { margin:0; color:var(--muted); font-size:0.98rem; }
.home-areas { list-style:none; margin:0; padding:0; border-top:1px solid var(--line); }
.home-areas li { display:grid; grid-template-columns:minmax(0,1fr) auto; gap:1.5rem; align-items:center; padding:1.5rem 0; border-bottom:1px solid var(--line); }
.home-areas h3 { font-size:1.3rem; letter-spacing:-0.01em; margin-bottom:0.25rem; }
.home-areas p { margin:0; color:var(--muted); max-width:55ch; }
.home-link { font-weight:600; color:var(--ink); text-decoration:none; border-bottom:2px solid var(--mark); padding-bottom:1px; white-space:nowrap; }
.home-link:hover { background:var(--soft); }
.home-projects { padding:3.5rem 0; border-bottom:1px solid var(--line); }
.home-panel { background:var(--deep); color:var(--on-deep); border:1px solid var(--line); border-radius:10px; padding:2.5rem; display:grid; grid-template-columns:minmax(0,1fr) minmax(0,1fr); gap:3rem; align-items:center; }
.home-panel h2 { font-weight:700; font-size:1.9rem; line-height:1.15; letter-spacing:-0.02em; margin-bottom:0.75rem; }
.home-panel p { color:var(--on-deep-muted); margin:0 0 1.5rem; max-width:48ch; }
.home-panel .home-btn { border-color:var(--on-deep); color:var(--on-deep); }
.home-panel .home-btn:hover { background:rgba(255,255,255,0.1); }
.home-tally { display:grid; grid-template-columns:repeat(3,minmax(0,1fr)); border:1px solid rgba(255,255,255,0.18); border-radius:8px; }
.home-tally a { display:block; padding:1.1rem 1.1rem; color:inherit; text-decoration:none; border-right:1px solid rgba(255,255,255,0.18); }
.home-tally a:last-child { border-right:0; }
.home-tally a:hover { background:rgba(255,255,255,0.08); }
.home-tally strong { display:block; font-family:"Bricolage Grotesque","Figtree",sans-serif; font-size:2.5rem; line-height:1.1; color:var(--mark); }
.home-tally span { font-size:0.9rem; color:var(--on-deep-muted); }
.home-all { display:inline-block; margin-top:1rem; color:var(--on-deep); font-weight:600; text-decoration:none; border-bottom:2px solid var(--mark); }
.home-closing { padding:4rem 0 5rem; display:flex; flex-wrap:wrap; justify-content:space-between; align-items:center; gap:2rem; }
.home-closing h2 { font-weight:700; font-size:clamp(1.7rem,3.6vw,2.4rem); line-height:1.1; letter-spacing:-0.025em; margin-bottom:0.5rem; max-width:20ch; }
.home-closing p { margin:0; color:var(--muted); max-width:46ch; }
.home-sr { position:absolute; width:1px; height:1px; overflow:hidden; clip:rect(0 0 0 0); white-space:nowrap; }
@media (max-width:860px) { .home-hero { padding:3rem 0; } .home-hero .home-wrap, .home-section, .home-panel { grid-template-columns:1fr; gap:2rem; } .home-side { position:static; } .home-areas li { grid-template-columns:1fr; gap:0.75rem; } .home-panel { padding:1.75rem; } }
@media (prefers-reduced-motion: no-preference) { .home-btn, .home-link, .home-tally a { transition:background-color 0.15s ease; } }
</style>
<div class="home">
<header class="home-hero">
<div class="home-wrap">
<div>
<h1>Turning curiosity into practical capability.</h1>
<p>Hello, I’m <strong>Syed A Mahdi</strong>, a Software engineer with experience across the fintech and autonomous mining industries. I develop web and desktop java applications using microservices architecture, with both event-driven and request-response communication, and RESTful APIs.</p>
<p>Alongside that work, I’m building my knowledge of data, cloud technology and artificial intelligence through structured learning and hands-on projects.</p>
<div class="home-actions">
<a class="home-btn home-btn--primary" href="{{ '/projects/' | relative_url }}">Explore my projects</a>
<a class="home-btn home-btn--secondary" href="{{ '/about/' | relative_url }}">More about me</a>
</div>
</div>
<dl class="home-facts">
<div><dt>Role</dt><dd>Software engineer</dd></div>
<div><dt>Industries</dt><dd>Fintech, autonomous mining and Government</dd></div>
<div><dt>Developed</dt><dd>Web and desktop applications</dd></div>
<div><dt>Architecture</dt><dd>Microservices, event-driven and request-response, RESTful APIs</dd></div>
</dl>
</div>
</header>
<div class="home-wrap">
<section class="home-section" aria-labelledby="focus-title">
<div class="home-side">
<h2 id="focus-title">Currently learning</h2>
<p>Three areas I’m building up, each with a practical focus.</p>
</div>
<ul class="home-areas">
<li>
<div><h3>Data and analysis</h3><p>Working with data in Python and pandas, and exploring datasets to find useful insights.</p></div>
<a class="home-link" href="{{ '/skills/' | relative_url }}">See my skills</a>
</li>
<li>
<div><h3>Artificial intelligence</h3><p>Building foundational knowledge of AI, AI agents and large language model concepts.</p></div>
<a class="home-link" href="{{ '/datacamp-activities/' | relative_url }}">View courses</a>
</li>
<li>
<div><h3>Cloud technology</h3><p>Learning core cloud concepts and the services available through AWS.</p></div>
<a class="home-link" href="{{ '/datacamp-activities/' | relative_url }}">View certificate</a>
</li>
</ul>
</section>
<section class="home-projects" aria-labelledby="projects-title">
<div class="home-panel">
<div>
<h2 id="projects-title">Learning applied through projects</h2>
<p>Practical exercises turn concepts into experience. Explore the DataCamp projects documented here.</p>
<a class="home-btn" href="{{ '/projects/' | relative_url }}">View projects</a>
</div>
<div>
<div class="home-tally">
<a href="{{ '/datacamp-activities/' | relative_url }}#tracks"><strong>2</strong><span>Tracks</span></a>
<a href="{{ '/datacamp-activities/' | relative_url }}#courses"><strong>3</strong><span>Courses</span></a>
<a href="{{ '/datacamp-activities/' | relative_url }}#projects"><strong>2</strong><span>Projects</span></a>
</div>
<a class="home-all" href="{{ '/datacamp-activities/' | relative_url }}">Browse all achievements</a>
</div>
</div>
</section>
<section class="home-closing">
<div>
<h2>Follow my work on GitHub</h2>
<p>See what I’m building and how my learning is progressing.</p>
</div>
<a class="home-btn home-btn--primary" href="https://github.com/sarmahdi" target="_blank" rel="noopener noreferrer">Find me on GitHub<span class="home-sr"> (opens in a new tab)</span></a>
</section>
</div>
</div>
