---
layout: home
title: Registration
permalink: /registration
---

<style>
  :root{
    --ink:#0a1133;
    --muted:#475467;
    --bg:#f6f8fc;
    --card:#ffffff;
    --soft:#edf5ff;
    --accent:#0e1b4d;      /* ICSOB blue */
    --accent-2:#4f7cff;
    --ok:#0e8f86;
    --warn:#b54708;
    --shadow:0 10px 28px rgba(10,22,70,.08);
    --radius:18px;
  }

  body{font-family: Arial, system-ui, Segoe UI, Roboto, sans-serif; color:var(--ink); background:var(--bg); margin:0}
  .container{max-width:1100px; margin:0 auto; padding:24px}
  .hero{
    background: linear-gradient(180deg,#0e1b4d 0%, #1f3a93 80%);
    color:#fff; padding:56px 20px; border-radius:0 0 28px 28px; box-shadow:var(--shadow)
  }
  .hero h1{margin:0; font-size: clamp(28px, 4.2vw, 44px)}
  .hero p{margin:10px 0 0; opacity:.95}

  .grid{display:grid; grid-template-columns: 2fr 1fr; gap:22px; margin-top:22px}
  @media (max-width: 900px){ .grid{grid-template-columns:1fr} }

  .card{background:var(--card); border:1px solid #e3e9fc; border-radius:var(--radius); box-shadow:var(--shadow)}
  .card h2{margin:0; padding:18px 22px; font-size:22px; color:var(--accent); border-bottom:1px solid #e3e9fc; background:linear-gradient(90deg,#eaf2ff,#e6f0ff)}
  .card .body{padding:18px 22px}

  /* Pricing table */
  .price-table{width:100%; border-collapse:separate; border-spacing:0}
  .price-table thead th{
    background:#0e1b4d; color:#fff; text-align:left; padding:14px; font-size:14px;
  }
  .price-table thead th:nth-child(2),
  .price-table thead th:nth-child(3){text-align:right}
  .price-table tbody td{padding:14px; border-bottom:1px solid #eef2ff}
  .price-table tbody td:nth-child(2),
  .price-table tbody td:nth-child(3){text-align:right; font-weight:700}
  .price-table tbody tr:hover{background:#f7faff}
  .price-note{font-size:12px; color:var(--muted); margin-top:10px}

  .badge{display:inline-block; padding:6px 10px; border-radius:999px; font-size:12px; font-weight:800}
  .badge-eb{background:#e6f0ff; color:#0e1b4d; border:1px solid #cdd9ff}
  .badge-std{background:#eafaf9; color:#0e8f86; border:1px solid #c2efe9}

  /* Buttons */
  .btn{
    display:inline-flex; align-items:center; justify-content:center; gap:10px;
    text-decoration:none; font-weight:800; border-radius:12px; padding:14px 18px;
    border:2px solid #cdd9ff; background:#fff; color:#0e1b4d; box-shadow:var(--shadow)
  }
  .btn:hover{border-color:#8fa7ff}
  .btn-primary{
    background:#0e1b4d; color:#fff; border-color:#0e1b4d;
  }
  .btn-primary:hover{filter:brightness(1.05)}
  .btn-ghost{background:#fff}
  .btn-disabled{opacity:.55; pointer-events:none}

  .muted{color:var(--muted)}
  .list{margin:0; padding-left:18px}
  .list li{margin:8px 0}

  /* Extra pages box */
  .extras{display:grid; gap:12px}
  .extras .opt{
    display:flex; align-items:center; justify-content:space-between; gap:12px;
    border:1px solid #e3e9fc; border-radius:12px; padding:12px 14px; background:#fff;
  }

  /* Alerts / banners */
  .banner{
    background:#fff; border:1px dashed #cdd9ff; border-radius:12px; padding:12px 14px; margin-bottom:16px;
  }
</style>

<div class="hero">
  <div class="container">
    <h1>Registration</h1>
    <p>Register to join ICSOB 2025 in Stuttgart. Early-bird and standard rates are listed below.</p>
  </div>
</div>

<div class="container">
  <div class="banner">
    <strong>Status:</strong> Registration will open soon. The button will activate once the payment portal is live.
  </div>

  <div class="grid">

    <!-- Pricing -->
    <section class="card">
      <h2>Conference Fees</h2>
      <div class="body">
        <table class="price-table" aria-describedby="price-notes">
          <thead>
            <tr>
              <th>Category</th>
              <th>Early Bird <span class="badge badge-eb">**</span></th>
              <th>Standard <span class="badge badge-std">***</span></th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>Student, Full conference</td>
              <td>625,00&nbsp;€</td>
              <td>735,00&nbsp;€</td>
            </tr>
            <tr>
              <td>Regular, Full conference</td>
              <td>735,00&nbsp;€</td>
              <td>850,00&nbsp;€</td>
            </tr>
            <tr>
              <td>Student, only PhD retreat</td>
              <td>200,00&nbsp;€</td>
              <td>200,00&nbsp;€</td>
            </tr>
            <tr>
              <td>Workshop only (1-day)</td>
              <td>300,00&nbsp;€</td>
              <td>300,00&nbsp;€</td>
            </tr>
            <tr>
              <td>Workshop and dinner</td>
              <td>400,00&nbsp;€</td>
              <td>400,00&nbsp;€</td>
            </tr>
            <tr>
              <td>Dinner <span class="muted">*</span></td>
              <td>100,00&nbsp;€</td>
              <td>100,00&nbsp;€</td>
            </tr>
          </tbody>
        </table>

        <p id="price-notes" class="price-note">
          * Optional dinner ticket (also for accompanying persons).<br>
          ** Early Bird valid until <em>t.b.a.</em><br>
          *** Standard applies after the Early-Bird deadline.
        </p>

        <!-- Primary CTA -->
        <div style="display:flex; gap:12px; flex-wrap:wrap; margin-top:14px;">
          <a class="btn btn-primary btn-disabled" href="#" aria-disabled="true">Register (opens soon)</a>
          <a class="btn btn-ghost" href="/program">View Program</a>
        </div>
      </div>
    </section>

    <!-- Extras + Policies -->
    <aside class="card">
      <h2>Extras & Policies</h2>
      <div class="body">

        <!-- Extra pages -->
        <h3 style="margin:0 0 8px; font-size:18px; color:var(--accent);">Extra Pages for Accepted Papers</h3>
        <p class="muted" style="margin-top:0">Buy additional pages for your accepted research paper.</p>

        <div class="extras">
          <div class="opt">
            <div><strong>One extra page</strong><div class="muted">100,00&nbsp;€</div></div>
            <div>
              <label><input type="radio" name="extra" onclick="setRedirectUrl('#extra1')"> Select</label>
            </div>
          </div>
          <div class="opt">
            <div><strong>Two extra pages</strong><div class="muted">200,00&nbsp;€</div></div>
            <div>
              <label><input type="radio" name="extra" onclick="setRedirectUrl('#extra2')"> Select</label>
            </div>
          </div>
          <button class="btn" style="margin-top:6px" onclick="redirectToSelected()">Proceed to payment</button>
        </div>

        <hr style="margin:18px 0; border:0; border-top:1px solid #e8eefc">

        <!-- Cancellation -->
        <h3 style="margin:0 0 8px; font-size:18px; color:var(--accent);">Cancellation Policy</h3>
        <ul class="list">
          <li>All cancellations incur a fee of <strong>150&nbsp;€</strong>.</li>
          <li>Cancellations > 1 month before the conference start: refund minus 150&nbsp;€ fee.</li>
          <li>Cancellations &lt; 1 month before the conference start: <strong>no refund</strong>.</li>
        </ul>

        <hr style="margin:18px 0; border:0; border-top:1px solid #e8eefc">

        <!-- Privacy -->
        <h3 style="margin:0 0 8px; font-size:18px; color:var(--accent);">Privacy Policy</h3>
        <p class="muted" style="margin-top:0">
          By registering you accept that your personal information will be used by the hosting organization(s) to administer the event and may be shared with service providers when necessary.
        </p>
      </div>
    </aside>

  </div>
</div>

<script>
  /* keep your simple redirect logic */
  let redirectUrl = '';
  function setRedirectUrl(url) { redirectUrl = url; }
  function redirectToSelected() {
    if (redirectUrl !== '') {
      window.location.href = redirectUrl;
    } else {
      alert('Please select an option first.');
    }
  }
</script>
