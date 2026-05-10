---
layout: page
title: About
permalink: /
nav: true
nav_order: 1
---

<style>
.about-hero {
  display: grid;
  grid-template-columns: 1.35fr 0.75fr;
  gap: 2.5rem;
  align-items: center;
  margin-top: 1.5rem;
}

.about-name {
  font-size: 2.4rem;
  font-weight: 500;
  margin-bottom: 0.3rem;
}

.about-title {
  font-size: 1.15rem;
  color: var(--global-text-color-light);
  margin-bottom: 1.75rem;
}

.about-text {
  font-size: 1.03rem;
  line-height: 1.75;
}

.about-text p {
  margin-bottom: 1.25rem;
}

.about-photo img {
  width: 100%;
  max-width: 340px;
  border-radius: 12px;
  box-shadow: 0 4px 18px rgba(0, 0, 0, 0.12);
}

.about-photo {
  text-align: center;
}

@media (max-width: 768px) {
  .about-hero {
    grid-template-columns: 1fr;
  }

  .about-photo {
    order: -1;
  }

  .about-photo img {
    max-width: 260px;
  }

  .about-name {
    font-size: 2rem;
  }
}
</style>

<div class="about-hero">

  <div>
    <div class="about-name">Ashish Ghimire</div>
    <div class="about-title">Professor of Finance</div>

    <div class="about-text">
      <p>
        I am a finance faculty member at Texas Christian University. My academic interests center on corporate finance, corporate governance, executive labor markets, and capital markets. I enjoy studying how firms, executives, boards, and financial markets interact, and I bring those real-world connections into the classroom.
      </p>

      <p>
        Outside of work, I enjoy watching sports, especially soccer, college football, and tennis. I also grew up playing cricket for much of my life and continue to enjoy staying active through tennis and pickleball. I enjoy hiking, nature, and traveling whenever I can.
      </p>
    </div>
  </div>

  <div class="about-photo">
    <img src="/assets/img/prof_pic.jpg" alt="Ashish Ghimire">
  </div>

</div>
