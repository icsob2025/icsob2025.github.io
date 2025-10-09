---
layout: home
title: Registration
permalink: /registration/
---

<style>
  :root{
    --ink:#0a1133;
    --muted:#475467;
    --bg:#f6f8fc;
    --card:#ffffff;
    --accent:#0e1b4d;      /* ICSOB blue */
    --accent-2:#4f7cff;
    --shadow:0 10px 25px rgba(10,22,70,.08);
    --radius:18px;
  }
  
  body{font-family: Arial, system-ui, sans-serif; color:var(--ink); background:var(--bg); margin:0}
  .container{max-width:1100px; margin:0 auto; padding:24px}
  .hero{background: linear-gradient(180deg,#0e1b4d 0%, #1f3a93 80%); color:#fff; padding:56px 20px; border-radius:0 0 28px 28px; box-shadow:var(--shadow)}
  .hero h1{margin:0; font-size:clamp(28px, 4vw, 44px)}
  .hero p{margin:10px 0 0; opacity:.95}

  /* CTA button */
  .hero .cta{ text-align:center; margin-top:24px }
  .register-btn{
    display:inline-block;
    padding:14px 24px;
    border-radius:12px;
    background: linear-gradient(90deg, var(--accent-2), #6b95ff);
    color:#fff;
    text-decoration:none;
    font-weight:700;
    letter-spacing:.2px;
    box-shadow: 0 0 0 3px rgba(255,255,255,.16), 0 10px 22px rgba(79,124,255,.35);
    border:1px solid rgba(255,255,255,.18);
    transition: transform .15s ease, box-shadow .2s ease, filter .2s ease;
  }
  .register-btn:hover{
    transform: translateY(-1px);
    box-shadow: 0 0 0 3px rgba(255,255,255,.22), 0 12px 26px rgba(79,124,255,.45);
    filter: brightness(1.03);
  }

  .card{background:var(--card); border:1px solid #e3e9fc; border-radius:var(--radius); box-shadow:var(--shadow); margin:22px 0}
  .card h2{margin:0; padding:18px 22px; font-size:22px; color:var(--accent); border-bottom:1px solid #e3e9fc; background:linear-gradient(90deg,#eaf2ff,#e6f0ff)}
  .card .body{padding:18px 22px}

  /* Pricing table */
  .price-table{width:100%; border-collapse:collapse}
  .price-table thead th{background:#0e1b4d; color:#fff; text-align:left; padding:14px; font-size:14px}
  .price-table thead th:nth-child(2), .price-table thead th:nth-child(3){text-align:right}
  .price-table tbody td{padding:12px; border-bottom:1px solid #eef2ff}
  .price-table tbody td:nth-child(2), .price-table tbody td:nth-child(3){text-align:right; font-weight:600}
  .price-table tbody tr:hover{background:#f7faff}
  .price-note{font-size:12px; color:var(--muted); margin-top:10px}

  .muted{color:var(--muted)}
  .list{margin:0; padding-left:18px}
  .list li{margin:6px 0}
</style>

<div class="hero">
  <div class="container">
    <h1>Registration</h1>
    <p>Information about fees, extra pages, and policies. Registration and payment will be handled via our external provider</p>
  </div>
  <div class="cta">
    <a class="register-btn" href="https://eveeno.com/288682045" target="_blank" rel="noopener">Register now →</a>
  </div>
</div>

<div class="container">

  <!-- Fees -->
  <section class="card">
    <h2>Conference Fees</h2>
    <div class="body">
      <table class="price-table" aria-describedby="price-notes">
        <thead>
          <tr>
            <th>Category</th>
            <th>Early Bird <span class="muted">**</span></th>
            <th>Standard <span class="muted">***</span></th>
          </tr>
        </thead>
        <tbody>
          <tr><td>Student, Full conference</td><td>625,00&nbsp;€</td><td>735,00&nbsp;€</td></tr>
          <tr><td>Regular, Full conference</td><td>735,00&nbsp;€</td><td>850,00&nbsp;€</td></tr>
          <tr><td>Student, only PhD retreat</td><td>200,00&nbsp;€</td><td>200,00&nbsp;€</td></tr>
          <tr><td>Workshop only (1-day)</td><td>300,00&nbsp;€</td><td>300,00&nbsp;€</td></tr>
          <tr><td>Workshop and dinner</td><td>400,00&nbsp;€</td><td>400,00&nbsp;€</td></tr>
          <tr><td>Dinner <span class="muted">*</span></td><td>119,00&nbsp;€</td><td>119,00&nbsp;€</td></tr>
        </tbody>
      </table>
      <p id="price-notes" class="price-note">
        * Optional dinner ticket (also for accompanying persons).<br>
        ** Early Bird valid until 23.10.2025<br>
        *** Standard applies after the Early Bird deadline.
      </p>
    </div>
  </section>

  <!-- Extra pages -->
  <section class="card">
    <h2>Extra Pages for Accepted Papers</h2>
    <div class="body">
      <p>We also offer the possibility of buying extra pages for your accepted research paper:</p>
      <ul class="list">
        <li>100 € for one extra page</li>
        <li>200 € for two extra pages</li>
      </ul>
    </div>
  </section>

  <!-- Cancellation -->
  <section class="card">
    <h2>Cancellation Policy</h2>
    <div class="body">
      <ul class="list">
        <li>All cancellations incur a fee of <strong>150&nbsp;€</strong>.</li>
        <li>Cancellations made more than one month before the conference start: refund minus the cancellation fee.</li>
        <li>Cancellations made less than one month before the conference start: <strong>no refund</strong>.</li>
      </ul>
    </div>
  </section>

  <!-- Privacy -->
  <section class="card">
    <h2>Privacy Policy</h2>
    <div class="body">
      <p class="muted">
        By registering you accept that your personal information will be used by the hosting organization(s) to administer the event and may be shared with service providers when necessary.
      </p>
    </div>
  </section>

</div>
