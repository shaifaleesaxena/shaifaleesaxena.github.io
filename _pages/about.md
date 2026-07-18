---
permalink: /
layout: home
title: "Shaifalee Saxena — Reinforcement Learning and Control Researcher"
description: "Ph.D. researcher developing robust reinforcement learning and adaptive control methods for robotics, particle accelerators, and autonomous systems."
redirect_from:
  - /about/
  - /about.html
---

<section class="hero shell" aria-labelledby="hero-title">
  <div class="hero-copy">
    <p class="eyebrow">Reinforcement learning &amp; control · Los Alamos, New Mexico</p>
    <h1 id="hero-title">Shaifalee Saxena</h1>
    <p class="hero-role">Ph.D. Student &amp; Graduate Research Assistant</p>
    <p class="lede">I develop robust learning-based control methods for robotics, particle accelerator tuning, and autonomous systems operating under distribution shift.</p>
    <div class="hero-actions">
      <a class="button primary" href="#research">Explore my research</a>
      <a class="button" href="{{ '/files/Shaifalee_Saxena_CV_030426.pdf' | relative_url }}">Download CV</a>
    </div>
    <ul class="social-list" aria-label="External profiles">
      <li><a href="mailto:shaifalees@lanl.gov">Email</a></li>
      <li><a href="https://scholar.google.com/citations?user=AimLmAcAAAAJ&amp;hl=en">Google Scholar</a></li>
      <li><a href="https://github.com/shaifaleesaxena">GitHub</a></li>
      <li><a href="https://www.linkedin.com/in/shaifalee-saxena-695a18108/">LinkedIn</a></li>
    </ul>
  </div>
  <figure class="portrait">
    <img src="{{ '/images/profile.jpg' | relative_url }}" alt="Portrait of Shaifalee Saxena">
  </figure>
</section>

<section class="section" id="about" aria-labelledby="about-title">
  <div class="shell">
    <p class="section-kicker">About</p>
    <h2 id="about-title">Learning systems that remain useful when the world changes</h2>
    <div class="about-grid">
      <div class="prose">
        <p>I am a Graduate Research Assistant in the Adaptive Machine Learning group at Los Alamos National Laboratory and a Ph.D. student in Electrical and Computer Engineering at the University of New Mexico.</p>
        <p>My research combines reinforcement learning, extremum seeking, robotics, representation learning, and adaptive control. I am particularly interested in controllers that can recognize distribution shift, stop trusting an unreliable learned policy, and adapt safely online.</p>
      </div>
      <div class="mini-columns">
        <div>
          <h3>Positions</h3>
          <p><strong>Graduate Research Assistant</strong><span>Los Alamos National Laboratory · 2025–present</span></p>
          <p><strong>Research Assistant</strong><span>University of New Mexico · 2024–present</span></p>
        </div>
        <div>
          <h3>Education</h3>
          <p><strong>Ph.D., Electrical &amp; Computer Engineering</strong><span>University of New Mexico · 2024–present</span></p>
          <p><strong>B.Tech., Aerospace Engineering</strong><span>IIST · 2014–2018</span></p>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="section section-tint" id="research" aria-labelledby="research-title">
  <div class="shell">
    <p class="section-kicker">Research</p>
    <div class="section-heading">
      <h2 id="research-title">Robust intelligence for dynamic physical systems</h2>
      <p>My work connects learning, adaptation, and control across accelerator and robotic platforms.</p>
    </div>
    <ul class="tag-list" aria-label="Research interests">
      <li>Reinforcement learning</li><li>Robotics</li><li>Robust &amp; adaptive control</li><li>Distribution shift</li><li>Representation learning</li><li>Accelerator control</li><li>Space robotics</li>
    </ul>
    <div class="research-grid">
      <article class="research-card">
        <p class="card-label">01 · Adaptive control</p>
        <h3>Robust RL for time-varying systems</h3>
        <p>Hybrid actor-critic and bounded extremum-seeking controllers that preserve fast learned behavior while adapting to drift and nonstationary dynamics.</p>
        <a href="https://arxiv.org/abs/2510.02490">Read the ACC 2026 paper <span aria-hidden="true">→</span></a>
      </article>
      <article class="research-card">
        <p class="card-label">02 · OOD detection</p>
        <h3>Learning when to trust RL</h3>
        <p>Mahalanobis-guided latent OOD detection for deciding when a controller should stop using a learned RL policy and switch to robust bounded extremum seeking.</p>
        <a href="https://arxiv.org/abs/2606.11474">Read the ICML RLxF paper <span aria-hidden="true">→</span></a>
      </article>
      <article class="research-card">
        <p class="card-label">03 · Autonomous systems</p>
        <h3>Visual control and space robotics</h3>
        <p>Compact visual representations, failure detection, and corrective control for autonomous systems, including satellite solar-panel deployment.</p>
        <a href="{{ '/research/' | relative_url }}">Explore all research projects <span aria-hidden="true">→</span></a>
      </article>
    </div>
  </div>
