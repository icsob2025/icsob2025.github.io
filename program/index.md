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
  summary{list-style:none; padding:14px 48px 14px 16px; cursor:pointer; display:grid; grid-template-columns:110px 1fr auto; gap:12px; align-items:center; position:relative; border-radius:12px}
  summary::-webkit-details-marker{display:none}
  /* Chevron indicator */
  summary::after{content:'\203A'; position:absolute; right:14px; top:50%; transform:translateY(-50%); color:#848e9c; font-size:22px; font-weight:800; transition:transform .18s ease}
  details[open] > summary::after{transform:translateY(-50%) rotate(90deg)}
  /* Hide chevron when no dropdown body exists */
  details.slot.static > summary::after{display:none}
  summary:not(:has(+ .slot-body))::after{display:none}
  summary:hover{background:#f3f6ff}
  summary:focus-visible{outline:3px solid #c9d7ff}
  /* Static (non-expandable) cards: dim + no pointer */
  details.slot.static summary{cursor:default; opacity:.88}
  details.slot.static summary:hover{background:transparent}
  details.slot.static summary:focus-visible{outline:none}
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
  <div class="subtitle"><a class="map-link" href="https://www.openstreetmap.org/?mlat=48.778901&mlon=9.173276#map=19/48.778901/9.173276" target="_blank" rel="noopener">Address of Location </a></div>
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
      <details class="slot static" open>
        <summary>
          <div class="time">09:00-09:30</div>
          <div class="title">Walk-In & Registration (Foyer Heinrich-Meidinger-Saal)</div>
          <span class="label cozy">Welcome</span>
        </summary>
      </details>
      <details class="slot">
        <summary>
          <div class="time">09:30-10:30</div>
          <div class="title">Workshop Kick-off & Keynote</div>
          <span class="label">Tracks</span>
        </summary>
        <div class="slot-body">
          <div class="tracks one">
            <div class="track">
              <h4>Workshop 1: 3rd International Workshop on Advances in Software Intensive Startups (Room Karlsruhe)</h4>
              <ul class="papers">
                <li>Workshop start</li>
                <li>Keynote: From Paralysis to Gruenderzeit 2.0</li>
              </ul>
            </div>
          </div>
        </div>
      </details>
      <details class="slot static">
        <summary>
          <div class="time">10:30-11:00</div>
          <div class="title">Coffee Break (Foyer Heinrich-Meidinger-Saal)</div>
          <span class="label break">Break</span>
        </summary>
      </details>
      <details class="slot">
        <summary>
          <div class="time">11:00-12:00</div>
          <div class="title">Late Morning Sessions</div>
          <span class="label">Tracks</span>
        </summary>
        <div class="slot-body">
          <div class="tracks one">
            <div class="track">
              <h4>Workshop 1: Book Chapter Presentations (Room Karlsruhe)</h4>
              <ul class="papers">
                <li>Do Agile Practices Inhibit Innovation?</li>
                <li>Designing a SaaS Pricing Strategy Canvas: Guiding Startups Towards Structured Decision-Making</li>
                <li>From Classrooms to Social Commerce: How 5G Is Turning Educators into Software Entrepreneurs</li>
              </ul>
            </div>
          </div>
        </div>
      </details>
      <details class="slot static">
        <summary>
          <div class="time">12:00-13:00</div>
          <div class="title">Lunch (Foyer Heinrich-Meidinger-Saal)</div>
          <span class="label break">Break</span>
        </summary>
        <div class="slot-body">
          <div class="tracks three">
            <div class="track">
              <h4>PhD Retreat</h4>
              <p class="note">Opening with mentors (with lunch).</p>
            </div>
            <div class="track">
              <h4>Workshop 1: 3rd International Workshop on Advances in Software Intensive Startups</h4>
              <p class="note">lunch</p>
            </div>
          </div>
        </div>
      </details>
      <details class="slot">
        <summary>
          <div class="time">13:00-14:30</div>
          <div class="title">Early Afternoon Sessions</div>
          <span class="label">Tracks</span>
        </summary>
        <div class="slot-body">
          <div class="tracks three">
            <div class="track">
              <h4>PhD Retreat (Room Baden-Baden)</h4>
              <p class="note">3 PhD students' papers (15 min presentation + 15 min questions each)</p>
            </div>
            <div class="track">
              <h4>Workshop 1: Startups (Room Karlsruhe)</h4>
              <ul class="papers">
                <li>Interactive Session: Updating roadmap</li>
                <li>Wrap-up: next steps</li>
              </ul>
            </div>
            <div class="track">
              <h4>Workshop 2: AI-Enabled Data Trustees (Room Mannheim)</h4>
              <p class="note">Workshop 2: Focus Group </p>
            </div>
          </div>
        </div>
      </details>
      <details class="slot static">
        <summary>
          <div class="time">14:30-15:00</div>
          <div class="title">Coffee Break (Foyer Heinrich-Meidinger-Saal)</div>
          <span class="label break">Break</span>
        </summary>
      </details>
      <details class="slot">
        <summary>
          <div class="time">15:00-17:00</div>
          <div class="title">Late Afternoon Session</div>
          <span class="label cozy">PhD Retreat (Room Baden-Baden)</span>
        </summary>
        <div class="slot-body">
          <ul class="papers">
            <li>Mentor teams meet each PhD student (30 min each)</li>
            <li>Panel of all mentors with Jan as facilitator (starts 16:30)</li>
          </ul>
          <div class="track">
              <h4>Workshop 2: AI-Enabled Data Trustees (Room Mannheim)</h4>
              <p class="note">Workshop 2: AI-Service demonstration </p>
          </div>
          <p class="note">Time for hotel check-in and transfer to Restaurant Empore, Markthalle Stuttgart (Dorotheenstraße 4, 70173 Stuttgart) (self-organized) ahead of reception.</p>
        </div>
      </details>
      <details class="slot static">
        <summary>
          <div class="time">18:00-20:30</div>
          <div class="title">Welcome Reception</div>
          <span class="label social">Social</span>
        </summary>
        <div class="slot-body">
          <p class="note">
            Restaurant Empore, Markthalle Stuttgart (Dorotheenstraße 4, 70173 Stuttgart)
            <a class="map-link" href="https://www.openstreetmap.org/?mlat=48.776345&mlon=9.178927#map=19/48.776345/9.178927" target="_blank" rel="noopener">Open in OpenStreetMap</a>
          </p>
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
      <details class="slot static" open>
        <summary>
          <div class="time">08:30-09:00</div>
          <div class="title">Walk-In & Registration (Foyer Heinrich-Meidinger-Saal)</div>
          <span class="label cozy">Welcome</span>
        </summary>
      </details>
      <details class="slot static" open>
        <summary>
          <div class="time">09:00-09:15</div>
          <div class="title">Opening & Introduction (Room Karlsruhe)</div>
          <span class="label cozy">Plenary</span>
        </summary>
      </details>
      <details class="slot static" open>
        <summary>
          <div class="time">09:15-10:00</div>
          <div class="title">Keynote 1: Daniel Trabucchi: Future-Proof Your Business: Embracing Platform Thinking for Sustainable Growth (Room Karlsruhe)</div>
          <span class="label cozy">Keynote</span>
        </summary>
      </details>
      <details class="slot static">
        <summary>
          <div class="time">10:00-10:15</div>
          <div class="title">Coffee Break (Foyer Heinrich-Meidinger-Saal)</div>
          <span class="label break">Break</span>
        </summary>
      </details>
      <details class="slot">
        <summary>
          <div class="time">10:15-11:45</div>
          <div class="title">Parallel Sessions</div>
          <span class="label">Tracks 1 & 2</span>
        </summary>
        <div class="slot-body">
          <div class="tracks">
            <div class="track">
              <h4>Track 1: Data Economy: Data Practices, Spaces, and Architectures (Room Karlsruhe)</h4>
              <ul class="papers">
                <li>105: The Beauty and the Beast: Patterns and Anti-Patterns in use of Data</li>
                <li>132: What Characterizes Data Spaces in Industry 4.0? Towards a Better Understanding</li>
                <li>185: What Are Digital Identities in Practice? Initial Insight from Finnish B2B Software Companies</li>
                <li>144: Engineering Data Architectures for AI/ML Integration in Regulated Manufacturing</li>
              </ul>
            </div>
            <div class="track">
              <h4>Track 2: Security, Trust, and Ethical Practices in Software Business (Room Mannheim)</h4>
              <ul class="papers">
                <li>129: Trust in Practice: Evaluating Third-Party Software in Large Organisational Procurement</li>
                <li>146: Simulating ERP Cyber Incidents: A Serious Game for Awareness and Incident Management</li>
                <li>165: The Ethical Requirements Stack: Operationalizing Adaptive Ethical Requirements with Human-AI Collaboration and GPT-based LLMs</li>
              </ul>
            </div>
          </div>
        </div>
      </details>
      <details class="slot static">
        <summary>
          <div class="time">11:45-12:45</div>
          <div class="title">Lunch (Foyer Heinrich-Meidinger-Saal)</div>
          <span class="label break">Break</span>
        </summary>
      </details>
      <details class="slot">
        <summary>
          <div class="time">12:45-14:00</div>
          <div class="title">Parallel Sessions</div>
          <span class="label">Tracks 1 & 2</span>
        </summary>
        <div class="slot-body">
          <div class="tracks">
            <div class="track">
              <h4>Track 1: AI Adoption and Governance in Software Organizations (Room Karlsruhe)</h4>
              <ul class="papers">
                <li>161: Cost of Not Investing (CONI) in Intelligent Processes Automation</li>
                <li>174: Understanding Organizational Decision to Adopt AI Technologies: A Qualitative Study</li>
                <li>148: Investigating Generative AI's Impact on Software Organizations' Security Practices: A Multi-Case Study Using Gioia Methodology</li>
              </ul>
            </div>
            <div class="track">
              <h4>Track 2: Sustainable and Responsible Software and Reporting (Room Mannheim)</h4>
              <ul class="papers">
                <li>154: Recommended Features for Digital Reporting Systems to Support Emissions Disclosures for Small and Medium-Sized Enterprises</li>
                <li>166: A Thematic Analysis of Environmental Sustainability in Software-Intensive Business: Understanding Practices, Barriers, and Benefits</li>
                <li>126: Design Principles for IT-Driven Circular Economy Initiatives</li>
              </ul>
            </div>
          </div>
        </div>
      </details>
      <details class="slot static">
        <summary>
          <div class="time">14:00-14:30</div>
          <div class="title">Coffee Break, Demos & Poster Session (Foyer Heinrich-Meidinger-Saal)</div>
          <span class="label break">Break</span>
        </summary>
      </details>
      <details class="slot">
        <summary>
          <div class="time">14:30-16:00</div>
          <div class="title">Parallel Sessions</div>
          <span class="label">Tracks 1 & 2</span>
        </summary>
        <div class="slot-body">
          <div class="tracks">
            <div class="track">
              <h4>Track 1: GenAI for Software Engineering and Education (Room Karlsruhe)</h4>
              <ul class="papers">
                <li>134: Comparative Analysis of Generative AI Performance in University Programming Courses</li>
                <li>170: Enhancing Agile Workflows with AI-Driven, Sustainability-Aware Requirements Engineering: A Design Science Approach</li>
                <li>141: Narrative AI Strategies for Media, Ethics and Higher Education: Impulse Perspectives from Practice Based Media Education</li>
              </ul>
            </div>
            <div class="track">
              <h4>Track 2: Digital Strategy, Enterprise Architecture, and Value Networks (Room Mannheim)</h4>
              <ul class="papers">
                <li>173: Active Personas for Synthetic User Feedback</li>
                <li>163: Transitioning Towards Enterprise Architecture Management in a Software and Service Mobility Company: A Case Study</li>
                <li>184: A Software-Driven Approach to Model, Simulate and Optimize Service-Oriented Value Creation</li>
              </ul>
            </div>
          </div>
        </div>
      </details>
      <details class="slot">
        <summary>
          <div class="time">16:15-19:15</div>
          <div class="title">Excursions</div>
          <span class="label social">Off-site</span>
        </summary>
        <div class="slot-body">
          <div class="tracks">
            <div class="track">
              <h4>Ex 1: IBM / Quantum Computing</h4>
              <ul class="papers">
                <li>16:15-17:00 transfer</li>
                <li>17:00-18:45 tour</li>
                <li>18:45-19:30 transfer</li>
              </ul>
            </div>
            <div class="track">
              <h4>Ex 2: Computer Museum</h4>
              <ul class="papers">
                <li>17:30-18:00 transfer</li>
                <li>18:00-19:00 tour</li>
                <li>19:00-19:30 transfer</li>
              </ul>
            </div>
          </div>
          <p class="note">Bus for Excursion 1 leaves early (longer drive).</p>
        </div>
      </details>
      <details class="slot">
        <summary>
          <div class="time">19:15-22:00</div>
          <div class="title">Dinner, Entertaining Keynote 2 & Awards</div>
          <span class="label social">Social</span>
        </summary>
        <div class="slot-body">
          <p class="note">
            Restaurant Leonhardts, Fernsehturm Stuttgart (Jahnstraße 120, 70597 Stuttgart)
            <a class="map-link" href="https://www.openstreetmap.org/?mlat=48.755774&mlon=9.189676#map=19/48.755774/9.189676" target="_blank" rel="noopener">Open in OpenStreetMap</a>
          </p>
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
      <details class="slot static" open>
        <summary>
          <div class="time">09:00-09:15</div>
          <div class="title">Opening & Introduction (Room Karlsruhe)</div>
          <span class="label cozy">Plenary</span>
        </summary>
      </details>
      <details class="slot static" open>
        <summary>
          <div class="time">09:15-10:00</div>
          <div class="title">Keynote 3: Rose Sturm (Room Karlsruhe)</div>
          <span class="label cozy">Keynote</span>
        </summary>
      </details>
      <details class="slot static">
        <summary>
          <div class="time">10:00-10:30</div>
          <div class="title">Coffee Break, Demos & Poster Session (Foyer Heinrich-Meidinger-Saal)</div>
          <span class="label break">Break</span>
        </summary>
      </details>
      <details class="slot">
        <summary>
          <div class="time">10:30-12:30</div>
          <div class="title">Best Paper Session (Room Karlsruhe)</div>
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
      <details class="slot static">
        <summary>
          <div class="time">12:30-13:30</div>
          <div class="title">Lunch (Foyer Heinrich-Meidinger-Saal)</div>
          <span class="label break">Break</span>
        </summary>
      </details>
      <details class="slot">
        <summary>
          <div class="time">13:30-15:00</div>
          <div class="title">Parallel Sessions</div>
          <span class="label">Tracks 1 & 2</span>
        </summary>
        <div class="slot-body">
          <div class="tracks">
          <div class="track">
              <h4>Track 2: Human-Centered and Socially Responsible Software Business (Room Mannheim)</h4>
              <ul class="papers">
                <li>142: Balancing Power and Participation: Ethical Contributions to Digital Strategy Development Based on a Case Study at a Public University</li>
                <li>140: Playing Against Creative Burnout in Sprint Retrospectives: A Design Science Research Study</li>
                <li>169: Understanding consumer behavior and sustainability perception for digital technology products and services: addressing end-user unmet sustainability needs</li>
              </ul>
            </div>
            <div class="track">
              <h4>Track 1: Startups, SaaS, and Innovation Ecosystems (Room Karlsruhe)</h4>
              <ul class="papers">
                <li>176: Product Feature Prioritization in Software Startups: A Multiple Case-study on the Status Quo and Potential of AI-based Decision Support Systems</li>
                <li>156: The Finnish Way to SaaS Scaling: A Qualitative Study</li>
                <li>175: Accelerating Software-Intensive Innovation via Living Labs: Evidence from the AIAMO Project</li>
              </ul>
            </div>
          </div>
        </div>
      </details>
      <details class="slot static">
        <summary>
          <div class="time">15:00-15:15</div>
          <div class="title">Coffee Break, Demos & Poster Session (Foyer Heinrich-Meidinger-Saal)</div>
          <span class="label break">Break</span>
        </summary>
      </details>
      <details class="slot static">
        <summary>
          <div class="time">15:15-15:45</div>
          <div class="title">Closing (Room Karlsruhe)</div>
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
