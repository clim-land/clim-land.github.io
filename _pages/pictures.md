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
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="100%" style="float: left" />
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


## International network
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Interchange1.jpg" style="width: 45%; display: inline-block;">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/interchange2.jpg" style="width: 45%; display: inline-block;">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Interchange3.jpg" style="width: 45%; display: inline-block;">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Interchange4.jpg" style="width: 50%; display: inline-block;">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/5.jpg" style="width: 45%; display: inline-block;">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/6.jpg" style="width: 45%; display: inline-block;">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/c.jpg" style="width: 45%; display: inline-block;">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/e.jpg" style="width: 45%; display: inline-block;">
</figure>

