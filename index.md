---
layout: page
title: About me 
cover: false
---

Hi, I am Zeyuan Chen, a senior undergraduate majored in big data and data science at University of Science and Technology of China.

My main research interests lie on Computer Vision, especially on the topics of low-level vision and 3D reconstruction. Currently I am a research assistant at [UCSD](https://ucsd.edu) working with [Xiaolong Wang](https://xiaolonw.github.io/). Before I worked on image restoration & enhancement tasks advised by [Zhangyang(Atlas) Wang](https://vita-group.github.io/) and [Dong Liu](http://staff.ustc.edu.cn/~dongeliu/). Here is my [curriculum vitae].

I am looking for a 2022 fall Ph.D. position.

**Contact**: nnice1216@mail.ustc.edu.cn

# Publications 
<ul>
{% for paper in site.data.papers.papers %}
  {% if paper.selected %}
  <li>
  {% include paper.html paper=paper %}
  </li>
  {% endif %}
{% endfor %}
</ul>



# Research Experience

<div style="clear: both;">
  <div style="float: left; margin-right 1em;">
    <img src="/assets/img/ucsd.png" alt="" width="100" height="100">
  </div>
  <div>
    <h3>&nbsp;&nbsp;&nbsp;Apr. 2021 - Present: University of California, San Diego</h3>
    <p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Advisor: Xiaolong Wang</p>
  </div>
</div>

<div style="clear: both;">
  <div style="float: left; margin-right 1em;">
    <img src="/assets/img/austin.png" alt="" width="100" height="100">
  </div>
  <div>
    <h3>&nbsp;&nbsp;&nbsp;Jun. 2020 - Mar. 2021: University of Texas at Austin</h3>
    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;VITA Group</p>
    <p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Advisor: Zhangyang(Atlas) Wang</p>
  </div>
</div>

<div style="clear: both;">
  <div style="float: left; margin-right 1em;">
    <img src="/assets/img/mcmaster.png" alt="" width="100" height="100">
  </div>
  <div>
    <h3>&nbsp;&nbsp;&nbsp;Jun. 2020 - Aug. 2020: McMaster University</h3>
    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Data Science Lab</p>
    <p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Advisor: Fei Chiang</p>
  </div>
</div>
<br/>