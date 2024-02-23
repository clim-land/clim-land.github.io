---
title: "Clim-land - Team"
layout: gridlay
excerpt: "Clim-land: Team members"
sitemap: false
permalink: /team/
---
# Group Leader
<div class="col-sm-6 clearfix">
  <img src="/images/teampic/xudong.png" class="img-responsive" width="50%" style="float: left" />
  <h4>Xudong Wu</h4>
  <i>Associate Professor, Alexander von Humboldt Fellow 
  Beijing Forestry University, China
  Potsdam Institute for Climate Impact Research, Germany
  E-mail: wuxudong@bjfu.edu.cn
  Research ID: https://orcid.org/0000-0002-0752-0282<!--<br>email: <email@example.com> --></i>
  <ul style="overflow: hidden">
    <!-- 这里可以放置更多的成员详细信息列表 -->
  </ul>
</div>

<!-- Clearfix to ensure that the following content starts on a new line -->
<div class="clearfix"></div> <!-- This div ends the floating effect -->

# Group Members

 **We are looking for pashionate new members to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/vacancies) **!**

{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <br>email: <{{ member.email }}></i> 
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 | markdownify}} </li>
  <li> {{ member.education2 | markdownify}} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

# Graduate Members
<div class="col-sm-6 clearfix">
  <img src="/images/teampic/hongxiao.jpg" class="img-responsive" width="25%" style="float: left" />
  <h4>Hongxiao Yue</h4>
  <i>Grad since 2023</i>
  <i>Institute of Geographic Sciences and Natural Resource Research, Chinese Academy of Sciences(CAS)<!--<br>email: <email@example.com> --></i>
  <ul style="overflow: hidden">
    <!-- 这里可以放置更多的成员详细信息列表 -->
  </ul>
</div>

