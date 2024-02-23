---
title: "Clim-land - Publications"
layout: gridlay
excerpt: "Clim-land -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## Group highlights

**At the end of this page, you can find the [full list of publications and patents](#full-list-of-publications). **

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>

## Full List of publications

## 2023

<div class="article">
  <p style="font-weight: bold; text-align: left;">Impacts of production structure changes on global CH4 emissions: Evidences from income-based accounting and decomposition analysis</p>
  <p style="font-style: italic; text-align: left;">Xuelei Cheng; Xudong Wu; Chenghe Guan; Xudong Sun; Bo Zhang</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Ecological Economics</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Mutual complementarity of arable land use in the Sino-Africa trade: Evidence from the global supply chain</p>
  <p style="font-style: italic; text-align: left;">Xi Ji; Pinyi Su; Yifang Liu; Guowei Wu; Xudong Wu</p>
  <p><a href="10.1016/j.landusepol.2023.106588" style="font-weight: bold; text-decoration: none;">Land Use Policy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Resource exergy analysis of the Chinese society in 2017</p>
  <p style="font-style: italic; text-align: left;">Zheng Meng; Zhuan Yang; Bo Zhang; Xudong Wu</p>
  <p><a href="10.1007/s11356-023-25278-0" style="font-weight: bold; text-decoration: none;">Environmental Science and Pollution Research</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Global pastureland use as reflected in inter-regional supply chain</p>
  <p style="font-style: italic; text-align: left;">Chaohui Li; Xudong Wu; Kuang Chen; Guoqian Chen*</p>
  <p><a href="10.1007/s11356-023-25278-0" style="font-weight: bold; text-decoration: none;">Journal of Environmental Management</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Resource exergy analysis of the Chinese society in 2017</p>
  <p style="font-style: italic; text-align: left;">Zheng Meng; Zhuan Yang; Bo Zhang; Xudong Wu</p>
  <p><a href="10.1007/s11356-023-25278-0" style="font-weight: bold; text-decoration: none;">Environmental Science and Pollution Research</a></p>
</div>

## 2022

<div class="article">
  <p style="font-weight: bold; text-align: left;">Global temporal evolution of CH4 emissions via geo-economic integration</p>
  <p style="font-style: italic; text-align: left;">Wang Xin; Tian Wenjie; Guan Chenghe; Wu Xudong*; Sun Xudong; Zhang Bo*</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Environmental Management</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">An improved extended exergy accounting method for assessing the sustainability of the Chinese society</p>
  <p style="font-style: italic; text-align: left;">Zheng Meng; Pengfei Jin; Xudong Wu; Bo Zhang*; Junlian Gao</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Water cost for water purification: Renewability assessment of a typical wastewater treatment plant in China</p>
  <p style="font-style: italic; text-align: left;">Yongjuan Xie; Li Zeng; Ping Wang*; Xudong Wu*; Tianjiao Feng</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Global temporal evolution of CH4 emissions via geo-economic integration</p>
  <p style="font-style: italic; text-align: left;">Xin Wang; Wenjie Tian; Chenghe Guan; Xudong Wu*; Xudong Sun; Bo Zhang*</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>

## 2021

<div class="article">
  <p style="font-weight: bold; text-align: left;">Energy use flows in the supply chains of the world economy: A full account of both primary and intermediate inputs</p>
  <p style="font-style: italic; text-align: left;">Wu Xudong*,#; Guo Jinlan#; Chen Guoqian; Wu Xiaofang; Meng Jing; Alhodaly Mohammed; Wakeel Muhammad</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Science of The Total Environment</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Pastureland use of China: Accounting variations from different input-output analyses</p>
  <p style="font-style: italic; text-align: left;">Chaohui Li; Xudong Wu; Guoqian Chen*; Mengyao Han; Kuang Chen; Ciren Yangzong; Dan Lo; Ahmed Alsaedi; Tasawar Hayat</p>
  <p><a href="10.1016/j.landusepol.2021.105597" style="font-weight: bold; text-decoration: none;">Land Use Policy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Multi criteria analysis ranking of solar photovoltaic modules manufacturing countries by an importing country: A case of Uganda</p>
  <p style="font-style: italic; text-align: left;">Wu Xudong; Li Chaohui; Shao Ling; Meng Jing; Zhang Lixiao; Chen Guoqian*</p>
  <p><a href="10.1016/j.scitotenv.2020.144841" style="font-weight: bold; text-decoration: none;">Solar Energy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Extended carbon footprint and emission transfer of world regions: With both primary and intermediate inputs into account</p>
  <p style="font-style: italic; text-align: left;">Wu Xudong; Li Chaohui; Shao Ling; Meng Jing; Zhang Lixiao; Chen Guoqian*</p>
  <p><a href="10.1016/j.scitotenv.2021.145578" style="font-weight: bold; text-decoration: none;">Science of The Total Environment</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Can constructed wetlands be more land efficient than centralized wastewater treatment systems? A case study based on direct and indirect land use</p>
  <p style="font-style: italic; text-align: left;">Ying Fan; Xudong Wu; Ling Shao; Mengyao Han; Bin Chen; Jing Meng; Ping Wang*; Guoqian Chen*</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Science of The Total Environment</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Is solar power renewable and carbon-neutral: Evidence from a pilot solar tower plant in China under a systems view</p>
  <p style="font-style: italic; text-align: left;">Wu Xudong; Li Chaohui; Shao Ling; Meng Jing; Zhang Lixiao; Chen Guoqian*</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Renewable and Sustainable Energy Reviews</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Unveiling land footprint of solar power: A pilot solar tower project in China</p>
  <p style="font-style: italic; text-align: left;">Wu Xudong*,#; Shao Ling#; Chen Guoqian; Han Mengyao; Chi Yuanying; Yang Qing; Alhodaly Mohammed; Wakeel Muhammad</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Environmental Management</a></p>
</div>

## 2020

<div class="article">
  <p style="font-weight: bold; text-align: left;">Exports-driven primary energy requirements and the structural paths of Chinese regions</p>
  <p style="font-style: italic; text-align: left;">Ying Liu; Xudong Wu; Xudong Sun; Chenghe Guan; Bo Zhang*; Xiaofang Wu*</p>
  <p><a href="10.1007/s11707-020-0822-4" style="font-weight: bold; text-decoration: none;">Frontiers of Earth Science</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Global supply chain of biomass use and the shift of environmental welfare from primary exploiters to final consumers</p>
  <p style="font-style: italic; text-align: left;">Wu Xudong; Guo Jinlan; Li Chaohui; Chen Guoqian; Ji Xi</p>
  <p><a href="10.1016/j.apenergy.2020.115484" style="font-weight: bold; text-decoration: none;">Applied Energy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">A unified ecological assessment of a solar concentrating plant based on an integrated approach joining cosmic exergy analysis with ecological indicators</p>
  <p style="font-style: italic; text-align: left;">Ying Fan; Xudong Wu; Xiaofang Wu; Chaohui Li; Qing Yang; Tasawar Hayat; Ahmed Alsaedi; Ping Wang*; Guoqian Chen*</p>
  <p><a href="10.1016/j.rser.2020.109934" style="font-weight: bold; text-decoration: none;">Renewable and Sustainable Energy Reviews</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Carbon emissions embodied in the global supply chain: Intermediate and final trade imbalances</p>
  <p style="font-style: italic; text-align: left;">Wu Xudong; Guo Jinlan; Li Chaohui; Chen Guoqian; Ji Xi</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Science of The Total Environment</a></p>
</div>
