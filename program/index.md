---
layout: home
title: Conference Program Overview
permalink: /program
---

<style>
  :root{
    --bg:#0e1b4d;           /* ICSOB dark blue */
    --ink:#0b132b;
    --muted:#667085;
    --card:#ffffff;
    --soft:#edf5ff;         /* light accent */
    --accent:#4f7cff;       /* link / accent */
    --accent-2:#00b0a6;     /* secondary accent */
    --ring:rgba(79,124,255,.25);
    --shadow:0 10px 25px rgba(10, 22, 70, .08);
    --radius:18px;
  }

  /* Page basics */
  body{font-family: Arial, system-ui, -apple-system, Segoe UI, Roboto, sans-serif; color:var(--ink); background:linear-gradient(180deg,#f7f9fc 0%,#f9fbff 100%); margin:0}
  .container{max-width:1100px; margin:0 auto; padding:24px}
  .title-wrap{
    background: radial-gradient(1200px 400px at 50% -20%, #cfe0ff 0%, transparent 60%),
                linear-gradient(90deg, #0e1b4d, #1f3a93 60%, #2f63ff);
    color:#fff; padding:56px 20px; border-radius:0 0 28px 28px; box-shadow:var(--shadow)
  }
  .title-wrap h1{margin:0; font-size: clamp(28px, 4.2vw, 44px); letter-spacing:.2px}
  .subtitle{opacity:.95; margin-top:10px; font-size:clamp(14px, 2.2vw, 18px)}
  .hint{display:inline-block; margin-top:16px; background:rgba(255,255,255,.18); padding:8px 12px; border-radius:999px; font-size:12px; letter-spacing:.3px}

  /* Local nav buttons */
  .day-nav{display:flex; gap:10px; flex-wrap:wrap; margin:18px 0 28px}
  .day-nav a{
    text-decoration:none; color:#0e1b4d; background:#fff; border:1px solid #e6eaf5;
    padding:10px 14px; border-radius:999px; font-weight:600; box-shadow:var(--shadow)
  }
  .day-nav a:hover{border-color:#c9d6ff; box-shadow:0 12px 24px var(--ring)}

  /* Day cards */
  .day-card{
    background:var(--card); border-radius:var(--radius); box-shadow:var(--shadow);
    margin:22px 0; overflow:hidden; border:1px solid #e8eefc
  }
  .day-head{
    display:flex; align-items:center; justify-content:space-between; gap:12px;
    padding:18px 22px; background:
      linear-gradient(90deg, var(--soft), #e6f0ff);
    border-bottom:1px solid #dfe8ff
  }
  .badge{
    display:inline-flex; align-items:center; gap:8px; font-weight:700;
    padding:6px 12px; border-radius:999px; background:#0e1b4d; color:#fff; letter-spacing:.3px
  }
  .date{
    color:#0e1b4d; font-weight:700; font-size:14px; opacity:.9
  }

  /* Timeline */
  .timeline{padding:22px}
  .t-row{
    position:relative; display:grid; grid-template-columns: 16px 1fr; gap:16px; margin:14px 0
  }
  .t-row:before{
    content:""; position:absolute; left:7px; top:-6px; bottom:-6px; width:2px; background:#e1e8ff
  }
  .dot{
    width:14px; height:14px; background:var(--accent); border-radius:50%;
    border:3px solid #fff; box-shadow:0 0 0 4px var(--ring); margin-top:4px
  }
  .card{
    background:#fff; border:1px solid #eef2ff; border-radius:14px; padding:14px 16px
  }
  .card h4{margin:0 0 4px; font-size:16px; color:#0e1b4d}
  .meta{font-size:12px; color:var(--muted); margin-bottom:8px}
  .chips{display:flex; gap:8px; flex-wrap:wrap; margin-top:6px}
  .chip{font-size:11px; padding:5px 10px; border-radius:999px; background:#f2f6ff; border:1px solid #e2e9ff}

  /* Two-column list inside a card (excursions) */
  .cols{display:grid; grid-template-columns:repeat(2, minmax(0,1fr)); gap:12px}
  @media (max-width:720px){ .cols{grid-template-columns:1fr} }

  /* Footer note */
  .note{margin:18px 2px 8px; font-size:13px; color:var(--muted); text-align:center}
</style>

<div class="title-wrap">
  <div class="container">
    <h1>Conference Program Overview</h1>
    <div class="subtitle">Short agenda for ICSOB 2025 — subject to minor adjustments.</div>
    <span class="hint">Tip: Use the day buttons below to jump.</span>
  </div>
</div>

<div class="container">
  <div class="day-nav">
    <a href="#mon">Mon · Nov 24</a>
    <a href="#tue">Tue · Nov 25</a>
    <a href="#wed">Wed · Nov 26</a>
  </div>

  <!-- Monday -->
  <section id="mon" class="day-card">
    <div class="day-head">
      <span class="badge">Monday</span>
      <div class="date">November 24, 2025</div>
    </div>
    <div class="timeline">
      <div class="t-row">
        <div class="dot"></div>
        <div class="card">
          <h4>PhD Retreat</h4>
          <div class="meta">All day</div>
          <div class="chips"><span class="chip">Community</span><span class="chip">Research Training</span></div>
        </div>
      </div>

      <div class="t-row">
        <div class="dot"></div>
        <div class="card">
          <h4>Workshop 1 & Workshop 2</h4>
          <div class="meta">Walk-In & Registration · Coffee Breaks · Lunch</div>
          <div class="chips"><span class="chip">Workshops</span><span class="chip">Networking</span></div>
        </div>
      </div>

      <div class="t-row">
        <div class="dot"></div>
        <div class="card">
          <h4>Evening</h4>
          <div class="meta">Time for hotel check-in & transfer to Markthalle Stuttgart (self-organized)</div>
        </div>
      </div>

      <div class="t-row">
        <div class="dot"></div>
        <div class="card">
          <h4>Welcome Reception</h4>
          <div class="meta">Restaurant Ampulle, Markthalle Stuttgart</div>
          <div class="chips"><span class="chip">Reception</span><span class="chip">Get-together</span></div>
        </div>
      </div>
    </div>
  </section>

  <!-- Tuesday -->
  <section id="tue" class="day-card">
    <div class="day-head" style="background:linear-gradient(90deg,#e7fff8,#e6f0ff);">
      <span class="badge" style="background:var(--accent-2)">Tuesday</span>
      <div class="date">November 25, 2025</div>
    </div>
    <div class="timeline">

      <div class="t-row"><div class="dot"></div>
        <div class="card"><h4>Walk-In & Registration</h4></div></div>

      <div class="t-row"><div class="dot"></div>
        <div class="card"><h4>Opening & Introduction</h4></div></div>

      <div class="t-row"><div class="dot"></div>
        <div class="card"><h4>Keynote 1</h4><div class="chips"><span class="chip">Keynote</span></div></div></div>

      <div class="t-row"><div class="dot"></div>
        <div class="card"><h4>Coffee Break</h4></div></div>

      <div class="t-row"><div class="dot"></div>
        <div class="card">
          <h4>Parallel Sessions</h4>
          <div class="meta">Session 1 & Session 2</div>
          <div class="chips"><span class="chip">Parallel</span><span class="chip">Research Talks</span></div>
        </div>
      </div>

      <div class="t-row"><div class="dot"></div>
        <div class="card"><h4>Lunch</h4></div></div>

      <div class="t-row"><div class="dot"></div>
        <div class="card">
          <h4>Parallel Sessions</h4>
          <div class="meta">Session 3 & Session 4</div>
        </div>
      </div>

      <div class="t-row"><div class="dot"></div>
        <div class="card"><h4>Coffee Break, Demos & Poster Session</h4></div></div>

      <div class="t-row"><div class="dot"></div>
        <div class="card">
          <h4>Parallel Sessions</h4>
          <div class="meta">Session 5 & Session 6</div>
        </div>
      </div>

      <div class="t-row"><div class="dot"></div>
        <div class="card">
          <h4>Excursions</h4>
          <div class="cols">
            <div>
              <strong>Ex 1: IBM / Quantum Computing</strong>
              <div class="meta">16:15–17:00 transfer · 17:00–18:45 tour · 18:45–19:30 transfer</div>
            </div>
            <div>
              <strong>Ex 2: Computer Museum</strong>
              <div class="meta">17:30–18:00 transfer (via 3) · 18:00–19:00 tour · 19:00–19:30 transfer (via 3)</div>
            </div>
            <div>
              <strong>Ex 3: Arena2036</strong>
              <div class="meta">17:30–17:50 transfer · 17:50–19:10 tour · 19:10–19:30 transfer</div>
            </div>
          </div>
        </div>
      </div>

      <div class="t-row"><div class="dot"></div>
        <div class="card">
          <h4>Dinner, Entertaining Keynote 2 & Awards</h4>
          <div class="meta">Leonhardts, Fernsehturm</div>
          <div class="chips"><span class="chip">Social</span><span class="chip">Awards</span></div>
        </div>
      </div>
    </div>
  </section>

  <!-- Wednesday -->
  <section id="wed" class="day-card">
    <div class="day-head">
      <span class="badge">Wednesday</span>
      <div class="date">November 26, 2025</div>
    </div>
    <div class="timeline">

      <div class="t-row"><div class="dot"></div>
        <div class="card"><h4>Opening & Introduction</h4></div></div>

      <div class="t-row"><div class="dot"></div>
        <div class="card"><h4>Keynote 3</h4></div></div>

      <div class="t-row"><div class="dot"></div>
        <div class="card"><h4>Coffee Break, Demos & Poster Session</h4></div></div>

      <div class="t-row"><div class="dot"></div>
        <div class="card">
          <h4>Parallel Sessions</h4>
          <div class="meta">Session 6 & Session 7</div>
        </div>
      </div>

      <div class="t-row"><div class="dot"></div>
        <div class="card"><h4>Lunch</h4></div></div>

      <div class="t-row"><div class="dot"></div>
        <div class="card">
          <h4>Parallel Sessions</h4>
          <div class="meta">Session 8 & Session 9</div>
        </div>
      </div>

      <div class="t-row"><div class="dot"></div>
        <div class="card"><h4>Coffee Break, Demos & Poster Session</h4></div></div>

      <div class="t-row"><div class="dot"></div>
        <div class="card"><h4>Closing</h4></div></div>

    </div>
  </section>

  <div class="note">Times and details are indicative and may be adjusted. Final schedule will be announced on site.</div>
</div>
