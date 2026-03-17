---
layout: default
title: Does ChatGPT enhance student learning?
---

<style>
  body {
    font-family: Arial, sans-serif;
    background: #f7f9fc;
    margin: 0;
    color: #1f2937;
    line-height: 1.6;
  }

  .hero {
    position: relative;
    height: 400px;
    background: url("images/students.png") center/cover no-repeat;
    margin-top: -24px;
  }

  .overlay {
    position: absolute;
    inset: 0;
    background: rgba(0, 0, 0, 0.7);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 20px;
  }

  .overlay h1 {
    color: white;
    font-size: 2.5rem;
    margin: 0 0 10px;
  }

  .overlay p {
    color: #e5e7eb;
    font-size: 1.2rem;
    margin: 0;
  }

  .site-nav {
    background: #0f766e;
    padding: 14px 20px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    gap: 10px 28px;
  }

  .site-nav a {
    color: white;
    text-decoration: none;
    font-weight: 700;
    font-size: 1rem;
    line-height: 1.2;
    padding: 4px 0;
    white-space: nowrap;
  }

  .site-nav a:hover {
    text-decoration: underline;
    text-underline-offset: 4px;
  }

  .meta-wrapper {
    display: flex;
    justify-content: center;
    margin: 50px auto 20px;
    padding: 0 20px;
  }

  .meta-card {
    background: #ffffff;
    padding: 30px;
    border-radius: 16px;
    max-width: 900px;
    width: 100%;
    box-shadow: 0 8px 24px rgba(0, 0, 0, 0.08);
    border-top: 4px solid #0f766e;
  }

  .meta-card h2 {
    color: #0f766e;
    margin: 0 0 20px;
    font-size: 2rem;
  }

  .meta-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 25px;
  }

  .meta-item h3 {
    margin: 0 0 6px;
    font-size: 1.05rem;
  }

  .meta-item p {
    margin: 0;
    color: #475569;
  }

  .content-card {
    max-width: 900px;
    margin: 2rem auto;
    background: white;
    padding: 2rem;
    border-radius: 14px;
    box-shadow: 0 4px 14px rgba(0, 0, 0, 0.08);
  }

  .content-card section:not(:last-child) {
    margin-bottom: 50px;
    padding-bottom: 30px;
    border-bottom: 2px solid #0f766e;
  }

  .content-card h2 {
    color: #0f766e;
    margin-top: 0;
  }

  .content-card h4,
  .content-card h5 {
    margin-bottom: 8px;
  }

  details {
    background: #f1f5f9;
    margin-bottom: 12px;
    border-radius: 10px;
    padding: 12px 16px;
    transition: 0.2s;
  }

  summary {
    font-weight: bold;
    cursor: pointer;
    list-style: none;
  }

  summary::after {
    content: "+";
    float: right;
    font-size: 18px;
  }

  details[open] summary::after {
    content: "−";
  }

  details[open] {
    background: #e0f2f1;
  }

  .download-box {
    margin-top: 10px;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  }

  .download-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 20px;
    padding: 25px;
    background: linear-gradient(90deg, #0a5a53, #649794);
    color: white;
  }

  .download-content h3 {
    margin: 0 0 8px;
  }

  .download-content p {
    margin: 4px 0;
  }

  .download-btn {
    display: inline-block;
    background: white;
    color: #0f172a;
    padding: 10px 18px;
    border-radius: 8px;
    text-decoration: none;
    font-weight: bold;
    transition: 0.2s;
  }

  .download-btn:hover {
    background: #e2e8f0;
  }

  .license {
    background: #f8fafc;
    padding: 12px 20px;
    font-size: 0.9rem;
    color: #133a70;
  }

  .site-footer {
    text-align: center;
    padding: 1.5rem;
    color: #6b7280;
  }

  @media (max-width: 700px) {
    .overlay h1 {
      font-size: 2rem;
    }

    .overlay p {
      font-size: 1rem;
    }

    .site-nav {
      gap: 8px 16px;
      padding: 12px 16px;
    }

    .site-nav a {
      font-size: 0.95rem;
    }

    .meta-grid {
      grid-template-columns: 1fr;
    }

    .download-content {
      flex-direction: column;
      align-items: flex-start;
    }

    .content-card,
    .meta-wrapper {
      padding-left: 16px;
      padding-right: 16px;
    }
  }