</section>

<section class="section" id="news" aria-labelledby="news-title">
  <div class="shell news-shell">
    <div><p class="section-kicker">News</p><h2 id="news-title">Recent updates</h2></div>
    <ol class="timeline">
      {% for item in site.data.news %}
        <li>
          <time datetime="{{ item.date | date: '%Y-%m-%d' }}"><span>{{ item.date | date: '%b' }}</span>{{ item.date | date: '%Y' }}</time>
          <p>{{ item.text }} {% if item.url %}<a href="{{ item.url }}">{{ item.link | default: 'Details' }} <span aria-hidden="true">→</span></a>{% endif %}</p>
        </li>
      {% endfor %}
    </ol>
  </div>
</section>

<section class="section section-tint" id="recent-publications" aria-labelledby="publications-title">
  <div class="shell">
    <p class="section-kicker">Selected work</p>
    <div class="section-heading publication-heading">
      <div><h2 id="publications-title">Recent publications</h2><p>Learning-based control methods designed for changing, uncertain environments.</p></div>
      <a class="text-link" href="https://scholar.google.com/citations?user=AimLmAcAAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Google Scholar <span aria-hidden="true">→</span></a>
    </div>
    <div class="filters" role="group" aria-label="Filter publications by topic">
      <button class="active" type="button" data-filter="all" aria-pressed="true">All</button>
      <button type="button" data-filter="reinforcement-learning" aria-pressed="false">Reinforcement learning</button>
      <button type="button" data-filter="robotics" aria-pressed="false">Robotics</button>
    </div>
    <div class="publication-list">
      {% for publication in site.data.publications %}
        <article class="publication" data-topic="{{ publication.topic_slug }}">
          <div class="pub-meta"><span>{{ publication.year }}</span><span>{{ publication.type }}</span></div>
          <div>
            <p class="venue">{{ publication.venue }}</p>
            <h3>{{ publication.title }}</h3>
            <p class="authors">{{ publication.authors }}</p>
            <div class="pub-links">
              {% if publication.paper %}<a href="{{ publication.paper }}">Paper</a>{% endif %}
              {% if publication.arxiv %}<a href="{{ publication.arxiv }}">arXiv</a>{% endif %}
              {% if publication.code %}<a href="{{ publication.code }}">Code</a>{% endif %}
            </div>
          </div>
        </article>
      {% endfor %}
    </div>
  </div>
</section>

<section class="section" id="service" aria-labelledby="service-title">
  <div class="shell">
    <p class="section-kicker">Community</p>
    <h2 id="service-title">Service &amp; recognition</h2>
    <div class="service-grid">
      <article><p class="card-label">Peer review</p><h3>Conference reviewer</h3><p>Reviewer for the IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2026) and the IEEE Conference on Decision and Control (CDC 2026).</p></article>
      <article><p class="card-label">Recognition</p><h3>Awards and support</h3><p>ACC 2026 travel grant recipient, Airbus SPOT Award recipient, Tata Best Performer and Team Award recipient, and ICONS 2018 second-best-paper awardee.</p></article>
      <article><p class="card-label">Engagement</p><h3>Talks and programs</h3><p>Participant in the 2026 Deep Learning for Science Summer School and invited speaker on unmanned aerial systems autonomy through the IEEE RAS Technical Education Program.</p></article>
    </div>
  </div>
</section>
