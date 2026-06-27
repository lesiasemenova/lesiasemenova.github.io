---
layout: page
permalink: /facct2026_tutorial/
inline: true
title: FAccT 2026 Tutorial
related_posts: false
nav: false
---

{% assign slides_pdf = '/assets/pdf/facct26-tutorial-slides.pdf' | relative_url %}
{% assign lesia_headshot = '/assets/img/lesia_semenova.jpg' | relative_url %}
{% assign chudi_headshot = '/assets/img/group/chudi_headshot.jpg' | relative_url %}

<style>
  .facct-tutorial-page {
    max-width: 1040px;
    margin: 0 auto;
  }

  .facct-hero {
    margin-bottom: 1.25rem;
  }

  .facct-label {
    margin: 0 0 0.35rem;
    font-size: 0.85rem;
    font-weight: 700;
    letter-spacing: 0.06em;
    text-transform: uppercase;
    opacity: 0.72;
  }

  .facct-hero h1 {
    margin: 0 0 0.45rem;
    font-size: clamp(2rem, 4vw, 3.2rem);
    line-height: 1.08;
  }

  .facct-subtitle {
    margin: 0 0 0.6rem;
    font-size: 1.2rem;
    line-height: 1.4;
    opacity: 0.84;
  }

  .facct-meta {
    margin: 0 0 1rem;
    font-weight: 600;
  }

  .facct-intro {
    max-width: 850px;
    font-size: 1.05rem;
    line-height: 1.65;
  }

  .facct-section {
    margin: 2.6rem 0;
  }

  .facct-section h2 {
    margin-bottom: 0.9rem;
  }

  .facct-button-row {
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
    margin: 0.75rem 0 1rem;
  }

  .facct-button {
    display: inline-block;
    padding: 0.55rem 0.85rem;
    border: 1px solid currentColor;
    border-radius: 999px;
    text-decoration: none;
    font-weight: 600;
    line-height: 1.2;
  }

  .facct-button:hover {
    text-decoration: none;
  }

  .facct-pdf-frame {
    width: 100%;
    height: min(76vh, 760px);
    min-height: 520px;
    border: 1px solid rgba(0, 0, 0, 0.15);
    border-radius: 12px;
    overflow: hidden;
    background: #f7f7f7;
  }

  .facct-pdf-frame iframe {
    width: 100%;
    height: 100%;
    border: 0;
  }

  .facct-note {
    margin-top: 0.75rem;
    font-size: 0.95rem;
    opacity: 0.78;
  }

  .facct-highlight-grid,
  .facct-presenter-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 1.2rem;
  }

  .facct-card {
    padding: 1.1rem;
    border: 1px solid rgba(0, 0, 0, 0.12);
    border-radius: 14px;
    background: rgba(0, 0, 0, 0.015);
  }

  .facct-card h3 {
    margin-top: 0;
    margin-bottom: 0.45rem;
  }

  .facct-card p:last-child,
  .facct-card ul:last-child {
    margin-bottom: 0;
  }

  .facct-presenter-card {
    padding: 1.1rem;
    border: 1px solid rgba(0, 0, 0, 0.12);
    border-radius: 16px;
    text-align: center;
  }

  .facct-presenter-card img {
    width: 180px;
    height: 180px;
    object-fit: cover;
    border-radius: 50%;
    margin-bottom: 0.9rem;
  }

  .facct-presenter-card h3 {
    margin: 0 0 0.3rem;
  }

  .facct-affiliation {
    margin: 0 0 0.9rem;
    font-size: 0.95rem;
    opacity: 0.82;
  }

  .facct-schedule {
    width: 100%;
    border-collapse: collapse;
    margin-top: 0.75rem;
  }

  .facct-schedule th,
  .facct-schedule td {
    padding: 0.75rem;
    border-bottom: 1px solid rgba(0, 0, 0, 0.12);
    vertical-align: top;
  }

  .facct-schedule th {
    text-align: left;
    font-weight: 700;
  }

  .facct-schedule td:first-child {
    white-space: nowrap;
    font-weight: 600;
  }

  .facct-resource-list li {
    margin-bottom: 0.35rem;
  }

  @media (max-width: 640px) {
    .facct-pdf-frame {
      height: 540px;
      min-height: 420px;
    }

    .facct-presenter-card img {
      width: 150px;
      height: 150px;
    }

    .facct-schedule td:first-child {
      white-space: normal;
    }
  }
