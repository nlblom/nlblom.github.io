---
layout: default
permalink: /
---

<style>
  .hero {
    max-width: 1200px;
    margin: 50px auto;
    padding: 0 20px;
    display: grid;
    grid-template-columns: 320px 1fr; /* smaller left -> wider text */
    gap: 50px;
    align-items: start;
  }

  .hero-left { text-align: center; }

  .hero-left img {
    width: 230px;
    height: 230px;
    object-fit: cover;
    border-radius: 50%;
    display: block;
    margin: 0 auto;
  }

  .hero-name {
    margin: 20px 0 10px 0;
    font-size: 40px;
    line-height: 1.05;
    font-weight: 700;
  }

  .hero-links a {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 42px;
    height: 42px;
    margin: 0 6px;
    border: 1px solid #d0d0d0;
    border-radius: 8px;
    text-decoration: none;
    font-size: 14px;
  }

  .hero-right {
    padding-left: 40px;          /* less padding -> more text width */
    border-left: 1px solid #e6e6e6;

    /* Force normal text sizing */
    font-size: 16px;
    line-height: 1.7;
  }

  .hero-right p { margin: 0 0 16px 0; }

  @media (max-width: 1100px) {
    .hero {
      grid-template-columns: 1fr;
      gap: 28px;
      margin: 28px auto;
    }
    .hero-right {
      border-left: none;
      padding-left: 0;
    }
  }
</style>

<div class="hero">

  <div class="hero-left">
    <img src="/assets/cv_photo.jpg" alt="Profile photo">

    <div class="hero-name">Niels Blom</div>

    <div class="hero-links">
      <a href="mailto:niels4blom@gmail.com" aria-label="Email">✉</a>
      <a href="https://www.linkedin.com/in/niels-blom-706125241/" aria-label="LinkedIn">in</a>
      <a href="https://github.com/nlblom" aria-label="GitHub">⌂</a>
    </div>
  </div>

  <div class="hero-right">
    <p>
      Hi! I am currently pursuing a one-year MSc in Data Science at University College London. In June 2025, I graduated from Erasmus University Rotterdam with a BSc in Econometrics and Operations Research, including a major in quantitative finance, and a minor in Engineering with AI at TU Delft.
    </p>

    <p>
      I focus on quantitative modelling and decision-making under uncertainty, with applications in financial markets and strategic contexts. My work has been mainly centered around density forecasting, portfolio evaluation, time-series econometrics and panel data analysis. I am proficient in Python, R, Matlab, Java and AIMMS.
    </p>

    <p>
      On this website, you will find a selection of projects demonstrating my work.
    </p>
  </div>

</div>
