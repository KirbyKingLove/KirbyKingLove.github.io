---
layout: archive
title: "Notes"
permalink: /Notes/
author_profile: true
---

{% include base_path %}

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
  
  /* 更新日志时间轴样式 */
  .timeline {
    position: relative;
    padding-left: 30px;
  }
  .timeline:before {
    content: '';
    position: absolute;
    left: 10px;
    top: 0;
    bottom: 0;
    width: 2px;
    background: #e1e4e8;
  }
  .timeline-entry {
    position: relative;
    margin-bottom: 20px;
    padding-bottom: 10px;
    border-bottom: 1px solid #f0f0f0;
  }
  .timeline-entry:last-child {
    border-bottom: none;
    margin-bottom: 0;
  }
  .timeline-date {
    position: absolute;
    left: -30px;
    width: 22px;
    height: 22px;
    border-radius: 50%;
    background: #0366d6;
    color: white;
    text-align: center;
    line-height: 22px;
    font-size: 12px;
  }
  .timeline-content {
    margin-left: 15px;
  }
  .timeline-title {
    font-weight: 600;
    margin-bottom: 5px;
    color: #24292e;
  }
  .timeline-desc {
    color: #586069;
    font-size: 14px;
  }
  
  /* 笔记标题样式 */
  .note-title {
    color: #0366d6;
    cursor: pointer;
    text-decoration: underline;
  }
   .note-section {
    padding-top: 50px;
    margin-top: -50px;
  }
</style>


## 用前须知 ##
**在您下载笔记之前，请先看Attention一栏。**因为笔记较多，所以直接翻找有些困难（*其实是我懒得敲分页代码了*）。我在笔记列表中插入了超链接，读者可直接选择跳转。


## 笔记列表 ##
1. <span class="note-title" onclick="document.getElementById('note1').scrollIntoView({behavior: 'smooth'})">货币银行学</span> 国家发展研究院 *李明浩*
2. <span class="note-title" onclick="document.getElementById('note2').scrollIntoView({behavior: 'smooth'})">电子线路分析与设计</span> 信息科学技术学院 *胡薇薇，陈江*
3. <span class="note-title" onclick="document.getElementById('note3').scrollIntoView({behavior: 'smooth'})">高等数学II</span> 数学科学学院 *黄得*
4. <span class="note-title" onclick="document.getElementById('note4').scrollIntoView({behavior: 'smooth'})">普通生物学B</span> 生命科学学院 *佟向军*
5. <span class="note-title" onclick="document.getElementById('note5').scrollIntoView({behavior: 'smooth'})">数学物理方法</span> 信息科学技术学院 *彭超*
6. <span class="note-title" onclick="document.getElementById('note6').scrollIntoView({behavior: 'smooth'})">数字电路与系统设计</span> 信息科学技术学院 *罗武*
7. <span class="note-title" onclick="document.getElementById('note7').scrollIntoView({behavior: 'smooth'})">中级微观经济学</span> 国家发展研究院 *王敏*
8. <span class="note-title" onclick="document.getElementById('note8').scrollIntoView({behavior: 'smooth'})">电磁学</span> 元培学院 *韩铭*

## 下载链接 ##

<!-- 货币银行学 -->
<div id="note1" class="note-section"></div>
<a href="/files/货币银行学.pdf" download class="download-link">
1.货币银行学.pdf</a>

 <div class="accordion">
  <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
    <span>笔记信息</span>
    <span>▾</span>
  </div>
  <div class="accordion-content">
    <p>国家发展研究院课程，2024-2025第一学期，讲课内容以米什金货币金融学为主，有少量老师原创内容</p>
  </div>
</div>

 <div class="accordion">
  <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
    <span>更新日志</span>
    <span>▾</span>
  </div>
  <div class="accordion-content">
    <div class="timeline">
      <div class="timeline-entry">
        <div class="timeline-date">01</div>
        <div class="timeline-content">
          <div class="timeline-title">初始版本</div>
          <div class="timeline-desc">2025-06-01</div>
          <div class="timeline-desc">上传了一份笔记</div>
        </div>
      </div>    
       </div>
  </div>
</div>
<!-- 如果要增加词条，复制132-139行>

<!-- 电子线路分析与设计 -->
<div id="note2" class="note-section"></div>
<a href="/files/电子线路分析与设计_模拟电路部分.pdf" download class="download-link">
2.电子线路分析与设计_模拟电路部分.pdf</a>

 <div class="accordion">
  <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
    <span>笔记信息</span>
    <span>▾</span>
  </div>
  <div class="accordion-content">
    <p>信息科学技术学院ee专业：电路分析+模拟电路内容。2024-2025第一学期。本文档只有陈江老师讲述的模电部分。</p>
  </div>
</div>

 <div class="accordion">
  <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
    <span>更新日志</span>
    <span>▾</span>
  </div>
  <div class="accordion-content">
    <div class="timeline">
      <div class="timeline-entry">
        <div class="timeline-date">01</div>
        <div class="timeline-content">
          <div class="timeline-title">初始版本</div>
          <div class="timeline-desc">2025-06-01</div>
          <div class="timeline-desc">上传了一份笔记</div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- 高等数学II -->
<div id="note3" class="note-section"></div>
<a href="/files/高等数学_II_.pdf" download class="download-link">
3.高等数学（下）[高数A、B均可用].pdf</a>

 <div class="accordion">
  <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
    <span>笔记信息</span>
    <span>▾</span>
  </div>
  <div class="accordion-content">
    <p>数院公共课高等数学下册笔记，2024-2025第二学期。含有HD老师上课讲解内容和xhm数学分析讲义中的部分例题</p>
  </div>
