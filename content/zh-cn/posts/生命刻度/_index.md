---
title: "生命刻度"
layout: "page"
searchHidden: true
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
  color: #999 ;
  margin-bottom: 2rem;
  line-height: 1.7;
}
</style>

<a href="/zh-cn/" style="display:inline-block;margin-bottom:4px;color:var(--secondary);text-decoration:none;font-size:16px;">主页</a>
<a href="/zh-cn/goldhouse/" style="display:inline-block;margin-bottom:4px;color:var(--secondary);text-decoration:none;font-size:16px;">>>🏠黄金屋</a>
<h1 style="margin-top:0;margin-bottom:20px;font-size:2rem;">生命刻度</h1>

<p class="timeline-intro">
  "这里的每一个坐标都代表着我生命的重要时刻，它们都是时间留给我的礼物。"
</p>

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-year">2001</div>
    <div class="timeline-content">出生于云南昆明</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2019</div>
    <div class="timeline-content">参加高考，进入大学</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2023</div>
    <div class="timeline-content">大学毕业，开始工作</div>
  </div>
</div>