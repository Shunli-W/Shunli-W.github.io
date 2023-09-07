---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span id="Biography" class="section-subheading">Biography</span>
<!-- ====== -->

王顺利是中国山东农业大学信息科学与工程学院的在读研究生，目前正攻读计算机科学与技术工学硕士学位。他的研究方向包括计算机科学与技术，专注于人工智能深度学习技术和自然语言处理技术在精准生猪养殖中的应用。他对智能农业、农业机器人以及精准养殖等领域有浓厚的兴趣，并致力于将先进的技术应用于农业，以提高生产效率和可持续性。

Shunli Wang is a graduate student in the College of Information Science and Engineering at Shandong Agricultural University in China, where she is currently pursuing a master's degree in Computer science and Technology Engineering. His research interests include computer science and technology, focusing on the application of artificial intelligence deep learning technology and natural language processing technology in precision pig breeding. He has a strong interest in the fields of smart agriculture, agricultural robotics, and precision farming, and is committed to applying advanced technologies to agriculture to improve productivity and sustainability.

{% include education.html %}

<span id="Publications" class="section-subheading">Publications</span>
  <ul>
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>

<span id="Talks" class="section-subheading">Talks and presentations</span>

  <ul>
  {% for post in site.talks reversed %}
    {% include archive-single-talk.html %}
  {% endfor %}
  </ul>


<span id="Honour" class="section-subheading">Honour</span>
  <ul>
  {% for post in site.honour reversed %}
    {% include archive-single-honour.html %}
  {% endfor %}
  </ul>



<span id="Contact" class="section-subheading"></span>
  {% include Contact.html %}

  
<span id="Patent" class="section-subheading">Patent</span>
  <ul>
  {% for post in site.patent reversed %}
    {% include archive-single-patent.html %}
  {% endfor %}
  </ul>

<span id="News" class="section-subheading">News</span>
<!-- include News.html -->

<span id="Services"></span>
  <!-- include service.html -->

<!-- Talks
======
  <ul>
  {% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}
  </ul>


Teaching
======
  <ul>
  {% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>


Service and leadership
======
* Currently signed in to 43 different slack teams -->

<!-- 个人Github信息小卡片 -->
<!-- ![Christmas's GitHub stats](https://github-readme-stats.vercel.app/api?username=Shunli-W&show_icons=true&theme=tokyonight) -->

<!-- 个人主页各个国家的访问人数 -->
<!-- <a href="https://flagcounter.me/details/doX"><img src="https://flagcounter.me/doX/" alt="Flag Counter"></a> -->

<!-- 主页访问人数 -->
<!-- ![Visitor Count](https://profile-counter.glitch.me/qiao19981314/count.svg)
![Visitor Count](https://komarev.com/ghpvc/?username=qiao19981314&label=PROFILE+VIEWS) -->
