---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

目前在上海交通大学攻读硕士学位。

我的研究领域包括：
- 基于强化学习的机械臂运动规划
  


<span class='anchor' id='-xl'></span>

# 🎓 学历
- *2021.09 - 2025.06*, 上海交通大学航空航天学院，航空航天工程专业
 
<span class='anchor' id='-toolbox'></span>

# 🧰工具箱（实用网站链接）

## 机器人学
### 机器人正向运动学
- [运动学建模方法-DH法](https://blog.csdn.net/subtitle_/article/details/130982929)  
- [微分运动学-雅克比矩阵](https://blog.csdn.net/Bellwen/article/details/129185312)  
我发现在实际的机器人运动控制实践中，许多人会在旋转的表示和使用上产生问题，主要是因为旋转不像平动一样具有线性性，因此在计算中容易产生混乱，因此我认为有必要从旋转的定义、表示方法出发，理解旋转的概念，这在机器人位姿表示中是很重要的。

### 机器人逆运动学

### 机器人动力学

## 深度强化学习

## python编程
- [python中列表(list)的使用](https://www.runoob.com/python/python-lists.html)