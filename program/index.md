---
layout: home
title: Conference Program Overview
permalink: /program
---

<style>
  :root{
    --ink:#0a1133;
    --muted:#495067;
    --card:#ffffff;
    --accent:#0e1b4d;
    --accent-2:#0e8f86;
    --shadow:0 10px 25px rgba(10,22,70,.08);
    --radius:14px;
  }
  body{font-family: Arial, system-ui, sans-serif; color:var(--ink); background:#f6f8fc; margin:0}
  .container{max-width:1100px; margin:0 auto; padding:24px}
  .title-wrap{background:linear-gradient(180deg,#0e1b4d 0%, #1f3a93 80%); color:#fff; padding:56px 20px; border-radius:0 0 28px 28px; box-shadow:var(--shadow); text-align:center}
  .title-wrap h1{margin:0; font-size:clamp(28px, 4vw, 44px)}
  .subtitle{opacity:.95; margin-top:10px; font-size:clamp(14px, 2vw, 18px)}

  /* Navigation buttons */
  .day-nav{display:flex; justify-content:center; flex-wrap:wrap; gap:12px; margin:28px 0}
  .day-nav a{
    text-decoration:none;
    background:#fff;
    border:2px solid #d8e0f5;
    color:var(--accent);
    font-weight:700;
    padding:10px 18px;
    border-radius:999px;
    transition:all .2s ease;
    box-shadow:0 4px 8px rgba(10,22,70,.05);
  }
  .day-nav a:hover{background:var(--accent); color:#fff; border-color:var(--accent)}

  /* Day cards */
  .day-card{background:var(--card); border:1px solid #e3e9fc; border-radius:var(--radius); box-shadow:var(--shadow); margin:22px 0; overflow:hidden}
  .day-head{padding:18px 22px; background:linear-gradient(90deg,#eaf2ff,#e6f0ff); border-bottom:1px solid #dfe6ff; display:flex; justify-content:space-between; align-items:center}
  .badge{background:#0e1b4d; color:#fff; font-weight:700; padding:6px 12px; border-radius:999px; font-size:14px}
  .badge.green{background:var(--accent-2)}
  .date{font-weight:700; color:#0e1b4d}

  /* Timeline list */
  .agenda{position:relative; margin:0; padding:30px 22px; list-style:none}
  .agenda:before{content:""; position:absolute; top:0; bottom:0; left:42px; width:2px; background:#dfe6ff}
  .agenda-item{position:relative; padding-left:80px; margin-bottom:26px}
  .agenda-item:last-child{margin-bottom:0}
  .agenda-dot{position:absolute; left:34px; top:6px; width:18px; height:18px; border-radius:50%; background:var(--accent); border:3px solid #fff; box-shadow:0 0 0 4px rgba(14,27,77,.15)}
  .agenda-card{background:#fff; border:1px solid #e8ecf9; border-radius:var(--radius); padding:14px 16px; box-shadow:0 4px 8px rgba(10,22,70,.05)}
  .agenda-card h4{margin:0 0 6px; font-size:16px; color:var(--accent)}
  .agenda-card p{margin:0; font-size:14px; color:var(--muted)}
  .agenda-sublist{margin:6px 0 0 16px; font-size:14px; color:var(--ink)}
  .agenda-sublist li{margin:3px 0}
</style>

<div class="title-wrap">
  <h1>Conference Program Overview</h1>
  <div class="subtitle">Initial program for ICSOB 2025 — times and details will be published later.</div>
</div>

<div class="container">

  <!-- Navigation -->
  <div class="day-nav">
    <a href="#monday">Monday · Nov 24</a>
    <a href="#tuesday">Tuesday · Nov 25</a>
    <a href="#wednesday">Wednesday · Nov 26</a>
  </div>

  <!-- Monday -->
  <section id="monday" class="day-card">
    <div class="day-head">
      <span class="badge">Monday</span>
      <div class="date">November 24, 2025</div>
    </div>
    <ul class="agenda">
      
      
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Walk-In & Registration</h4></div></li>
	  <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Part 1: PhD Retreat, Workshop 1 & Workshop 2</h4></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Coffee Breaks</h4></div></li>
	  <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Part 2:PhD Retreat, Workshop 1 & Workshop 2</h4></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Lunch</h4></div></li>
	  <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Part 3:PhD Retreat, Workshop 1 & Workshop 2</h4></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Hotel Check-in & Transfer</h4><p>To Markthalle Stuttgart (self-organized)</p></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Welcome Reception</h4><p>Restaurant Ampulle, Markthalle Stuttgart</p></div></li>
    </ul>
  </section>

  <!-- Tuesday -->
  <section id="tuesday" class="day-card">
    <div class="day-head">
      <span class="badge green">Tuesday</span>
      <div class="date">November 25, 2025</div>
    </div>
    <ul class="agenda">
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Walk-In & Registration</h4></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Opening & Introduction</h4></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Keynote 1</h4></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Coffee Break</h4></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Parallel Paper Sessions</h4><p>Session 1 & Session 2</p></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Lunch</h4></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Parallel Paper Sessions</h4><p>Session 3 & Session 4</p></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Coffee Break, Demos & Poster Session</h4></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Parallel Paper Sessions</h4><p>Session 5 & Session 6</p></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span>
        <div class="agenda-card">
          <h4>Excursions</h4>
          <ul class="agenda-sublist">
            <li>Ex 1: IBM / Quantum Computing</li>
            <li>Ex 2: Computer Museum</li>
            <li>Ex 3: Arena2036</li>
          </ul>
        </div>
      </li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Dinner, Entertaining Keynote 2 & Awards</h4><p>Leonhardts, Fernsehturm</p></div></li>
    </ul>
  </section>

  <!-- Wednesday -->
  <section id="wednesday" class="day-card">
    <div class="day-head">
      <span class="badge">Wednesday</span>
      <div class="date">November 26, 2025</div>
    </div>
    <ul class="agenda">
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Opening & Introduction</h4></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Keynote 3</h4></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Coffee Break, Demos & Poster Session</h4></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Parallel Paper Sessions</h4><p>Session 6 & Session 7</p></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Lunch</h4></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Parallel Paper Sessions</h4><p>Session 8 & Session 9</p></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Coffee Break, Demos & Poster Session</h4></div></li>
      <li class="agenda-item"><span class="agenda-dot"></span><div class="agenda-card"><h4>Closing</h4></div></li>
    </ul>
  </section>

</div>
