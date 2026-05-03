---
title: "Blog"
layout: "page"
---

<style>
.card-grid { display: flex; flex-direction: column; gap: 20px; margin-top: 2rem; }
.card { display: flex; align-items: center; gap: 25px; border: 1px solid var(--border); border-radius: 14px; padding: 35px 35px; background: var(--entry); transition: transform 0.2s, box-shadow 0.2s; text-decoration: none !important; color: inherit; }
.card:hover { transform: translateY(-2px); box-shadow: 0 8px 20px rgba(0,0,0,0.1); text-decoration: none !important; }
.card-icon { font-size: 2rem; line-height: 1; }
.card-title { font-weight: 600; font-size: 1.2rem; }
</style>

<a href="/en/" style="display:inline-block;margin-bottom:4px;color:var(--secondary);text-decoration:none;font-size:16px;">Home</a>
<h1 style="margin-top:0;margin-bottom:20px;font-size:2rem;">Blog</h1>

<div class="card-grid">
  <a class="card" href="/en/posts/timeline/">
    <span class="card-icon">🕰️</span>
    <span class="card-title">Timeline</span>
  </a>
  <a class="card" href="/en/thinking/">
    <span class="card-icon">🤔</span>
    <span class="card-title">Thinking</span>
  </a>
  <a class="card" href="/en/technique/">
    <span class="card-icon">🔧</span>
    <span class="card-title">Technique</span>
  </a>
  <a class="card" href="/en/on-the-road/">
    <span class="card-icon">🧭</span>
    <span class="card-title">On the Road</span>
  </a>
  <a class="card" href="/en/reading/">
    <span class="card-icon">📚</span>
    <span class="card-title">Reading</span>
  </a>
</div>