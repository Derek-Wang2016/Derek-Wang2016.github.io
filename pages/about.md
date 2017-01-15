---
layout: page
title: About
description: 你想看的World
keywords: Derek Wang
comments: true
menu: 关于
permalink: /about/
---

我是Derek

仰慕「优雅码字的艺术」。

## 坚信

* 熟能生巧
* 努力改变人生

## 联系

* GitHub：[@derek]()
* 掘金：[@derek]()
* LinkedIn：[@derek]()
* 博客：[{{ site.title }}]({{ site.url }})
* 微博: [@derek]()
* 知乎: [@derek]()
* 豆瓣: [@derek]()

## Skill Keywords

#### Software Engineer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_software_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### Mobile Developer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_mobile_app_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### Windows Developer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_windows_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>
