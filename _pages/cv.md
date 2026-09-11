---
layout: archive
title: "简历"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

教育经历
======

> 请在此填写学校、专业、学位与起止时间。

工作与项目经历
======

> 请在此填写工作、实习或重要项目经历。

技能
======

> 请在此填写技术栈、工具与研究方向。

论文
======

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

<!-- 临时滚动测试区域：确认页脚位置后可以删除。 -->
<div style="height: 120vh;" aria-hidden="true"></div>
