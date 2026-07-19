---
layout: default
is_contact: true
title: Let's connect
description: Get in touch with Milind Juttiga.
---

<section class="page-hero container contact-hero">
  <p class="eyebrow"><span class="status-dot"></span> Open to good conversations</p>
  <h1>Say hello.<br><em>Build something.</em></h1>
  <p class="page-intro">Whether you want to talk infrastructure, a side project, or an interesting problem, my inbox is open.</p>
  <a class="contact-email" href="mailto:{{ site.email }}">{{ site.email }} <span aria-hidden="true">↗</span></a>
</section>

<section class="section container contact-links-section">
  <div class="section-label">01 / Find me online</div>
  <div class="social-list">
    {% for social in site.social %}
      <a class="social-row" href="{{ social.link }}" target="_blank" rel="noreferrer">
        <span class="social-name">{{ social.name }}</span>
        <span class="social-handle">{{ social.handle }}</span>
        <span class="social-arrow" aria-hidden="true">↗</span>
      </a>
    {% endfor %}
  </div>
</section>

<section class="contact-note container">
  <span class="contact-note-mark">✳</span>
  <div><h2>Always thinking about<br><span>the next useful thing.</span></h2><p>Working across datacenters and the edge, thinking about systems, and looking for the next problem worth solving.</p></div>
</section>
