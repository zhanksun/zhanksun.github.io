---
layout: default
title: "Homepage Preview"
permalink: /homepage-preview/
author_profile: false
sitemap: false
---

<style>
  .homepage-preview {
    max-width: 1120px;
    margin: 2.5rem auto 3rem;
    padding: 0 1rem;
    color: #202124;
  }

  .homepage-preview a {
    color: #9d2235;
    text-decoration: none;
  }

  .homepage-preview a:hover {
    text-decoration: underline;
  }

  .homepage-hero {
    display: grid;
    grid-template-columns: minmax(0, 1fr) 220px;
    gap: 2rem;
    align-items: center;
    padding-bottom: 2rem;
    border-bottom: 1px solid #e2e5e9;
  }

  .homepage-kicker {
    margin: 0 0 0.45rem;
    color: #6b7280;
    font-size: 0.9rem;
    font-weight: 700;
    text-transform: uppercase;
  }

  .homepage-hero h1 {
    margin: 0;
    color: #111827;
    font-size: 2.35rem;
    line-height: 1.1;
  }

  .homepage-roles {
    margin: 0.75rem 0 0;
    color: #374151;
    font-size: 1.05rem;
    line-height: 1.55;
  }

  .homepage-lead {
    max-width: 740px;
    margin: 1.25rem 0 0;
    color: #374151;
    font-size: 1.05rem;
    line-height: 1.65;
  }

  .homepage-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 0.7rem;
    margin-top: 1.35rem;
  }

  .homepage-actions a {
    display: inline-flex;
    align-items: center;
    min-height: 2.35rem;
    padding: 0.35rem 0.8rem;
    border: 1px solid #d6d9de;
    border-radius: 6px;
    color: #202124;
    font-size: 0.95rem;
    font-weight: 700;
  }

  .homepage-actions a.primary {
    border-color: #9d2235;
    background: #9d2235;
    color: #fff;
  }

  .homepage-photo {
    margin: 0;
  }

  .homepage-photo img {
    display: block;
    width: 220px;
    height: 246px;
    object-fit: cover;
    border-radius: 6px;
  }

  .homepage-section {
    margin-top: 2.25rem;
  }

  .homepage-section h2 {
    margin: 0 0 1rem;
    padding-bottom: 0.45rem;
    border-bottom: 1px solid #e2e5e9;
    color: #111827;
    font-size: 1.35rem;
  }

  .homepage-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 1rem;
  }

  .homepage-card {
    padding: 1rem;
    border: 1px solid #e2e5e9;
    border-radius: 6px;
    background: #fff;
  }

  .homepage-card h3 {
    margin: 0 0 0.45rem;
    color: #111827;
    font-size: 1rem;
  }

  .homepage-card p {
    margin: 0;
    color: #4b5563;
    font-size: 0.95rem;
    line-height: 1.55;
  }

  .homepage-publications {
    margin: 0;
    padding: 0;
    list-style: none;
  }

  .homepage-publications li {
    display: grid;
    grid-template-columns: 3.5rem minmax(0, 1fr);
    gap: 0.75rem;
    padding: 0.9rem 0;
    border-bottom: 1px solid #edf0f3;
  }

  .homepage-publications li:first-child {
    border-top: 1px solid #edf0f3;
  }

  .homepage-year {
    color: #6b7280;
    font-size: 0.9rem;
    font-weight: 700;
  }

  .homepage-paper-title {
    margin: 0;
    color: #111827;
    font-weight: 700;
    line-height: 1.45;
  }

  .homepage-paper-meta {
    margin: 0.2rem 0 0;
    color: #4b5563;
    font-size: 0.92rem;
    line-height: 1.45;
  }

  .homepage-bottom {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1rem;
  }

  .homepage-contact {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1rem;
    margin-top: 2.25rem;
    padding-top: 1.25rem;
    border-top: 1px solid #e2e5e9;
    color: #4b5563;
    font-size: 0.95rem;
    line-height: 1.6;
  }

  .homepage-contact p {
    margin: 0;
  }

  @media (max-width: 760px) {
    .homepage-hero,
    .homepage-grid,
    .homepage-bottom,
    .homepage-contact {
      grid-template-columns: 1fr;
    }

    .homepage-photo img {
      width: 180px;
      height: 202px;
    }

    .homepage-hero h1 {
      font-size: 2rem;
    }
  }
</style>

