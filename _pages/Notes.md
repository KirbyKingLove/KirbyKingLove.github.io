---
layout: archive
title: "Notes"
permalink: /Notes/
author_profile: true
---

{% include base_path %}
<!-- 笔记列表 -->
## 笔记列表 ##
1. **货币银行学** 国家发展研究院 *李明浩*
2. **电子线路分析与设计** 信息科学技术学院 *胡薇薇，陈江*


## 下载链接 ##
<style>
  /* 折叠面板样式 */
  .accordion {
    border: 1px solid #e1e4e8;
    border-radius: 6px;
    margin: 20px 0;
  }
  .accordion-header {
    padding: 12px 15px;
    background: #f6f8fa;
    cursor: pointer;
    display: flex;
    justify-content: space-between;
    font-weight: 600;
  }
  .accordion-content {
    padding: 15px;
    display: none;
  }
  .accordion.active .accordion-content {
    display: block;
  }
  
  /* 下载链接样式 */
  .download-link {
    display: inline-block;
    padding: 10px;
    background: #f5f5f5;
    border-radius: 4px;
    color: #0366d6;
    text-decoration: none;
    margin: 10px 0;
  }
  
  /* 更新日志条目样式 */
  .update-entry {
    margin-bottom: 15px;
  }
  .update-date {
    font-weight: 500;
    color: #586069;
  }
  .update-title {
    font-weight: 600;
  }
</style>

<!-- 文档下载链接 -->
<a href="/files/货币银行学.pdf" download class="download-link">
  货币银行学.pdf nsd wm 2024-2025第二学期
</a>

<!-- 笔记信息面板 -->
<div class="accordion">
  <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
    <span>笔记信息</span>
    <span>▾</span>
  </div>
  <div class="accordion-content">
    <p>这里填写您的笔记描述信息...</p>
  </div>
</div>

<!-- 更新日志面板 -->
<div class="accordion">
  <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
    <span>更新日志</span>
    <span>▾</span>
  </div>
  <div class="accordion-content">
    <div class="update-entry">
      <div class="update-date">2024-03-15</div>
      <div class="update-title">初始版本</div>
      <div>创建了笔记框架</div>
    </div>
  </div>
</div>



{% assign notes = site.Notes | sort: 'date' | reverse %}
{% for post in notes %}
  {% unless post.path contains 'archive' %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}