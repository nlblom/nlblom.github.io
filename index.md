---
layout: default
permalink: /
---

<style>
  .hero {
    max-width: 900px;           /* narrower overall, fits Minima nicely */
    margin: 40px auto;
    padding: 0 20px;
    display: grid;
    grid-template-columns: 320px 1fr;  /* smaller left column */
    gap: 40px;                  /* smaller gap */
    align-items: center;
  }

  .hero-left { text-align: center; }

  .hero-left img {
    width: 220px;
    height: 220px;
    object-fit: cover;
    border-radius: 50%;
    display: block;
    margin: 0 auto;
  }

  .hero-name {
    margin: 18px 0 10px 0;
    font-size: 40px;
    line-height: 1.05;
    font-weight: 700;
  }

  .hero-links a {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 40px;
    height: 40px;
    margin: 0 6px;
    border: 1px solid #d0d0d0;
    border-radius: 8px;
    text-decoration: none;
    font-size: 14px;
  }

  .hero-right {
    padding-left: 40px;          /* smaller padding */
    border-left: 1px solid #e6e6e6;
    font-size: 16px;             /* back to normal */
    line-height: 1.7;
  }

  .hero-right p { margin: 0 0 16px 0; }

  /* Stack layout earlier so text never becomes a skinny column */
  @media (max-width: 1050px) {
    .hero {
      grid-template-columns: 1fr;
      gap: 26px;
      margin: 24px auto;
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
