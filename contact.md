---
layout: page
title: "Contact"
subtitle: "Ways to reach me."
page_header: true
permalink: /contact/
---

<div class="contact-grid">
  <a class="contact-card" href="mailto:{{ site.author.email }}">
    <div class="contact-icon">
      <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
        <rect x="2" y="4" width="20" height="16" rx="2"/>
        <path d="M22 4L12 13L2 4"/>
      </svg>
    </div>
    <div class="contact-info">
      <h3>Email</h3>
      <p>{{ site.author.email }}</p>
    </div>
  </a>

  <a class="contact-card" href="https://github.com/{{ site.author.github }}" target="_blank" rel="noopener">
    <div class="contact-icon">
      <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
        <polyline points="16 18 22 12 16 6"/>
        <polyline points="8 6 2 12 8 18"/>
      </svg>
    </div>
    <div class="contact-info">
      <h3>GitHub</h3>
      <p>github.com/{{ site.author.github }}</p>
    </div>
  </a>

  <a class="contact-card" href="https://linkedin.com/in/{{ site.author.linkedin }}" target="_blank" rel="noopener">
    <div class="contact-icon">
      <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
        <path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-4 0v7h-4v-7a6 6 0 0 1 6-6z"/>
        <rect x="2" y="9" width="4" height="12"/>
        <circle cx="4" cy="4" r="2"/>
      </svg>
    </div>
    <div class="contact-info">
      <h3>LinkedIn</h3>
      <p>linkedin.com/in/{{ site.author.linkedin }}</p>
    </div>
  </a>
</div>
