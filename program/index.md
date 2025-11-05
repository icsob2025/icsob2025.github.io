---
layout: home
title: Conference Program
permalink: /program
---

<style>
  :root{
    --ink:#0b1026;
    --muted:#4a536b;
    --card:#ffffff;
    --bg:#f6f8fc;
    --accent:#0e1b4d;
    --accent-2:#0ea89e;
    --accent-3:#ff7a59;
    --shadow:0 12px 28px rgba(10,22,70,.08);
    --radius:16px;
  }
  body{font-family:Inter, ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif; color:var(--ink); background:var(--bg)}
  .container{max-width:1100px; margin:0 auto; padding:24px}

  /* Hero */
  .title-wrap{position:relative; overflow:hidden; background:linear-gradient(160deg,#0e1b4d 0%, #1e3a8a 60%, #0ea89e 120%); color:#fff; padding:56px 20px; border-radius:0 0 28px 28px; box-shadow:var(--shadow); text-align:center}
  .title-wrap h1{margin:0; font-size:clamp(28px, 4vw, 44px)}
  .subtitle{opacity:.95; margin-top:10px; font-size:clamp(14px, 2vw, 18px)}
  .hint{display:inline-block; margin-top:14px; background:rgba(255,255,255,.16); padding:8px 12px; border-radius:999px; font-size:14px}

  /* Top controls */
  .controls{display:flex; gap:10px; justify-content:center; flex-wrap:wrap; margin:22px auto}
  .btn{cursor:pointer; border:2px solid #d8e0f5; background:#fff; color:var(--accent); padding:10px 16px; border-radius:999px; font-weight:700; box-shadow:0 5px 10px rgba(10,22,70,.06); transition:all .15s ease}
  .btn:hover{background:var(--accent); color:#fff; border-color:var(--accent)}
  .btn.alt{color:#fff; background:var(--accent-2); border-color:transparent}

  /* Day navigation */
  .day-nav{position:sticky; top:0; z-index:10; padding:10px 12px; background:rgba(246,248,252,.9); backdrop-filter:saturate(180%) blur(8px); border-bottom:1px solid #e6ecff}
  .day-nav .wrap{display:flex; justify-content:center; gap:10px; flex-wrap:wrap}
  .day-nav a{ text-decoration:none; background:#fff; border:1px solid #dfe6ff; color:var(--accent); font-weight:700; padding:8px 14px; border-radius:999px; transition:.15s; box-shadow:0 4px 8px rgba(10,22,70,.05)}
  .day-nav a:hover{background:var(--accent); color:#fff; border-color:var(--accent)}

  /* Day cards */
  .day-card{background:var(--card); border:1px solid #e6ecff; border-radius:var(--radius); box-shadow:var(--shadow); margin:26px 0; overflow:hidden}
  .day-head{padding:18px 22px; background:linear-gradient(90deg,#eaf2ff,#e6f5ff); border-bottom:1px solid #dfe6ff; display:flex; justify-content:space-between; align-items:center}
  .badge{background:#0e1b4d; color:#fff; font-weight:800; padding:6px 12px; border-radius:999px; font-size:14px}
  .badge.green{background:var(--accent-2)}
  .badge.orange{background:var(--accent-3)}
  .date{font-weight:800; color:#0e1b4d}

  /* Slot / accordion */
  .slots{padding:12px}
  details.slot{border:1px solid #e8ecf9; border-radius:14px; background:#fff; margin:12px; box-shadow:0 6px 14px rgba(10,22,70,.05); overflow:hidden}
  details.slot[open]{box-shadow:0 10px 22px rgba(10,22,70,.09)}
  summary{list-style:none; padding:14px 44px 14px 16px; cursor:pointer; display:grid; grid-template-columns:110px 1fr auto; gap:12px; align-items:center; position:relative; border-radius:12px}
  summary::-webkit-details-marker{display:none}
  /* Chevron indicator */
  summary::after{content:'\25B8'; /* ▸ */ position:absolute; right:14px; top:50%; transform:translateY(-50%); color:#6c7cff; font-size:18px; font-weight:800; transition:transform .18s ease,color .18s ease}
  details[open] > summary::after{transform:translateY(-50%) rotate(90deg); color:var(--accent-2)}
  summary:hover{background:#f3f6ff}
  summary:focus-visible{outline:3px solid #c9d7ff}
  .time{font-weight:800; color:var(--accent)}
  .title{font-weight:800}
  .label{font-size:12px; font-weight:800; color:#fff; padding:4px 8px; border-radius:999px; background:var(--accent-2)}
  .label.cozy{background:#6c7cff}
  .label.break{background:#ffb14f}
  .label.social{background:#ef476f}

  .slot-body{padding:0 16px 16px}
  .tracks{display:grid; grid-template-columns:repeat(2,1fr); gap:16px}
  .tracks.three{grid-template-columns:repeat(3,1fr)}
  .track{border:1px solid #ecf0fb; border-radius:12px; padding:12px; background:#fbfdff}
  .track h4{margin:0 0 8px; color:var(--accent); font-size:16px}
  .papers{margin:0; padding-left:16px; font-size:14px}
  .papers li{margin:6px 0}
  .note{color:var(--muted); font-size:14px}

  /* Mobile tweaks */
  @media (max-width: 820px){
    summary{grid-template-columns:86px 1fr auto}
    .tracks, .tracks.three{grid-template-columns:1fr}
  }
</style>

<div class="title-wrap">
  <h1>Conference Program</h1>
  <div class="subtitle">Tap a slot to see details. All times local.</div>
  <div class="controls">
    <button class="btn" id="expandAll">Expand all</button>
    <button class="btn alt" id="collapseAll">Collapse all</button>
  </div>
</div>

<nav class="day-nav">
  <div class="wrap">
    <a href="#monday">Mon 24.11</a>
    <a href="#tuesday">Tue 25.11</a>
    <a href="#wednesday">Wed 26.11</a>
  </div>
  </nav>

<div class="container">

  <!-- Monday -->
  <section id="monday" class="day-card">
    <div class="day-head">
      <span class="badge">Monday</span>
      <div class="date">24 November 2025</div>
    </div>
    <div class="slots">
      <details class="slot" open>
        <summary>
          <div class="time">09:00–09:30</div>
          <div class="title">Walk‑In & Registration</div>
          <span class="label cozy">Welcome</span>
        </summary>
      </details>

      <details class="slot">
        <summary>
          <div class="time">09:30–10:30</div>
          <div class="title">Morning Sessions</div>
          <span class="label">Tracks</span>
        </summary>
        <div class="slot-body">
          <div class="tracks three">
            <div class="track">
              <h4>PhD Retreat</h4>
              <p class="note">Group activities and mentoring.</p>
            </div>
            <div class="track">
              <h4>3rd International Workshop on Advances in Software Intensive Startups</h4>
              <p class="note">Talks and discussions.</p>
            </div>
            <div class="track">
              <h4>1st International Workshop on AI‑Enabled Data Trustees</h4>
              <p class="note">Talks and discussions.</p>
            </div>
          </div>
        </div>
      </details>

      <details class="slot">
        <summary>
          <div class="time">10:30–11:00</div>
          <div class="title">Coffee Break</div>
          <span class="label break">Break</span>
        </summary>
      </details>

      <details class="slot">
        <summary>
          <div class="time">11:00–12:00</div>
          <div class="title">Late Morning Sessions</div>
          <span class="label">Tracks</span>
        </summary>
        <div class="slot-body">
          <div class="tracks three">
            <div class="track"><h4>PhD Retreat</h4></div>
            <div class="track"><h4>Software Intensive Startups Workshop</h4></div>
            <div class="track"><h4>AI‑Enabled Data Trustees Workshop</h4></div>
          </div>
        </div>
      </details>

      <details class="slot">
        <summary>
          <div class="time">12:00–13:00</div>
          <div class="title">Lunch</div>
          <span class="label break">Break</span>
        </summary>
      </details>

      <details class="slot">
        <summary>
          <div class="time">13:00–14:30</div>
          <div class="title">Early Afternoon Sessions</div>
          <span class="label">Tracks</span>
        </summary>
        <div class="slot-body">
          <div class="tracks three">
            <div class="track"><h4>PhD Retreat</h4></div>
            <div class="track"><h4>Software Intensive Startups Workshop</h4></div>
            <div class="track"><h4>AI‑Enabled Data Trustees Workshop</h4></div>
          </div>
        </div>
      </details>

      <details class="slot">
        <summary>
          <div class="time">14:30–15:00</div>
          <div class="title">Coffee Break</div>
          <span class="label break">Break</span>
        </summary>
      </details>

      <details class="slot">
        <summary>
          <div class="time">15:00–17:00</div>
          <div class="title">Afternoon Sessions</div>
          <span class="label">Tracks</span>
        </summary>
        <div class="slot-body">
          <div class="tracks three">
            <div class="track"><h4>PhD Retreat</h4></div>
            <div class="track"><h4>Software Intensive Startups Workshop</h4></div>
            <div class="track"><h4>AI‑Enabled Data Trustees Workshop</h4></div>
          </div>
        </div>
      </details>

      <details class="slot">
        <summary>
          <div class="time">—</div>
          <div class="title">Time for Hotel Check‑in & Transfer to Markthalle Stuttgart</div>
          <span class="label break">Self‑organized</span>
        </summary>
      </details>

      <details class="slot">
        <summary>
          <div class="time">18:00–20:30</div>
          <div class="title">Welcome Reception</div>
          <span class="label social">Social</span>
        </summary>
        <div class="slot-body">
          <p class="note">Restaurant Ampulle, Markthalle Stuttgart</p>
        </div>
      </details>
    </div>
  </section>

  <!-- Tuesday -->
  <section id="tuesday" class="day-card">
    <div class="day-head">
      <span class="badge green">Tuesday</span>
      <div class="date">25 November 2025</div>
    </div>
    <div class="slots">
      <details class="slot" open>
        <summary>
          <div class="time">08:30–09:00</div>
          <div class="title">Walk‑In & Registration</div>
          <span class="label cozy">Welcome</span>
        </summary>
      </details>

      <details class="slot" open>
        <summary>
          <div class="time">09:00–09:15</div>
          <div class="title">Opening & Introduction</div>
          <span class="label cozy">Plenary</span>
        </summary>
      </details>

      <details class="slot" open>
        <summary>
          <div class="time">09:15–10:00</div>
          <div class="title">Keynote 1</div>
          <span class="label cozy">Keynote</span>
        </summary>
      </details>

      <details class="slot">
        <summary>
          <div class="time">10:00–10:15</div>
          <div class="title">Coffee Break</div>
          <span class="label break">Break</span>
        </summary>
      </details>

      <details class="slot">
        <summary>
          <div class="time">10:15–11:45</div>
          <div class="title">Parallel Sessions</div>
          <span class="label">Tracks 1 & 2</span>
        </summary>
        <div class="slot-body">
          <div class="tracks">
            <div class="track">
              <h4>Track 1 — Session “Data Economy: Data Practices, Spaces, and Architectures”</h4>
              <ul class="papers">
                <li>105: The Beauty and the Beast: Patterns and Anti‑Patterns in use of Data</li>
                <li>132: What Characterizes Data Spaces in Industry 4.0? Towards a Better Understanding</li>
                <li>185: What Are Digital Identities in Practice? Initial Insight from Finnish B2B Software Companies</li>
                <li>144: Engineering Data Architectures for AI/ML Integration in Regulated Manufacturing</li>
              </ul>
            </div>
            <div class="track">
              <h4>Track 2 — Session “Security, Trust, and Ethical Practices in Software Business”</h4>
              <ul class="papers">
                <li>129: Trust in Practice: Evaluating Third‑Party Software in Large Organisational Procurement</li>
                <li>146: Simulating ERP Cyber Incidents: A Serious Game for Awareness and Incident Management</li>
                <li>165: The Ethical Requirements Stack: Operationalizing Adaptive Ethical Requirements with Human‑AI Collaboration and GPT‑based LLMs</li>
              </ul>
            </div>
          </div>
        </div>
      </details>

      <details class="slot">
        <summary>
          <div class="time">11:45–12:45</div>
          <div class="title">Lunch</div>
          <span class="label break">Break</span>
        </summary>
      </details>

      <details class="slot">
        <summary>
          <div class="time">12:45–14:00</div>
          <div class="title">Parallel Sessions</div>
          <span class="label">Tracks 1 & 2</span>
        </summary>
        <div class="slot-body">
          <div class="tracks">
            <div class="track">
              <h4>Track 1 — Session “AI Adoption and Governance in Software Organizations”</h4>
              <ul class="papers">
                <li>161: Cost of Not Investing (CONI) in Intelligent Processes Automation</li>
                <li>174: Understanding Organizational Decision to Adopt AI Technologies: A Qualitative Study</li>
                <li>148: Investigating Generative AI’s Impact on Software Organizations’ Security Practices: A Multi‑Case Study Using Gioia Methodology</li>
              </ul>
            </div>
            <div class="track">
              <h4>Track 2 — Session “Sustainable and Responsible Software and Reporting”</h4>
              <ul class="papers">
                <li>154: Recommended Features for Digital Reporting Systems to Support Emissions Disclosures for Small and Medium‑Sized Enterprises</li>
                <li>166: A Thematic Analysis of Environmental Sustainability in Software‑Intensive Business: Understanding Practices, Barriers, and Benefits</li>
                <li>126: Design Principles for IT‑Driven Circular Economy Initiatives</li>
              </ul>
            </div>
          </div>
        </div>
      </details>

      <details class="slot">
        <summary>
          <div class="time">14:00–14:30</div>
          <div class="title">Coffee Break, Demos & Poster Session</div>
          <span class="label break">Break</span>
        </summary>
      </details>

      <details class="slot">
        <summary>
          <div class="time">14:30–16:00</div>
          <div class="title">Parallel Sessions</div>
          <span class="label">Tracks 1 & 2</span>
        </summary>
        <div class="slot-body">
          <div class="tracks">
            <div class="track">
              <h4>Track 1 — Session “GenAI for Software Engineering and Education”</h4>
              <ul class="papers">
                <li>134: Comparative Analysis of Generative AI Performance in University Programming Courses</li>
                <li>170: Enhancing Agile Workflows with AI‑Driven, Sustainability‑Aware Requirements Engineering: A Design Science Approach</li>
                <li>141: Narrative AI Strategies for Media, Ethics and Higher Education – Impulse Perspectives from Practice Based Media Education</li>
              </ul>
              <p class="note">Preparation for Excursion</p>
            </div>
            <div class="track">
              <h4>Track 2 — Session “Digital Strategy, Enterprise Architecture, and Value Networks”</h4>
              <ul class="papers">
                <li>173: Active Personas for Synthetic User Feedback</li>
                <li>163: Transitioning Towards Enterprise Architecture Management in a Software and Service Mobility Company: A Case Study</li>
                <li>184: A Software‑Driven Approach to Model, Simulate and Optimize Service‑Oriented Value Creation</li>
              </ul>
            </div>
          </div>
        </div>
      </details>

      <details class="slot">
        <summary>
          <div class="time">16:15–19:15</div>
          <div class="title">Excursions</div>
          <span class="label social">Off‑site</span>
        </summary>
        <div class="slot-body">
          <div class="tracks">
            <div class="track">
              <h4>Ex 1: IBM / Quantum Computing</h4>
              <ul class="papers">
                <li>16:15–17:00 transfer</li>
                <li>17:00–18:45 tour</li>
                <li>18:45–19:30 transfer</li>
              </ul>
            </div>
            <div class="track">
              <h4>Ex 2: Computer Museum</h4>
              <ul class="papers">
                <li>17:30–18:00 transfer (via 3)</li>
                <li>18:00–19:00 tour</li>
                <li>19:00–19:30 transfer (via 3)</li>
              </ul>
            </div>
            <div class="track">
              <h4>Ex 3: Arena2036</h4>
              <ul class="papers">
                <li>17:30–17:50 transfer</li>
                <li>17:50–19:10 tour</li>
                <li>19:10–19:30 transfer</li>
              </ul>
            </div>
          </div>
        </div>
      </details>

      <details class="slot">
        <summary>
          <div class="time">19:15–22:00</div>
          <div class="title">Dinner, Entertaining Keynote 2 & Awards</div>
          <span class="label social">Social</span>
        </summary>
        <div class="slot-body">
          <p class="note">Leonhardts, Fernsehturm</p>
        </div>
      </details>
    </div>
  </section>

  <!-- Wednesday -->
  <section id="wednesday" class="day-card">
    <div class="day-head">
      <span class="badge orange">Wednesday</span>
      <div class="date">26 November 2025</div>
    </div>
    <div class="slots">
      <details class="slot" open>
        <summary>
          <div class="time">09:00–09:15</div>
          <div class="title">Opening & Introduction</div>
          <span class="label cozy">Plenary</span>
        </summary>
      </details>

      <details class="slot" open>
        <summary>
          <div class="time">09:15–10:00</div>
          <div class="title">Keynote 3</div>
          <span class="label cozy">Keynote</span>
        </summary>
      </details>

      <details class="slot">
        <summary>
          <div class="time">10:00–10:30</div>
          <div class="title">Coffee Break, Demos & Poster Session</div>
          <span class="label break">Break</span>
        </summary>
      </details>

      <details class="slot">
        <summary>
          <div class="time">10:30–12:30</div>
          <div class="title">Best Paper Session</div>
          <span class="label">Plenary</span>
        </summary>
        <div class="slot-body">
          <ul class="papers">
            <li>168: Nominee 1 (Full Paper): Practical Adoption of Green Coding in Finland and Globally</li>
            <li>130: Nominee 2 (Full Paper): Democratising Work in the Software Sector: Insights on Cooperative Businesses</li>
            <li>181: Nominee 1 (Short Paper): The Role of AI in Software Release Management</li>
            <li>159: Nominee 2 (Short Paper): Addictive UX: Heuristic Evidence from Online Gambling UX and the Need for Ethical</li>
          </ul>
        </div>
      </details>

      <details class="slot">
        <summary>
          <div class="time">12:30–13:30</div>
          <div class="title">Lunch</div>
          <span class="label break">Break</span>
        </summary>
      </details>

      <details class="slot">
        <summary>
          <div class="time">13:30–15:00</div>
          <div class="title">Parallel Sessions</div>
          <span class="label">Tracks 1 & 2</span>
        </summary>
        <div class="slot-body">
          <div class="tracks">
            <div class="track">
              <h4>Track 1 — Session “Startups, SaaS, and Innovation Ecosystems”</h4>
              <ul class="papers">
                <li>156: The Finnish Way to SaaS Scaling: A Qualitative Study</li>
                <li>176: Product Feature Prioritization in Software Startups: A Multiple Case‑study on the Status Quo and Potential of AI‑based Decision Support Systems</li>
                <li>175: Accelerating Software‑Intensive Innovation via Living Labs: Evidence from the AIAMO Project</li>
              </ul>
            </div>
            <div class="track">
              <h4>Track 2 — Session “Human‑Centered and Socially Responsible Software Business”</h4>
              <ul class="papers">
                <li>142: Balancing Power and Participation: Ethical Contributions to Digital Strategy Development Based on a Case Study at a Public University</li>
                <li>140: Playing Against Creative Burnout in Sprint Retrospectives: A Design Science Research Study</li>
                <li>169: Understanding consumer behavior and sustainability perception for digital technology products and services: addressing end‑user unmet sustainability needs</li>
              </ul>
            </div>
          </div>
        </div>
      </details>

      <details class="slot">
        <summary>
          <div class="time">15:00–15:15</div>
          <div class="title">Coffee Break, Demos & Poster Session</div>
          <span class="label break">Break</span>
        </summary>
      </details>

      <details class="slot">
        <summary>
          <div class="time">15:15–15:45</div>
          <div class="title">Closing</div>
          <span class="label cozy">Plenary</span>
        </summary>
      </details>
    </div>
  </section>

</div>

<script>
  // Expand / collapse all controls
  const expandAllBtn = document.getElementById('expandAll');
  const collapseAllBtn = document.getElementById('collapseAll');
  function allSlots(){ return Array.from(document.querySelectorAll('details.slot')); }
  if(expandAllBtn){ expandAllBtn.addEventListener('click', () => allSlots().forEach(d => d.open = true)); }
  if(collapseAllBtn){ collapseAllBtn.addEventListener('click', () => allSlots().forEach(d => d.open = false)); }
</script>
