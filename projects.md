---
layout: default
title: Projects
description: Selected practical projects completed through DataCamp.
permalink: /projects/
nav_order: 4
---

<style>
@import url("https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,500;12..96,700;12..96,800&family=Figtree:wght@400;500;600&display=swap");
.prj { --bg:#f4f7f6; --surface:#ffffff; --ink:#0c2233; --muted:#51667a; --line:#d5dfe0; --accent:#067a46; --soft:#dff5e9; --mark:#03ef62; --focus:#0b57d0; background:var(--bg); color:var(--ink); font-family:"Figtree",system-ui,-apple-system,"Segoe UI",sans-serif; font-size:1.0625rem; line-height:1.6; box-sizing:border-box; }
@media (prefers-color-scheme: dark) { .prj { --bg:#08141e; --surface:#0e1f2d; --ink:#e8f0f2; --muted:#9bb0bf; --line:#223748; --accent:#4ee08c; --soft:#11382a; --focus:#8ab4ff; } }
.prj *, .prj *::before, .prj *::after { box-sizing:inherit; }
.prj h1, .prj h2 { font-family:"Bricolage Grotesque","Figtree",system-ui,sans-serif; margin:0; }
.prj-wrap { max-width:1080px; margin:0 auto; padding:0 1.5rem; }
.prj a:focus-visible { outline:3px solid var(--focus); outline-offset:3px; border-radius:3px; }
.prj-hero { padding:5rem 0 3.5rem; border-bottom:1px solid var(--line); }
.prj-hero h1 { font-weight:800; font-size:clamp(2.6rem,7vw,5rem); line-height:1; letter-spacing:-0.035em; margin-bottom:1.25rem; }
.prj-hero p { max-width:58ch; color:var(--muted); margin:0; }
.prj-grid { list-style:none; margin:0; padding:3.5rem 0; display:grid; grid-template-columns:repeat(2,minmax(0,1fr)); gap:1.5rem; }
.prj-card { display:flex; flex-direction:column; background:var(--surface); border:1px solid var(--line); border-top:4px solid var(--mark); border-radius:6px; padding:2rem; }
.prj-field { margin:0 0 0.75rem; font-size:0.9rem; font-weight:600; color:var(--accent); }
.prj-card h2 { font-weight:700; font-size:1.9rem; line-height:1.1; letter-spacing:-0.02em; margin-bottom:1rem; }
.prj-card p.prj-desc { margin:0 0 1.25rem; color:var(--muted); max-width:46ch; }
.prj-tags { display:flex; flex-wrap:wrap; gap:0.4rem; margin:0 0 2rem; padding:0; list-style:none; }
.prj-tags li { font-size:0.85rem; padding:0.15rem 0.65rem; border-radius:999px; background:var(--soft); color:var(--ink); }
.prj-link { margin-top:auto; align-self:flex-start; font-weight:600; color:var(--ink); text-decoration:none; border-bottom:2px solid var(--mark); padding-bottom:1px; }
.prj-link:hover { background:var(--soft); }
.prj-cta { padding:0 0 5rem; }
.prj-btn { display:inline-block; padding:0.8rem 1.4rem; border-radius:8px; font-weight:600; text-decoration:none; border:2px solid var(--ink); color:var(--ink); }
.prj-btn:hover { background:var(--soft); }
.prj-sr { position:absolute; width:1px; height:1px; overflow:hidden; clip:rect(0 0 0 0); white-space:nowrap; }
@media (max-width:800px) { .prj-hero { padding:3rem 0 2.5rem; } .prj-grid { grid-template-columns:1fr; padding:2.5rem 0; } .prj-card { padding:1.5rem; } }
@media (prefers-reduced-motion: no-preference) { .prj-btn, .prj-link { transition:background-color 0.15s ease; } }
</style>
<div class="prj" markdown="0">
<header class="prj-hero">
<div class="prj-wrap">
<h1>Projects</h1>
<p>Practical exercises that put data manipulation, exploration and visualisation concepts into action.</p>
</div>
</header>
<div class="prj-wrap">
<ul class="prj-grid">
<li class="prj-card">
<p class="prj-field">Exploratory data analysis</p>
<h2>Getting a Good Night’s Sleep</h2>
<p class="prj-desc">Dive into sleep data and gain insights about factors that impact sleep quality.</p>
<ul class="prj-tags"><li>Data manipulation</li><li>Exploratory data analysis</li></ul>
<a class="prj-link" href="https://www.datacamp.com/completed/statement-of-accomplishment/project/40dda5fe-e07e-45e4-9386-aa5d6bb707bb" target="_blank" rel="noopener noreferrer">View DataCamp statement of accomplishment<span class="prj-sr"> (opens in a new tab)</span></a>
</li>
<li class="prj-card">
<p class="prj-field">Data manipulation and visualisation</p>
<h2>Investigating Netflix Movies</h2>
<p class="prj-desc">Apply foundational Python skills to manipulate and visualize movie data.</p>
<ul class="prj-tags"><li>Data manipulation</li><li>Data visualisation</li><li>Python</li></ul>
<a class="prj-link" href="https://www.datacamp.com/completed/statement-of-accomplishment/project/976f8ade-4846-43c3-ae6c-ab15c173d276" target="_blank" rel="noopener noreferrer">View DataCamp statement of accomplishment<span class="prj-sr"> (opens in a new tab)</span></a>
</li>
</ul>
<div class="prj-cta">
<a class="prj-btn" href="{{ '/datacamp/' | relative_url }}">View all learning achievements</a>
</div>
</div>
</div>
