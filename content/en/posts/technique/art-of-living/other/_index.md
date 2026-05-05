---
title: "other"
layout: "page"
---

<style>
.card-grid { display: flex; flex-direction: column; gap: 20px; margin-top: 2rem; }
.card { display: flex; align-items: center; gap: 25px; border: 1px solid var(--border); border-radius: 14px; padding: 35px 35px; background: var(--entry); transition: transform 0.2s, box-shadow 0.2s; text-decoration: none !important; color: inherit; }
.card:hover { transform: translateY(-2px); box-shadow: 0 8px 20px rgba(0,0,0,0.1); text-decoration: none !important; }
.card-icon { font-size: 2rem; line-height: 1; }
.card-title { font-weight: 600; font-size: 1.2rem; }

/* 隐藏自动生成的标题和面包屑 */
.page-header { display: none !important; }

/* 重要：隐藏子目录文章自动生成的条目，保持卡片页纯净 */
.post-entry {
  display: none !important;
}
</style>

<a href="/en/" style="display:inline-block;margin-bottom:4px;color:var(--secondary);text-decoration:none;font-size:16px;">Home</a>
<a href="/en/blog/" style="display:inline-block;margin-bottom:4px;color:var(--secondary);text-decoration:none;font-size:16px;">>>Blog</a>
<a href="/en/technique/" style="display:inline-block;margin-bottom:4px;color:var(--secondary);text-decoration:none;font-size:16px;">>>techology</a>
<a href="/en/posts/technique/art-of-living/" style="display:inline-block;margin-bottom:4px;color:var(--secondary);text-decoration:none;font-size:16px;">>>techology</a>
<h1 style="margin-top:0;margin-bottom:20px;font-size:2rem;">Other</h1>

<p style="color: #999; font-size: 1rem; line-height: 1.7; margin-bottom: 2rem;">
 A little from the east, a little from the west, the scraps of life.
</p>

<div class="card-grid">
  <a class="card" href="/en/posts/technique/art-of-living/other/chinese-brush/">
    <span class="card-icon">🖌️</span>
    <span class="card-title">Chinese Brush</span>
  </a>
  <a class="card" href="/en/posts/technique/art-of-living/other/music/">
    <span class="card-icon">🎵</span>
    <span class="card-title">Music</span>
  </a>
</div>