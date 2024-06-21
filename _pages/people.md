---
layout: archive
title: "Who We Are"
permalink: /people/
author_profile: true
---

{% include base_path %}

Hydro-Meteo-Envir Group (HME@EDU) is part of the [Team]() of the [School](), a research and service center at the [University]().

Collaboration Mentor
======

<style>
.center-text {
  text-align: center; /* 水平居中 */
  vertical-align: middle; /* 垂直居中 */
}
</style>

<style>
  table, th, td {
    border: none;
  }
</style>

<table border="0">
    <tr>
        <th class="center-text">A老师 腾讯广告算法Leader<br>研究方向：大模型在推荐中的应用研究<br><img src="/images/profile.jpg" alt="Avatar" class="avatar"/></th>
        <th class="center-text">B老师 蚂蚁金服算法Leader<br>研究方向：大模型Agent在金融科技中的应用研究<br><img src="/images/profile.jpg" alt="Avatar" class="avatar"/></th>
        <th class="center-text">C老师 京东广告算法Leader<br>大模型在电商内容理解中的应用研究<br><img src="/images/profile.jpg" alt="Avatar" class="avatar"/></th>
    </tr>
    <tr><hr></tr>
    <tr>
        <td class="center-text">D老师 腾讯广告算法Leader<br>研究方向：大模型在推荐中的应用研究<br><img src="/images/profile.jpg" alt="Avatar" class="avatar"/></td>
        <td class="center-text"></td>
        <td class="center-text"></td>
    </tr>
</table>


<hr> 
Ph.D. student
======

<table border="0">
    <tr>
        <th class="center-text">A同学</th>
        <th class="center-text">B同学</th>
        <th class="center-text">C同学</th>
    </tr>
    <tr>
        <td class="center-text">研究方向：大模型在推荐中的应用研究</td>
        <td class="center-text">研究方向：大模型Agent在金融科技中的应用研究</td>
        <td class="center-text">研究方向：大模型在电商内容理解中的应用研究</td>
    </tr>
    <tr>
        <td class="center-text"><img src="/images/profile.jpg" alt="Avatar" class="avatar"/></td>
        <td class="center-text"><img src="/images/profile.jpg" alt="Avatar" class="avatar"/></td>
        <td class="center-text"><img src="/images/profile.jpg" alt="Avatar" class="avatar"/></td>
    </tr>
</table>


<hr> 
Master's student
======

<table border="0">
    <tr>
        <th class="center-text">A同学</th>
        <th class="center-text">B同学</th>
        <th class="center-text">C同学</th>
    </tr>
    <tr>
        <td class="center-text">研究方向：大模型在推荐中的应用研究</td>
        <td class="center-text">研究方向：大模型Agent在金融科技中的应用研究</td>
        <td class="center-text">研究方向：大模型在电商内容理解中的应用研究</td>
    </tr>
    <tr>
        <td class="center-text"><img src="/images/profile.jpg" alt="Avatar" class="avatar"/></td>
        <td class="center-text"><img src="/images/profile.jpg" alt="Avatar" class="avatar"/></td>
        <td class="center-text"><img src="/images/profile.jpg" alt="Avatar" class="avatar"/></td>
    </tr>
</table>



<hr> 
Alumni
======
{% for post in site.people reversed %}
  {% include archive-single.html %}
{% endfor %}
