---
title: "黄金屋"
layout: "page" 
searchHidden: true
---

<style>
.card-grid { display: flex; flex-direction: column; gap: 20px; margin-top: 2rem; }
.card { display: flex; align-items: center; gap: 25px; border: 1px solid var(--border); border-radius: 14px; padding: 35px 35px; background: var(--entry); transition: transform 0.2s, box-shadow 0.2s; text-decoration: none !important; color: inherit; }
.card:hover { transform: translateY(-2px); box-shadow: 0 8px 20px rgba(0,0,0,0.1); text-decoration: none !important; }
.card-icon { font-size: 2rem; line-height: 1; }
.card-title { font-weight: 600; font-size: 1.2rem; }
</style>


<a href="/zh-cn/" style="display:inline-block;margin-bottom:4px;color:var(--secondary);text-decoration:none;font-size:0.9rem;">主页</a>
<h1 style="margin-top:0;margin-bottom:20px;font-size:2rem;">黄金屋</h1>

<div class="card-grid">
  <a class="card" href="/zh-cn/posts/生命刻度/">
    <span class="card-icon">🕰️</span>
    <span class="card-title">生命刻度</span>
  </a>
  <a class="card" href="/zh-cn/thinking/">
  <span class="card-icon">🤔</span>
  <span class="card-title">我思故我在</span>
  </a>
  <a class="card" href="/zh-cn/technique/">
  <span class="card-icon">🔧</span>
  <span class="card-title">巧夺天工</span>
  </a>
  <a class="card" href="/zh-cn/on-the-road/">
  <span class="card-icon">🧭</span>
  <span class="card-title">寻此苦旅</span>
  </a>
  <a class="card" href="/zh-cn/reading/">
  <span class="card-icon">📚</span>
  <span class="card-title">避难所</span>
  </a>
  <!-- 以后其他分类卡片就加在这里 -->
</div>