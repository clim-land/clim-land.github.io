---
title: "Clim-land - Pictures"
layout: piclay
excerpt: "Clim-land -- Pictures"
permalink: /pictures/
---

# Pictures

#### Gallery
(Right-click *'view image'* to see a larger image.)
{% assign number_printed = 0 %}
{% for pic in site.data.pictures_Leiden %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>


<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageLeiden_red.jpg" width="60%" >
</figure>


## Interchange
From the [group of Andreas Wallraff](http://www.qudev.ethz.ch/).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Interchange1.jpg" width="60%">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/interchange2.jpg" width="60%">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Interchange3.jpg" width="60%">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Interchange4.jpg" width="60%">

<div style="display: flex; align-items: center;">
  <div style="flex: 0 0 60%;">
    <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Interchange1.jpg" style="width: 100%;">
  </div>
  <div style="flex: 1;">
    <p>I am writing to share with you a selection of insightful articles published throughout the year 2023 in the One Earth journal. These publications cover a wide range of topics, such as carbon emissions, agriculture, water resources, the impact of climate change on human health, biodiversity, forest conservation, and various other critical issues related to emissions and environmental cycles. I hope my shared articles might be helpful in your research.</p>
    <!-- 添加更多文本或其他元素 -->
  </div>
</div>


</figure>