</style>

<div class="facct-tutorial-page">

  <section class="facct-hero">
    <p class="facct-label">FAccT 2026 tutorial</p>
    <h1>Translation Tutorial: The Illusion of the Best Model</h1>
    <p class="facct-subtitle">Multiplicity, Interpretability, and Accountability in High-Stakes AI</p>
    <p class="facct-meta">Lesia Semenova · Chudi Zhong</p>
    <p class="facct-intro">
      This tutorial introduces the Rashomon Effect: the idea that many substantively different models can achieve similarly high performance on the same dataset. We explain why this matters for high-stakes AI, and how exploring near-optimal models can make model selection more transparent, accountable, and contestable.
    </p>
  </section>

  <section class="facct-section" aria-labelledby="tutorial-slides">
    <h2 id="tutorial-slides">Tutorial slides</h2>
    <div class="facct-button-row">
      <a class="facct-button" href="{{ slides_pdf }}" target="_blank" rel="noopener">Open slides PDF</a>
    </div>
    <div class="facct-pdf-frame">
      <iframe src="{{ slides_pdf }}#toolbar=1&navpanes=0" title="FAccT 2026 tutorial slides" loading="lazy"></iframe>
    </div>
    <p class="facct-note">If the embedded PDF does not load in your browser, use the “Open slides PDF” link above.</p>
  </section>

  <section class="facct-section" aria-labelledby="presenters">
    <h2 id="presenters">Presenters</h2>
    <div class="facct-presenter-grid">
      <div class="facct-presenter-card">
        <a href="https://lesiasemenova.github.io/" target="_blank" rel="noopener">
          <img src="{{ lesia_headshot }}" alt="Lesia Semenova">
        </a>
        <h3>Lesia Semenova</h3>
        <p class="facct-affiliation">Assistant Professor of Computer Science, Rutgers University</p>
        <div class="facct-button-row" style="justify-content: center;">
          <a class="facct-button" href="https://lesiasemenova.github.io/" target="_blank" rel="noopener">Website</a>
          <a class="facct-button" href="mailto:lesia.semenova@rutgers.edu">Email</a>
        </div>
      </div>

      <div class="facct-presenter-card">
        <a href="https://chudizhong.github.io/" target="_blank" rel="noopener">
          <img src="{{ chudi_headshot }}" alt="Chudi Zhong">
        </a>
        <h3>Chudi Zhong</h3>
        <p class="facct-affiliation">Assistant Professor, UNC-Chapel Hill School of Data Science and Society</p>
        <div class="facct-button-row" style="justify-content: center;">
          <a class="facct-button" href="https://chudizhong.github.io/" target="_blank" rel="noopener">Website</a>
          <a class="facct-button" href="mailto:chudi@unc.edu">Email</a>
        </div>
      </div>
    </div>
  </section>

  <section class="facct-section" aria-labelledby="about">
    <h2 id="about">About the tutorial</h2>
    <p>
      In high-stakes settings such as criminal justice, healthcare, hiring, and lending, institutions often deploy a single machine learning model as if it were the uniquely correct or inevitable choice. The Rashomon perspective challenges that assumption: many models can perform nearly as well as the best model while differing in predictions, complexity, variable importance, interpretability, or fairness properties.
    </p>
    <p>
      This tutorial translates recent work on the Rashomon set for an interdisciplinary FAccT audience. Rather than treating interpretability, fairness, and accountability as downstream concerns, we show how multiplicity changes the starting point of model selection itself. If many near-optimal models exist, the question is not only which model is most accurate, but which model should be chosen, by whom, and according to which criteria.
    </p>
  </section>

  <section class="facct-section" aria-labelledby="why-it-matters">
    <h2 id="why-it-matters">What the Rashomon perspective adds</h2>
    <div class="facct-highlight-grid">
      <div class="facct-card">
        <h3>Model multiplicity</h3>
        <p>Participants learn why many accurate models can arise from the same dataset, especially when a problem is noisy or underspecified.</p>
      </div>
      <div class="facct-card">
        <h3>Interpretable alternatives</h3>
        <p>We discuss how large Rashomon sets can contain simpler, more interpretable models that perform comparably to more complex alternatives.</p>
      </div>
      <div class="facct-card">
        <h3>Accountability limits</h3>
        <p>The Rashomon set can reveal alternatives and clarify tradeoffs, but it does not by itself determine which tradeoff is normatively or legally justified.</p>
      </div>
    </div>
  </section>

  <section class="facct-section" aria-labelledby="learning-goals">
    <h2 id="learning-goals">Learning goals</h2>
    <ul>
      <li>Explain the Rashomon Effect and why similarly accurate models can arise in high-stakes settings.</li>
      <li>Describe how Rashomon sets can be characterized and explored for interpretable model classes.</li>
      <li>Use interactive tools to navigate near-optimal models and reason about tradeoffs among simplicity, interpretability, and other desiderata.</li>
      <li>Articulate what the Rashomon set can and cannot offer for explanation, audit, transparency, and accountability.</li>
      <li>Connect multiplicity theory to practical questions about model selection, procurement, documentation, and contestability.</li>
    </ul>
  </section>

  <section class="facct-section" aria-labelledby="format">
    <h2 id="format">Format</h2>
    <p>
      The tutorial is designed as a 60-minute session with a hands-on activity. Participants will explore near-optimal decision trees using <a href="https://poloclub.github.io/timbertrek/" target="_blank" rel="noopener">TimberTrek</a>, select models according to different criteria, and compare how equally accurate models can lead to different deployment choices.
    </p>

    <table class="facct-schedule">
      <thead>
        <tr>
          <th>Time</th>
          <th>Topic</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>10 min</td>
          <td>Introduction to the Rashomon Effect and why it challenges the single “best model” mindset.</td>
        </tr>
        <tr>
          <td>10 min</td>
          <td>Why multiplicity arises, including the roles of noise and underspecification.</td>
        </tr>
        <tr>
          <td>10 min</td>
          <td>What the Rashomon set can and cannot do for policy, audit, and accountability.</td>
        </tr>
        <tr>
          <td>10 min</td>
          <td>Methods and tools for exploring Rashomon sets in interpretable model classes.</td>
        </tr>
        <tr>
          <td>15 min</td>
          <td>Hands-on activity with near-optimal models using TimberTrek.</td>
        </tr>
        <tr>
          <td>5 min</td>
          <td>Discussion and conclusions.</td>
        </tr>
      </tbody>
    </table>
  </section>

  <section class="facct-section" aria-labelledby="resources">
    <h2 id="resources">Related materials</h2>
    <ul class="facct-resource-list">
      <li><a href="{{ slides_pdf }}" target="_blank" rel="noopener">Tutorial slides PDF</a></li>
      <li><a href="https://poloclub.github.io/timbertrek/" target="_blank" rel="noopener">TimberTrek hands-on tool</a></li>
      <li><a href="https://sites.google.com/view/rashomon-aaai-tutorial/" target="_blank" rel="noopener">Related AAAI 2026 tutorial materials</a></li>
      <li><a href="https://sites.google.com/view/interpretableml" target="_blank" rel="noopener">Related IC2S2 2024 tutorial materials</a></li>
    </ul>
  </section>

</div>
