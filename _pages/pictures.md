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


## Interchange
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Interchange1.jpg" width="50%"><img src="{{ site.url }}{{ site.baseurl }}/images/picpic/interchange2.jpg" width="50%">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Interchange3.jpg" width="50%"><img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Interchange4.jpg" width="50%">
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Interchange1.jpg" style="width: 25%; display: inline-block;">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/interchange2.jpg" style="width: 25%; display: inline-block;">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Interchange3.jpg" style="width: 25%; display: inline-block;">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Interchange4.jpg" style="width: 25%; display: inline-block;">

</figure>

