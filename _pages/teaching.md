---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---
<head>
   <style>
      .indent {
        text-align: justify;
        hyphens: auto;
        text-indent: 2em; 
      }
      .no-indent {
        text-align: justify;
        hyphens: auto;
        text-indent: 0; 
      }
   </style>

  <style>
    .timeline {
      list-style: none; /* 移除默认的列表样式 */
      padding: 0; /* 移除默认的内边距 */
      padding-left: 16px; /* 左侧缩进大约相当于2个字符 */
    }
    .entry {
      display: flex; /* 使用Flexbox布局 */
      justify-content: space-between; /* 使内容两端对齐 */
      margin-bottom: 10px; /* 在条目之间添加一些间隔 */
      position: relative; /* 为伪元素设置定位上下文 */
      padding-left: 20px; /* 确保有空间放置符号标识 */
    }
    .entry::before {
      content: "●"; /* 使用黑色实心点作为前缀 */
      color: black; /* 设置颜色为黑色 */
      position: absolute; /* 绝对定位 */
      left: 0; /* 将实心点放在条目最左边 */
      font-size: larger; /* 调整实心点的大小 */
      margin-right: 10px; /* 右边距，增加文本间隔 */
    }
    .date {
      white-space: nowrap; /* 防止日期折行 */
    }
    .details {
      text-align: left; /* 左对齐详细信息 */
      width: 80%; /* 限制详细信息的宽度 */
    }
  </style>
</head>

{% include base_path %}


<!-- 第二部分：时间线展示 -->
<section class="teaching-timeline">
   <h2>比赛指导</h2>
  <ul class="timeline">
    <li class="entry">
      <div class="details">
        第六届国际青年人工智能大赛百度Apollo星火自动驾驶主题赛，省一等<br>
        负责人：王思琪、陈晓琳、褚宏亚；指导老师：李强、李晓鹏
      </div>
    </li>
    <li class="entry">
      <div class="details">
        第二十一届全国大学生信息安全与对抗技术竞赛-自动驾驶仿真赛，省三等<br>
        负责人：陈晓琳、王思琪、褚宏亚；指导老师：李强、李晓鹏
      </div>
    </li>
  </ul>
</section>

<hr>

<!-- 第二部分：动态内容 -->
<section class="teaching-content">
  <h2>课程</h2>
  {% for post in site.teaching reversed %}
    {% include archive-single.html %}
  {% endfor %}
</section>
