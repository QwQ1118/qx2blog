---
title: "Timeline"
layout: "page"
---

<style>
/* 时间线整体容器 */
.timeline {
  position: relative;
  padding: 20px 0;
  margin: 2rem 0;
}
/* 中间竖线 */
.timeline::before {
  content: '';
  position: absolute;
  left: 30px;
  top: 0;
  bottom: 0;
  width: 2px;
  background: var(--border);
}
/* 每个事件 */
.timeline-item {
  position: relative;
  margin-bottom: 30px;
  padding-left: 70px;
}
/* 时间节点圆点 */
.timeline-item::before {
  content: '';
  position: absolute;
  left: 24px;
  top: 5px;
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background: var(--primary);
  border: 2px solid var(--background);
  z-index: 1;
}
/* 事件年份 */
.timeline-year {
  font-weight: 700;
  font-size: 1.1rem;
  margin-bottom: 4px;
  color: var(--primary);
}
/* 事件描述 */
.timeline-content {
  font-size: 0.95rem;
  color: var(--secondary);
}

/* 隐藏自动生成的标题和面包屑 */
.page-header {
  display: none !important;
}

/* 介绍文字样式 */
.timeline-intro {
  font-size: 1rem;
  color: #999;
  margin-bottom: 2rem;
  line-height: 1.7;
}
</style>

<a href="/en/" style="display:inline-block;margin-bottom:4px;color:var(--secondary);text-decoration:none;font-size:16px;">Home</a>
<a href="/en/blog/" style="display:inline-block;margin-bottom:4px;color:var(--secondary);text-decoration:none;font-size:16px;">>> 🏠Blog</a>
<h1 style="margin-top:0;margin-bottom:20px;font-size:2rem;">Timeline</h1>

<p class="timeline-intro">
 "Every coordinate here represents an important moment in my life; they are all gifts that time has given me."
</p>

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-year">2001</div>
    <div class="timeline-content">Born in Kunming, Yunnan</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2019</div>
    <div class="timeline-content">Took the college entrance exam, entered university</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2023</div>
    <div class="timeline-content">Graduated from university, started working</div>
  </div>
  <!-- Add more events as needed -->
</div>