<main id="main" class="homepage-preview" role="main">
  <section class="homepage-hero" aria-labelledby="homepage-title">
    <div>
      <p class="homepage-kicker">Decision Analytics and Operations</p>
      <h1 id="homepage-title">Zhankun Sun</h1>
      <p class="homepage-roles">
        Associate Professor, College of Business<br>
        MBA Program Director, City University of Hong Kong
      </p>
      <p class="homepage-lead">
        I study the modeling, analysis, and control of stochastic systems, with applications in healthcare operations and smart-city logistics. My recent work focuses on emergency department patient flow, mass-casualty response, and battery swapping infrastructure.
      </p>
      <div class="homepage-actions" aria-label="Primary links">
        <a class="primary" href="/publications/">Publications</a>
        <a href="https://scholar.google.com/citations?user=uzUmqc0AAAAJ&amp;hl=en">Google Scholar</a>
        <a href="/teaching/">Teaching</a>
        <a href="/awards/">Funding &amp; Awards</a>
      </div>
    </div>
    <figure class="homepage-photo">
      <img src="/images/profile_new.jpg" width="220" height="246" alt="Zhankun Sun">
    </figure>
  </section>

  <section class="homepage-section" aria-labelledby="research-areas">
    <h2 id="research-areas">Research Areas</h2>
    <div class="homepage-grid">
      <article class="homepage-card">
        <h3>Emergency Department Operations</h3>
        <p>Patient triage, physician staffing, patient prioritization, congestion management, and operational decisions under uncertainty.</p>
      </article>
      <article class="homepage-card">
        <h3>Emergency Response Management</h3>
        <p>Decision models for mass-casualty events, austere-care settings, and time-sensitive resource allocation.</p>
      </article>
      <article class="homepage-card">
        <h3>Smart-City Logistics</h3>
        <p>Stochastic control and optimization for battery swapping stations, charging decisions, and urban mobility infrastructure.</p>
      </article>
    </div>
  </section>

  <section class="homepage-section" aria-labelledby="selected-publications">
    <h2 id="selected-publications">Selected Publications</h2>
    <ol class="homepage-publications">
      <li>
        <span class="homepage-year">2018</span>
        <div>
          <p class="homepage-paper-title"><a href="https://doi.org/10.1287/mnsc.2017.2855">Patient Triage and Prioritization Under Austere Conditions</a></p>
          <p class="homepage-paper-meta">Management Science. Featured by Management Science Review.</p>
        </div>
      </li>
      <li>
        <span class="homepage-year">2022</span>
        <div>
          <p class="homepage-paper-title"><a href="https://doi.org/10.1111/poms.13494">When to Triage in Service Systems with Hidden Customer Class Identities?</a></p>
          <p class="homepage-paper-meta">Production and Operations Management.</p>
        </div>
      </li>
      <li>
        <span class="homepage-year">2022</span>
        <div>
          <p class="homepage-paper-title"><a href="https://doi.org/10.1111/poms.13571">Scheduling of Physicians with Time-Varying Productivity Levels in Emergency Departments</a></p>
          <p class="homepage-paper-meta">Production and Operations Management.</p>
        </div>
      </li>
      <li>
        <span class="homepage-year">2025</span>
        <div>
          <p class="homepage-paper-title"><a href="https://pubsonline.informs.org/doi/abs/10.1287/msom.2022.0440">Emergency Care Efficiency vs. Quality: Uncovering Hidden Consequences of Fast-Track Routing Decisions</a></p>
          <p class="homepage-paper-meta">Manufacturing &amp; Service Operations Management. Winner, Best Service Science Student Paper Award.</p>
        </div>
      </li>
    </ol>
    <p><a href="/publications/">View all publications</a></p>
  </section>

  <section class="homepage-section" aria-labelledby="academic-profile">
    <h2 id="academic-profile">Academic Profile</h2>
    <div class="homepage-bottom">
      <article class="homepage-card">
        <h3>Teaching</h3>
        <p>Courses and teaching activities in operations, analytics, stochastic modeling, and MBA education.</p>
        <p><a href="/teaching/">Teaching page</a></p>
      </article>
      <article class="homepage-card">
        <h3>Recognition</h3>
        <p>College Research Excellence Award and Outstanding Teaching Performance recognitions at City University of Hong Kong.</p>
        <p><a href="/awards/">Funding &amp; Awards</a></p>
      </article>
    </div>
  </section>

  <section class="homepage-contact" aria-label="Contact and profile links">
    <p>
      <strong>Contact</strong><br>
      7/F, Lau Ming Wai Academic Building<br>
      City University of Hong Kong<br>
      zhankun.sun AT cityu DOT edu.hk
    </p>
    <p>
      <strong>Profiles</strong><br>
      <a href="https://www.cb.cityu.edu.hk/staff/zhanksun/">CityUHK staff profile</a><br>
      <a href="https://orcid.org/0000-0002-1576-3372">ORCID</a><br>
      <a href="https://scholar.google.com/citations?user=uzUmqc0AAAAJ&amp;hl=en">Google Scholar</a>
    </p>
  </section>
</main>
