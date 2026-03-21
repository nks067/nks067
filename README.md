---
layout: default
title: Nilesh Kumar — Senior Software Engineer
---

<style>
  :root {
    --ink: #0f0f0f;
    --muted: #555;
    --accent: #1a56db;
    --tag-bg: #eef2ff;
    --tag-color: #3b4fcf;
    --border: #e0e0e0;
    --bg: #fafafa;
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: 'Georgia', serif;
    background: var(--bg);
    color: var(--ink);
    max-width: 780px;
    margin: 0 auto;
    padding: 3rem 1.5rem;
    line-height: 1.7;
  }

  /* ── HEADER ── */
  .header { border-bottom: 2px solid var(--ink); padding-bottom: 1.5rem; margin-bottom: 2rem; }
  .header h1 { font-size: 2.6rem; letter-spacing: -0.03em; font-weight: 700; }
  .header .title { font-size: 1.05rem; color: var(--accent); font-style: italic; margin: 0.25rem 0 0.75rem; }
  .header .contact { display: flex; flex-wrap: wrap; gap: 0.6rem 1.5rem; font-size: 0.85rem; color: var(--muted); }
  .header .contact a { color: var(--accent); text-decoration: none; }
  .header .contact a:hover { text-decoration: underline; }

  /* ── SECTIONS ── */
  section { margin-bottom: 2.5rem; }
  h2 {
    font-size: 0.7rem; letter-spacing: 0.18em; text-transform: uppercase;
    color: var(--muted); border-bottom: 1px solid var(--border);
    padding-bottom: 0.4rem; margin-bottom: 1.2rem;
  }

  /* ── EXPERIENCE ── */
  .job { margin-bottom: 1.6rem; }
  .job-header { display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; gap: 0.2rem; }
  .job-header h3 { font-size: 1rem; font-weight: 700; }
  .job-header .company { font-size: 0.95rem; color: var(--accent); font-style: italic; }
  .job-header .period { font-size: 0.8rem; color: var(--muted); white-space: nowrap; }
  .job ul { margin: 0.6rem 0 0.6rem 1.2rem; }
  .job ul li { font-size: 0.92rem; margin-bottom: 0.3rem; color: #333; }

  /* ── TAGS ── */
  .tags { display: flex; flex-wrap: wrap; gap: 0.35rem; margin-top: 0.5rem; }
  .tag {
    background: var(--tag-bg); color: var(--tag-color);
    font-size: 0.72rem; padding: 0.2rem 0.6rem; border-radius: 3px;
    font-family: 'Courier New', monospace; letter-spacing: 0.02em;
  }

  /* ── SKILLS GRID ── */
  .skills-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); gap: 1rem; }
  .skill-group h4 { font-size: 0.72rem; letter-spacing: 0.12em; text-transform: uppercase; color: var(--muted); margin-bottom: 0.4rem; }
  .skill-group .tags { margin-top: 0; }

  /* ── EDUCATION ── */
  .edu-item { margin-bottom: 1rem; }
  .edu-item h3 { font-size: 0.97rem; font-weight: 700; }
  .edu-item p { font-size: 0.87rem; color: var(--muted); }

  /* ── FOOTER ── */
  footer { border-top: 1px solid var(--border); padding-top: 1rem; font-size: 0.8rem; color: var(--muted); text-align: center; }
  footer a { color: var(--accent); }

  @media (max-width: 540px) {
    .header h1 { font-size: 2rem; }
    .job-header { flex-direction: column; }
  }
</style>

<div class="header">
  <h1>Nilesh Kumar</h1>
  <p class="title">Senior Associate · Morgan Stanley &nbsp;|&nbsp; Backend & Distributed Systems</p>
  <div class="contact">
    <span>📍 Bangalore, India</span>
    <a href="mailto:nileshsingh067@gmail.com">nileshsingh067@gmail.com</a>
    <a href="tel:+919457240028">+91-9457240028</a>
    <a href="https://github.com/Nilesh-Kumar" target="_blank">GitHub</a>
    <a href="https://linkedin.com/in/Nilesh-Kumar" target="_blank">LinkedIn</a>
  </div>
</div>

---

<section>
<h2>Experience</h2>

<div class="job">
  <div class="job-header">
    <span><h3>Senior Associate</h3>&nbsp;<span class="company">Morgan Stanley</span></span>
    <span class="period">Mar 2023 — Present</span>
  </div>
  <ul>
    <li>Working as part of the FIDCOM team on fixed income & currency products.</li>
    <li>Built <strong>Restricted FX</strong> — an internal platform for the foreign exchange market.</li>
  </ul>
  <div class="tags">
    <span class="tag">Java</span><span class="tag">Spring Boot</span><span class="tag">Kafka</span>
  </div>
</div>

<div class="job">
  <div class="job-header">
    <span><h3>Software Development Engineer II</h3>&nbsp;<span class="company">Amazon</span></span>
    <span class="period">Oct 2022 — Mar 2023</span>
  </div>
  <ul>
    <li>Member of the <strong>UTR Automation</strong> team, automating operations at Amazon delivery stations.</li>
    <li>Contributed to <strong>Scanless 2.0</strong> to eliminate vendor dependency on legacy scanning hardware.</li>
    <li>Led a POC with Intel RealSense depth cameras to improve packet stow accuracy.</li>
  </ul>
  <div class="tags">
    <span class="tag">Java</span><span class="tag">AWS Greengrass</span>
  </div>
