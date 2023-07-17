---
title: "농업 데이터"
layout: archive
permalink: categories/ad
author_profile: true
sidebar_main: true
---

<!-- 공백이 포함되어 있는 카테고리 이름의 경우 site.categories['a b c'] 이런식으로! -->

***

{% assign posts = site.categories.ad %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}