</style>

<header class="hero">
  <div class="overlay">
    <h1>Does ChatGPT enhance student learning?</h1>
    <p>Research-based insights on AI in education</p>
  </div>
</header>

<nav class="site-nav">
  <a href="#review">Review</a>
  <a href="#results">Main Results</a>
  <a href="#quality">Analysis Quality</a>
  <a href="#stakeholders">Relevant Stakeholders</a>
  <a href="#studies">Study Examples</a>
  <a href="#transparency">AI Transparency</a>
</nav>

<section class="meta-wrapper">
  <div class="meta-card">
    <h2>Meta-Analysis Overview</h2>

    <div class="meta-grid">
      <div class="meta-item">
        <h3>Focus of the Study</h3>
        <p>Text</p>
      </div>

      <div class="meta-item">
        <h3>Average Effect Size</h3>
        <p>Text</p>
      </div>

      <div class="meta-item">
        <h3>Target Group</h3>
        <p>Text</p>
      </div>

      <div class="meta-item">
        <h3>Additional Findings</h3>
        <p>Text</p>
      </div>
    </div>
  </div>
</section>

<div class="content-card">
  <section id="review">
    <h2>Review of the Meta-Analysis</h2>
    <p>Text</p>

    <h4>Introduction</h4>
    <p>Text</p>

    <h4>What is this study about?</h4>
    <p>Text</p>
  </section>

  <section id="results">
    <h2>Main Results</h2>
    <p>Text</p>
    <ul>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
    </ul>
    <p>Text</p>
  </section>

  <section id="quality">
    <h2>Quality of the Meta-Analysis</h2>
    <p>Text</p>
    <ul>
      <li>M</li>
      <li>A</li>
      <li>G</li>
      <li>I</li>
      <li>C</li>
    </ul>
  </section>

  <section id="stakeholders">
    <h2>Conclusion for Research and Relevant Stakeholders</h2>
    <p>Text</p>
  </section>

  <section id="studies">
    <h2>Study Examples (Individual Contribution)</h2>

    <details>
      <summary>Christina</summary>

      <h5>General Description</h5>
      <ul>
        <li>What was done (use pictures)</li>
        <li>What were the main results?</li>
        <li>Conclusion</li>
      </ul>

      <h5>Why is it special to me?</h5>
      <p>Hallo! :)</p>

      <h5>Why is it a good example?</h5>
      <p>Hallo! :)</p>

      <h4>Here you can find my study example</h4>
      <a href="pdf/s41599-023-02269-7.pdf" download class="download-btn">
        ChatGPT-3.5 as writing assistance in students’ essays
      </a>
    </details>

    <details>
      <summary>Marina</summary>

      <ul>
        <li>What was done (use pictures)</li>
        <li>What were the main results?</li>
        <li>Conclusion</li>
      </ul>

      <h5>Why is it special?</h5>
      <p>Hey! :)</p>

      <h5>Why is it a good example?</h5>
      <p>Hey! :)</p>
    </details>
  </section>

  <section id="transparency">
    <h2>AI Transparency Statement</h2>
    <p>
      ChatGPT was used to support the structuring of the website, drafting of text and preparation of summaries.
      All content was checked against the original scientific sources.
    </p>
  </section>

  <section class="download-box">
    <div class="download-content">
      <div>
        <h3>Here you can find the original study</h3>
        <p>Does ChatGPT enhance student learning?</p>
        <p>A systematic review and meta-analysis of experimental studies.</p>
      </div>

      <a href='pdf/Deng et al. - 2025 - Does ChatGPT enhance student learning A systematic review and meta-analysis of experimental studies.pdf' download class="download-btn">
        Open PDF
      </a>
    </div>

    <div class="license">
      <p>
        This document is provided for academic purposes only.
        Please cite the original authors when using this material.
      </p>
    </div>
  </section>
</div>

<footer class="site-footer">
  University project by Knes Christina &amp; Hofer Marina on ChatGPT and Student Learning
</footer>