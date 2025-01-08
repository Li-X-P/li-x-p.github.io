---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

<!-- 第一部分：语言描述 -->
<section class="teaching-description">
  <h2>比赛指导</h2>
<body>
<ul class="timeline">
  <li class="entry"><div class="details">第六届国际青年人工智能大赛百度Apollo星火自动驾驶主题赛，省一等 <br>负责人：王思琪、陈晓琳、褚宏亚；指导老师：李强、李晓鹏</li>
  <li class="entry"><div class="details">第二十一届全国大学生信息安全与对抗技术竞赛-自动驾驶仿真赛项，省三等 <br>负责人：陈晓琳、王思琪、褚宏亚；指导老师：李强、李晓鹏 </li>
</ul>
</body>
  
</section>

<hr>

<!-- 第二部分：动态内容 -->
<section class="teaching-content">
  <h2>课程</h2>
  {% for post in site.teaching reversed %}
    {% include archive-single.html %}
  {% endfor %}
</section>
