---
layout: archive
title: "Notes"
permalink: /Notes/
author_profile: true
---

{% include base_path %}

<html>
<head>
    <style>
        /* 折叠面板基础样式 */
        .accordion {
            border: 1px solid #e1e4e8;
            border-radius: 6px;
            margin: 20px 0;
            overflow: hidden;
        }
        .accordion-header {
            padding: 12px 15px;
            background: #f6f8fa;
            cursor: pointer;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-weight: 600;
        }
        .accordion-content {
            padding: 15px;
            display: none;
        }
        .accordion.active .accordion-content {
            display: block;
        }
        .accordion-icon::after {
            content: "▾";
        }
        .accordion.active .accordion-icon::after {
            content: "▴";
        }
    </style>
</head>
<body>

<!-- 文档下载链接 -->
<a href="files/货币银行学.pdf" download style="display: inline-block; padding: 10px; background: #f5f5f5; border-radius: 4px; color: #0366d6; text-decoration: none;">
    货币银行学.pdf nsd wm 2024-2025第二学期
</a>

<!-- 笔记信息面板 -->
<div class="accordion">
    <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
        <span>笔记信息</span>
        <span class="accordion-icon"></span>
    </div>
    <div class="accordion-content">
        <!-- 这里填写您的笔记信息内容 -->
        <p>这是笔记的详细信息...</p>
    </div>
</div>

<!-- 更新日志面板 -->
<div class="accordion">
    <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
        <span>更新日志</span>
        <span class="accordion-icon"></span>
    </div>
    <div class="accordion-content">
        <!-- 单条更新示例 -->
        <div style="margin-bottom: 15px;">
            <div style="font-weight: 500; color: #586069;">2024-03-15</div>
            <div style="font-weight: 600;">更新标题</div>
            <div>更新内容描述...</div>
        </div>
        <!-- 可以添加更多更新条目 -->
    </div>
</div>

</body>
</html>

## 观点与本站发展


  <style>

        /* 时间线容器 */
        .timeline-container {
            position: relative;
            max-width: 800px;
            margin: 0 auto;
        }

        /* 时间线竖线 */
        .timeline-container::after {
            content: '';
            position: absolute;
            width: 2px;
            background-color: #3498db;
            top: 0;
            bottom: 0;
            left: 20px;
        }

        /* 单个时间线项目 */
        .timeline-item {
            position: relative;
            margin-bottom: 40px;
            padding-left: 60px;
        }

        /* 时间节点圆点 */
        .timeline-node {
            position: absolute;
            left: 10px;
            top: 5px;
            width: 20px;
            height: 20px;
            background: #fff;
            border: 3px solid #3498db;
            border-radius: 50%;
            z-index: 1;
        }

        /* 内容区域 */
        .content {
            position: relative;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        /* 时间标题 */
        .content h3 {
            color: #3498db;
            margin-bottom: 8px;
        }

        /* 时间日期 */
        .time {
            display: block;
            color: #666;
            font-size: 0.9em;
            margin-bottom: 10px;
        }

        /* 响应式设计 */
        @media (max-width: 600px) {
            .timeline-container::after {
                left: 10px;
            }
            
            .timeline-item {
                padding-left: 40px;
            }
            
            .timeline-node {
                left: 0;
            }
        }
    </style>
   <details><summary>点击展开 </summary>
  <div class="timeline-container">
        <!-- 2022 秋 -->
    <div class="timeline-item">
      <div class="timeline-node"></div>
        <div class="content">
                <h3>你好, EECS</h3>
                <span class="time">2022 秋</span>
                <p>入燕园，初窥计算机语言与 Github</p>
        </div>
    </div>
    </div>
</details>



## 111

{% assign paths = "nameofthemd.md" | split: "," %}

{% for post in site.Notes reversed %}
  {% for path in paths %}
    {% if post.path contains path %}
      {% include archive-single.html %}
      {% break %}
    {% endif %}
  {% endfor %}
{% endfor %}