</div>

 <div class="accordion">
  <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
    <span>更新日志</span>
    <span>▾</span>
  </div>
  <div class="accordion-content">
    <div class="timeline">
      <div class="timeline-entry">
        <div class="timeline-date">01</div>
        <div class="timeline-content">
          <div class="timeline-title">初始版本</div>
          <div class="timeline-desc">2025-06-01</div>
          <div class="timeline-desc">上传了一份笔记</div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- 普通生物学B -->
<div id="note4" class="note-section"></div>
<a href="/files/普通生物学_B_.pdf" download class="download-link">
4.普通生物学(B).pdf</a>

 <div class="accordion">
  <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
    <span>笔记信息</span>
    <span>▾</span>
  </div>
  <div class="accordion-content">
    <p>通选课，2024-2025第一学期。佟向军老师的普通生物学(B)，只看PPT完全不够，一定要多听课。</p>
  </div>
</div>

 <div class="accordion">
  <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
    <span>更新日志</span>
    <span>▾</span>
  </div>
  <div class="accordion-content">
    <div class="timeline">
      <div class="timeline-entry">
        <div class="timeline-date">01</div>
        <div class="timeline-content">
          <div class="timeline-title">初始版本</div>
          <div class="timeline-desc">2025-06-01</div>
          <div class="timeline-desc">上传了一份笔记</div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- 数学物理方法 -->
<div id="note5" class="note-section"></div>
<a href="/files/数学物理方法.pdf" download class="download-link">
5.数学物理方法.pdf</a>

 <div class="accordion">
  <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
    <span>笔记信息</span>
    <span>▾</span>
  </div>
  <div class="accordion-content">
    <p>信科彭超老师开设。2024-2025第二学期。内容较为精简，一些比较重要的内容老师也没有讲。</p>
  </div>
</div>

 <div class="accordion">
  <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
    <span>更新日志</span>
    <span>▾</span>
  </div>
  <div class="accordion-content">
    <div class="timeline">
      <div class="timeline-entry">
        <div class="timeline-date">01</div>
        <div class="timeline-content">
          <div class="timeline-title">初始版本</div>
          <div class="timeline-desc">2025-06-01</div>
          <div class="timeline-desc">上传了一份笔记</div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- 数字电路与系统设计 -->
<div id="note6" class="note-section"></div>
<a href="/files/数字电路与系统设计.pdf" download class="download-link">
6.数字电路与系统设计.pdf</a>

 <div class="accordion">
  <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
    <span>笔记信息</span>
    <span>▾</span>
  </div>
  <div class="accordion-content">
    <p>信科ee罗武老师开设。2024-2025第二学期。强烈建议配合教材进行使用。</p>
  </div>
</div>

  <div class="accordion">
  <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
    <span>更新日志</span>
    <span>▾</span>
  </div>
  <div class="accordion-content">
    <div class="timeline">
      <div class="timeline-entry">
        <div class="timeline-date">02</div>
        <div class="timeline-content">
          <div class="timeline-title">完整版本</div>
          <div class="timeline-desc">2025-06-02</div>
          <div class="timeline-desc">更新了第十章，第十一章内容，暂时用于小班课分享</div>
        </div>
      </div>    
      <div class="timeline-entry">
        <div class="timeline-date">01</div>
        <div class="timeline-content">
          <div class="timeline-title">初始版本</div>
          <div class="timeline-desc">2025-06-01</div>
          <div class="timeline-desc">上传了一份笔记,内容不完整，暂时用于小班课分享</div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- 中级微观经济学 -->
<div id="note7" class="note-section"></div>
<a href="/files/中级微观经济学.pdf" download class="download-link">
7.中级微观经济学.pdf</a>

 <div class="accordion">
  <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
    <span>笔记信息</span>
    <span>▾</span>
  </div>
  <div class="accordion-content">
    <p>国发院王敏老师开设。2024-2025第二学期。内容与范里安几乎一致。</p>
  </div>
</div>


<div class="accordion">
  <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
    <span>更新日志</span>
    <span>▾</span>
  </div>
  <div class="accordion-content">
    <div class="timeline">
      <div class="timeline-entry">
        <div class="timeline-date">01</div>
        <div class="timeline-content">
          <div class="timeline-title">初始版本</div>
          <div class="timeline-desc">2025-06-01</div>
          <div class="timeline-desc">上传了一份笔记</div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- 电磁学 -->
<div id="note8" class="note-section"></div>
<a href="/files/电磁学.pdf" download class="download-link">
8.电磁学.pdf</a>

 <div class="accordion">
  <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
    <span>笔记信息</span>
    <span>▾</span>
  </div>
  <div class="accordion-content">
    <p>元培学院韩铭老师开设。2024-2025第二学期。课本是伯克利电磁学，除了相对论部分和电介质和“本地教材”有些差别外，其余内容基本一致。是我自己很喜欢的一门课程。</p>
  </div>
</div>


<div class="accordion">
  <div class="accordion-header" onclick="this.parentElement.classList.toggle('active')">
    <span>更新日志</span>
    <span>▾</span>
  </div>
  <div class="accordion-content">
    <div class="timeline">
      <div class="timeline-entry">
        <div class="timeline-date">01</div>
        <div class="timeline-content">
          <div class="timeline-title">初始版本</div>
          <div class="timeline-desc">2025-06-02</div>
          <div class="timeline-desc">上传了一份笔记，还缺最后一节课的内容</div>
        </div>
      </div>
    </div>
  </div>
</div>