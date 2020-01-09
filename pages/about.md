---
layout: page
title: About
description: 持续记录，持续积累，持续思考，持续创新
keywords: Liu Huan, 刘欢
comments: true
menu: 关于
permalink: /about/
---

TO BE FILLED

[^_^]:
  ## 联系

    {% for website in site.data.social %}
    * {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
    {% endfor %}

  ## Skill Keywords

  {% for category in site.data.skills %}
  ### {{ category.name }}
  <div class="btn-inline">
  {% for keyword in category.keywords %}
  <button class="btn btn-outline" type="button">{{ keyword }}</button>
  {% endfor %}
  </div>
  {% endfor %}
