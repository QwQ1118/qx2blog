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

.timeline-note {
  font-size: 0.9rem;
  color: var(--secondary);
  margin-top: 4px;
  font-style: italic;
}
</style>

<a href="/zh-cn/" style="display:inline-block;margin-bottom:4px;color:var(--secondary);text-decoration:none;font-size:16px;">主页</a>
<a href="/zh-cn/goldhouse/" style="display:inline-block;margin-bottom:4px;color:var(--secondary);text-decoration:none;font-size:16px;">>>🏠黄金屋</a>
<h1 style="margin-top:0;margin-bottom:20px;font-size:2rem;">生命刻度</h1>

<p class="timeline-intro">
  "记录生命中重要的moments。"
</p>

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-year">2025.09.14</div>
    <div class="timeline-content">养了人生中第一只猫：吴墨</div>
    <div class="timeline-note">别名：小手套，男，生日：2026.07.15，奶牛猫，鼻子有一个白点，肚子有一个黑点，有白色手套</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2025.09</div>
    <div class="timeline-content">离职，回昆</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2024.04</div>
    <div class="timeline-content">进入陕西今日头条，开始工作，由此开始接触代码</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2023.07</div>
    <div class="timeline-content">大学毕业</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2022</div>
    <div class="timeline-content">奶奶离世</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2021</div>
    <div class="timeline-content">因为换宿舍陷入抑郁，开始接触哲学、天文学</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2019.09</div>
    <div class="timeline-content">进入昆明理工大学津桥学院，成为一名大学生</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2018.04</div>
    <div class="timeline-content">在b站发布了第一条剪辑视频</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2017.03</div>
    <div class="timeline-content">在网络上报名学习毛笔</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2016.09</div>
    <div class="timeline-content">进入师范附属中学，成为一名高中生</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2014</div>
    <div class="timeline-content">有了人生中第一台iphone，开始接触中玄、欧美圈</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2013.09</div>
    <div class="timeline-content">进入昆八中外国语学校，成为一名初中生</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2011</div>
    <div class="timeline-content">因为对星座感兴趣，开始研究西玄</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2009</div>
    <div class="timeline-content">同一年爷爷因心梗、小舅因脑溢血，相继去世</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2008</div>
    <div class="timeline-content">家里有了第一台电脑，开始接触tvb、韩流</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2007.09</div>
    <div class="timeline-content">进入春城小学，成为一名小学生</div>
  </div>
   <div class="timeline-item">
    <div class="timeline-year">2003.09</div>
    <div class="timeline-content">由于父母忙于生存，我提前进入幼儿园</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2001.01.18</div>
    <div class="timeline-content">世界上多了一个我</div>
  </div>
</div>