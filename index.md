---
layout: default
title: Home
permalink: /
---

<!-- Font Awesome Icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
.hero {
  max-width: 1100px;
  margin: 60px auto;
  padding: 0 20px;
  display: grid;
  grid-template-columns: 340px 1fr;
  gap: 60px;
  align-items: start;
}

.hero-left {
  text-align: center;
}

.hero-left img {
  width: 230px;
  height: 230px;
  object-fit: cover;
  border-radius: 50%;
  display: block;
  margin: 0 auto;
}

.hero-name {
  margin: 20px 0 12px 0;
  font-size: 40px;
  font-weight: 700;
}

.hero-links {
  margin-top: 10px;
}

.icon-btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;

  width: 44px;
  height: 44px;
  margin: 0 6px;

  border: 1.5px solid #bdbdbd;
  border-radius: 8px;

  background: white;
  color: #222;

  font-size: 18px;
  text-decoration: none;

  transition: all 0.2s ease;
}

.icon-btn:hover {
  border-color: #111;
  color: #111;
}

.hero-right {
  padding-left: 50px;
  border-left: 1px solid #e6e6e6;
  font-size: 16px;
  line-height: 1.7;
}

.hero-right p {
  margin: 0 0 18px 0;
}

@media (max-width: 1000px) {
  .hero {
    grid-template-columns: 1fr;
    gap: 30px;
    margin: 30px auto;
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
      <a class="icon-btn" href="mailto:niels4blom@gmail.com">
        <i class="fa-regular fa-envelope"></i>
      </a>

      <a class="icon-btn" href="https://www.linkedin.com/in/niels-blom-706125241/">
        <i class="fa-brands fa-linkedin-in"></i>
      </a>

      <a class="icon-btn" href="https://github.com/nlblom">
        <i class="fa-brands fa-github"></i>
      </a>
    </div>
  </div>

  <div class="hero-right">
    <p>
      Hi! I am currently pursuing a one-year MSc in Data Science at University College London. In June 2025, I graduated from Erasmus University Rotterdam with a BSc in Econometrics and Operations Research, including a major in Quantitative Finance, and a minor in Engineering with AI at TU Delft.
    </p>

    <p>
      I focus on quantitative modelling and decision-making under uncertainty, with applications in financial markets and strategic contexts. My work has been mainly centered around density forecasting, portfolio evaluation, time-series econometrics and panel data analysis. I am proficient in Python, R, Matlab, Java and AIMMS.
    </p>

    <p>
      On this website, you will find a selection of projects demonstrating my work.
    </p>
  </div>

</div>
