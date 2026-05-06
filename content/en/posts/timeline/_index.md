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

.timeline-note {
  font-size: 0.9rem;
  color: var(--secondary);
  margin-top: 4px;
  font-style: italic;
}
</style>

<a href="/en/" style="display:inline-block;margin-bottom:4px;color:var(--secondary);text-decoration:none;font-size:16px;">Home</a>
<a href="/en/blog/" style="display:inline-block;margin-bottom:4px;color:var(--secondary);text-decoration:none;font-size:16px;">>> 🏠Blog</a>
<h1 style="margin-top:0;margin-bottom:20px;font-size:2rem;">Timeline</h1>

<p class="timeline-intro">
 Record important moments in life.
</p>

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-year">2025.09.14</div>
    <div class="timeline-content">Got my first cat in life: Wu Mo</div>
    <div class="timeline-note">Alias: Little Gloves, Male, Birthday: 2026.07.15, Cow Cat, a white spot on the nose, a black spot on the belly, with white gloves</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2025.09</div>
    <div class="timeline-content">Resigned and returned to Kunming</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2024.04</div>
    <div class="timeline-content">Joined Shaanxi Toutiao, started working, and began learning to code from then on</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2023.07</div>
    <div class="timeline-content">Graduated from university</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2022</div>
    <div class="timeline-content">Grandmother passed away</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2021</div>
    <div class="timeline-content">Fell into depression due to changing dormitories and began to get into philosophy</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2019.09</div>
    <div class="timeline-content">Entered Jinqiao College, Kunming University of Science and Technology, becoming a university student</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2018.04</div>
    <div class="timeline-content">Uploaded my first fan edit video on Bilibili</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2017.03</div>
    <div class="timeline-content">Started learning Chinese brush calligraphy through online classes</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2016.09</div>
    <div class="timeline-content">Entered the Affiliated High School of Yunnan Normal University, becoming a high school student</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2014</div>
    <div class="timeline-content">Got my first iPhone in life, and started to get into Chinese metaphysics and European/American pop culture</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2013.09</div>
    <div class="timeline-content">Entered Kunming No. 8 Middle School Foreign Language School, becoming a middle school student</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2011</div>
    <div class="timeline-content">Began studying Western metaphysics due to an interest in astrology</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2009</div>
    <div class="timeline-content">In the same year, grandfather passed away from a heart attack, and uncle passed away from a cerebral hemorrhage</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2008</div>
    <div class="timeline-content">Got the first computer at home, and started to get into TVB and the Korean Wave</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2007.09</div>
    <div class="timeline-content">Entered Chuncheng Primary School, becoming a primary school student</div>
  </div>
   <div class="timeline-item">
    <div class="timeline-year">2003.09</div>
    <div class="timeline-content">Due to my parents being busy making a living, I entered kindergarten early</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2001.01.18</div>
    <div class="timeline-content">One more "me" appeared in the world</div>
  </div>
</div>