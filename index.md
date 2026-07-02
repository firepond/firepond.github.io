---
layout: default
title: Ruitao Xue
description: Ruitao Xue is a PhD student at Newcastle University researching IoT intelligence, TinyML, streaming anomaly detection, and lifelong learning.
body_class: home
---

<section class="hero" aria-labelledby="intro-title">
  <div class="hero-copy">
    <p class="eyebrow">PhD Student | School of Computing | Newcastle University</p>
    <h1 id="intro-title">Ruitao Xue</h1>
    <p class="lede">I build resource-efficient and secure intelligence for the Internet of Things. My research connects streaming anomaly detection, TinyML, and lifelong learning so embedded devices can adapt at the edge without sacrificing reliability.</p>

    <div class="hero-actions" aria-label="Contact and profile links">
      <a class="button primary" href="mailto:{{ site.email }}">Email me</a>
      <a class="button" href="https://github.com/{{ site.github_username }}">GitHub</a>
      <a class="button" href="{{ '/cv/' | relative_url }}">CV</a>
    </div>
  </div>

  <figure class="hero-visual">
    <img src="{{ '/assets/img/iot-edge-lab-hero.png' | relative_url }}" alt="IoT edge computing research setup with embedded devices and signal analysis on a laptop screen">
    <figcaption>Edge devices, sensors, and streaming signals are the practical setting for my research.</figcaption>
  </figure>
</section>

<section class="section intro-band" aria-labelledby="about-title">
  <div class="section-kicker">About</div>
  <div class="section-body">
    <h2 id="about-title">Edge intelligence that keeps learning after deployment.</h2>
    <p>I am a PhD student in Computing at Newcastle University. My work studies how tiny, networked devices can detect change, learn from streaming data, and remain dependable in messy real-world environments.</p>
    <p>I am especially interested in practical algorithms that balance accuracy, energy cost, memory limits, and security needs for embedded sensing systems.</p>
  </div>
</section>

<section class="section" id="research" aria-labelledby="research-title">
  <div class="section-kicker">Research</div>
  <div class="section-body">
    <h2 id="research-title">Research focus</h2>
    <div class="research-grid">
      <article class="research-card">
        <span class="card-index">01</span>
        <h3>Streaming anomaly detection</h3>
        <p>Algorithms that identify unusual behavior and concept drift as data arrives, with attention to latency, robustness, and deployability.</p>
      </article>
      <article class="research-card">
        <span class="card-index">02</span>
        <h3>Tiny machine learning</h3>
        <p>Learning pipelines for constrained hardware such as Raspberry Pi, ESP32, and Arduino-class platforms.</p>
      </article>
      <article class="research-card">
        <span class="card-index">03</span>
        <h3>Lifelong edge intelligence</h3>
        <p>Continual learning and autonomous agents for cyber-physical systems that need to adapt after deployment.</p>
      </article>
    </div>
  </div>
</section>

<section class="section split-section" id="publications" aria-labelledby="publications-title">
  <div class="section-kicker">Publications</div>
  <div class="section-body">
    <h2 id="publications-title">Selected publications</h2>
    <ol class="publication-list">
      <li>
        <span class="venue">ICDM OWAD 2025</span>
        <strong>STREAM-LAD: A Practical Streaming Lifelong Anomaly Detection Algorithm for IoT.</strong>
      </li>
      <li>
        <span class="venue">EWSN EMERGE 2025</span>
        <strong>Energy-Efficient Change Point Detection Algorithm for Resource-Constrained Devices.</strong>
      </li>
    </ol>
  </div>
</section>

<section class="section" aria-labelledby="education-title">
  <div class="section-kicker">Education</div>
  <div class="section-body">
    <h2 id="education-title">Education</h2>
    <div class="timeline">
      <article>
        <span>2024 - present</span>
        <h3>Newcastle University</h3>
        <p>PhD in Computing. Researching IoT intelligence, TinyML, anomaly detection, and agent-driven automation.</p>
      </article>
      <article>
        <span>Sept 2022 - Oct 2023</span>
        <h3>University of Glasgow</h3>
        <p>MSc in Computer Systems Engineering. Graduated with Distinction; GPA 17.8/22.</p>
      </article>
      <article>
        <span>Sept 2017 - Sept 2021</span>
        <h3>Beihang University (BUAA)</h3>
        <p>Bachelor of Engineering in Information Security. Graduated with Honors from ShenYuan Honors College.</p>
      </article>
    </div>
  </div>
</section>

<section class="section compact-section" aria-labelledby="skills-title">
  <div class="section-kicker">Skills</div>
  <div class="section-body">
    <h2 id="skills-title">Selected skills</h2>
    <div class="tag-groups">
      <div>
        <h3>Programming</h3>
        <p>Java, Python, PyTorch, NumPy, scikit-learn, C, C++, CUDA, Go, SQL</p>
      </div>
      <div>
        <h3>Embedded systems</h3>
        <p>Raspberry Pi, ESP32, Arduino, high-level and low-level development</p>
      </div>
      <div>
        <h3>Tooling</h3>
        <p>Linux, Bash, Zsh, LaTeX, Microsoft Office, Git</p>
      </div>
      <div>
        <h3>Languages</h3>
        <p>English, Chinese, Japanese</p>
      </div>
    </div>
  </div>
</section>

<section class="contact-band" id="contact" aria-labelledby="contact-title">
  <div>
    <p class="eyebrow">Collaborate</p>
    <h2 id="contact-title">Interested in IoT intelligence, TinyML, or adaptive anomaly detection?</h2>
  </div>
  <div class="contact-actions">
    <a class="button primary" href="mailto:{{ site.email }}">R.Xue5 [at] newcastle.ac.uk</a>
    <a class="button" href="https://github.com/{{ site.github_username }}">github.com/{{ site.github_username }}</a>
  </div>
</section>
