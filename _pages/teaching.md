---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

<!-- 第一部分：语言描述 -->
<section class="teaching-description">
  <h2>关于教学</h2>
  <p>
    欢迎来到我的教学页面！这里您可以找到我教授课程的相关信息以及教学资源。
    我专注于 [具体学科或领域]，致力于为学生提供高质量的学习体验。
  </p>
  <p>
    如果您有兴趣了解更多，欢迎随时联系我！
  </p>
</section>

<hr>

<!-- 第二部分：动态内容 -->
<section class="teaching-content">
  <h2>教学动态</h2>
  {% for post in site.teaching reversed %}
    {% include archive-single.html %}
  {% endfor %}
</section>