</div>

<div class="job">
  <div class="job-header">
    <span><h3>Software Development Engineer I</h3>&nbsp;<span class="company">Tesco Bengaluru</span></span>
    <span class="period">Sep 2020 — Oct 2022</span>
  </div>
  <ul>
    <li>Worked on the <strong>Stored Value Points</strong> team managing Clubcard for 50M+ users.</li>
    <li>Designed and developed microservices to migrate legacy systems to a strategic cloud-based platform.</li>
    <li>Implemented fully CI/CD model for all microservices via Pipeline as Code.</li>
    <li>Designed a housekeeping mechanism for Couchbase documents to achieve optimal database performance.</li>
  </ul>
  <div class="tags">
    <span class="tag">Java</span><span class="tag">Elixir</span><span class="tag">Kafka</span><span class="tag">Couchbase</span><span class="tag">Azure</span>
  </div>
</div>

<div class="job">
  <div class="job-header">
    <span><h3>Software Engineer Intern</h3>&nbsp;<span class="company">Tesco Bengaluru</span></span>
    <span class="period">Jan 2020 — Jun 2020</span>
  </div>
  <ul>
    <li>Worked on an order optimization problem across E2E supply chain cost factors for stores and distribution.</li>
    <li>Formulated an objective function to minimize cost while outputting fuller trucks leaving warehouses.</li>
  </ul>
</div>

<div class="job">
  <div class="job-header">
    <span><h3>Software Engineer Intern</h3>&nbsp;<span class="company">Endurance International Group (Directi)</span></span>
    <span class="period">May 2019 — Jul 2019</span>
  </div>
</div>

<div class="job">
  <div class="job-header">
    <span><h3>Software Engineer</h3>&nbsp;<span class="company">Digivive Service Pvt Ltd.</span></span>
    <span class="period">Mar 2018 — Jul 2018</span>
  </div>
  <ul>
    <li>Built subscription management for an OTT platform including media streaming workflows.</li>
    <li>Implemented plug-and-play architecture for integrating multiple payment channels (telecom gateways, digital wallets) with the subscription engine.</li>
  </ul>
  <div class="tags">
    <span class="tag">Spring Boot</span><span class="tag">MongoDB</span>
  </div>
</div>

<div class="job">
  <div class="job-header">
    <span><h3>Software Engineer</h3>&nbsp;<span class="company">Jiffy Software Solutions Pvt. Ltd.</span></span>
    <span class="period">Nov 2015 — May 2017</span>
  </div>
  <ul>
    <li>Built a CMS for bulk and single content upload for VAS products.</li>
    <li>Integrated multiple national and international telecom operator charging gateways.</li>
    <li>Created a standalone multithreaded service for active customer base renewal.</li>
  </ul>
  <div class="tags">
    <span class="tag">J2EE</span><span class="tag">MySQL</span><span class="tag">AWS</span>
  </div>
</div>

</section>

---

<section>
<h2>Skills</h2>
<div class="skills-grid">
  <div class="skill-group">
    <h4>Languages</h4>
    <div class="tags">
      <span class="tag">Java</span><span class="tag">J2EE</span><span class="tag">Elixir</span>
    </div>
  </div>
  <div class="skill-group">
    <h4>Frameworks</h4>
    <div class="tags">
      <span class="tag">Spring Boot</span><span class="tag">Micronaut</span>
    </div>
  </div>
  <div class="skill-group">
    <h4>Databases</h4>
    <div class="tags">
      <span class="tag">MySQL</span><span class="tag">Couchbase</span><span class="tag">MongoDB</span>
    </div>
  </div>
  <div class="skill-group">
    <h4>Cloud & Infra</h4>
    <div class="tags">
      <span class="tag">AWS</span><span class="tag">Azure</span><span class="tag">Docker</span><span class="tag">Kubernetes</span>
    </div>
  </div>
  <div class="skill-group">
    <h4>Messaging & Observability</h4>
    <div class="tags">
      <span class="tag">Kafka</span><span class="tag">Splunk</span>
    </div>
  </div>
  <div class="skill-group">
    <h4>DevOps & OS</h4>
    <div class="tags">
      <span class="tag">Jenkins</span><span class="tag">Azure DevOps</span><span class="tag">Linux</span>
    </div>
  </div>
</div>
</section>

---

<section>
<h2>Education</h2>

<div class="edu-item">
  <h3>M.Tech in Computer Science & Engineering</h3>
  <p>IIIT Bangalore &nbsp;·&nbsp; 2018–2020 &nbsp;·&nbsp; CGPA: 3.19 / 4.0</p>
</div>

<div class="edu-item">
  <h3>B.Tech in Computer Science & Engineering</h3>
  <p>Dr. A.P.J. Abdul Kalam Technical University, Lucknow &nbsp;·&nbsp; 2012–2016 &nbsp;·&nbsp; 69.4%</p>
</div>

</section>

---

<footer>
  Built with GitHub Pages &nbsp;·&nbsp;
  <a href="mailto:nileshsingh067@gmail.com">nileshsingh067@gmail.com</a>
</footer>
