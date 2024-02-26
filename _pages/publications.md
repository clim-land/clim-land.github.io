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
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="40%" style="float: left;  height: 180px" />
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

## 2024

<div class="article">
  <p style="font-weight: bold; text-align: left;">Mapping spatially-explicit cropland-related soil erosion in China from 1980 to 2018 at a 30 m resolution</p>
  <p style="font-style: italic; text-align: left;">Xie, Y., Zhang, T., Zhang, Z., Wu, X.* (Contributed equally as the 1<sup>st</sup> author)</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Submitting</a></p>
</div>

## 2023


<div class="article">
  <p style="font-weight: bold; text-align: left;">Mapping the spatial heterogeneity of global land use and land cover from 2020 to 2100 at a 1 km resolution</p>
  <p style="font-style: italic; text-align: left;">Zhang, T., Cheng, C.*, Wu, X.*</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Scientific Data</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Mapping the heterogeneity of global methane footprint in China at the subnational level</p>
  <p style="font-style: italic; text-align: left;">Guo, M., Cheng, C.*, Wu, X.*</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Environmental Management</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Impacts of production structure changes on global CH<sub>4</sub> emissions: Evidences from income-based accounting and decomposition analysis</p>
  <p style="font-style: italic; text-align: left;">Cheng, X., Wu, X., Guan, C., Sun, X., Zhang, B.* </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Ecological Economics</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Evaluating temporal-spatial variations of wetland ecosystem service value in China during 1990–2020 from the donor side based on cosmic exergy</p>
  <p style="font-style: italic; text-align: left;">Xu, Y., Xie, Y., Wu, X.*, Xie, Y., Zhang, T., Zou, Z., Zhang, R., Zhang, Z.* (Contributed equally as the 1<sup>st</sup> author)</p>
  <p><a href="10.1016/j.landusepol.2023.106588" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Mutual complementarity of arable land use in the Sino-Africa trade: Evidence from the global supply chain</p>
  <p style="font-style: italic; text-align: left;">Ji, X.*, Su, P., Liu, Y., Wu, G., Wu, X. </p>
  <p><a href="10.1016/j.landusepol.2023.106588" style="font-weight: bold; text-decoration: none;">Land Use Policy</a></p>
</div>


## 2022


<div class="article">
  <p style="font-weight: bold; text-align: left;">Global pastureland use as reflected in inter-regional supply chain</p>
  <p style="font-style: italic; text-align: left;">Li, C., Wu, X., Chen, K., Chen, G.*  (Contributed equally as the 1<sup>st</sup> author)</p>
  <p><a href="10.1007/s11356-023-25278-0" style="font-weight: bold; text-decoration: none;">Journal of Environmental Management</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Water cost for water purification: Renewability assessment of a typical wastewater treatment plant in China</p>
  <p style="font-style: italic; text-align: left;">Xie, Y., Zeng, L., Wang, P.*, Wu, X.*, Feng, T. (Contributed equally as the 1<sup>st</sup> author)</p>
  <p><a href="10.1007/s11356-023-25278-0" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Global temporal evolution of CH<sub>4</sub> emissions via geo-economic integration</p>
  <p style="font-style: italic; text-align: left;">Wang, X., Tian, W., Guan, C., Wu, X.*, Sun, X., Zhang, B.* (Contributed equally as the 1<sup>st</sup> author)</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Environmental Management</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">An improved extended exergy accounting method for assessing the sustainability of the Chinese society</p>
  <p style="font-style: italic; text-align: left;">Meng, Z., Jin, P., Wu, X., Zhang, B.*, Guo JL</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>


## 2021

<div class="article">
  <p style="font-weight: bold; text-align: left;">Is solar power renewable and carbon-neutral: Evidence from a pilot solar tower plant in China under a systems view</p>
  <p style="font-style: italic; text-align: left;">Wu, X., Li, C., Shao, L., Meng, J., Zhang, L.*, Chen, G.*</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Renewable and Sustainable Energy Reviews</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Energy use flows in the supply chains of the world economy: A full account of both primary and intermediate inputs</p>
  <p style="font-style: italic; text-align: left;">Wu, X.*, Guo, J., Chen, G.*, Wu, X.F., Meng, J., Alhodaly, M., Wakeel, M.</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Pastureland use of China: Accounting variations from different input-output analyses</p>
  <p style="font-style: italic; text-align: left;">Li, C., Wu, X., Chen, G.*, Han, M., Chen, K., Yangzong, C., Lo, D., Alsaedi, A., Hayat, T. (Contributed equally as the 1<sup>st</sup> author)</p>
  <p><a href="10.1016/j.landusepol.2021.105597" style="font-weight: bold; text-decoration: none;">Land Use Policy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Multi criteria analysis ranking of solar photovoltaic modules manufacturing countries by an importing country: A case of Uganda</p>
  <p style="font-style: italic; text-align: left;">Mukisa, N.*, Zamora, R., Tek, L., Wu, X., Chen, G</p>
  <p><a href="10.1016/j.scitotenv.2020.144841" style="font-weight: bold; text-decoration: none;">Solar Energy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Extended carbon footprint and emission transfer of world regions: With both primary and intermediate inputs into account</p>
  <p style="font-style: italic; text-align: left;">Wu, X.*, Li, C., Guo, J., Wu, X.F., Meng, J., Chen, G.* </p>
  <p><a href="10.1016/j.scitotenv.2021.145578" style="font-weight: bold; text-decoration: none;">Science of The Total Environment</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Can constructed wetlands be more land efficient than centralized wastewater treatment systems? A case study based on direct and indirect land use</p>
  <p style="font-style: italic; text-align: left;">Fan, Y., Wu, X., Shao, L., Han, M., Chen, B., Meng, J., Wang, P.*, Chen, G.* (Contributed equally as the 1<sup>st</sup> author)</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Science of The Total Environment</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Unveiling land footprint of solar power: A pilot solar tower project in China</p>
  <p style="font-style: italic; text-align: left;">Wu, X.*, Shao, L., Chen, G.*, Han, M., Chi, Y., Yang, Q., Alhodaly, M., Wakeel, M.</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Environmental Management</a></p>
</div>

## 2020

<div class="article">
  <p style="font-weight: bold; text-align: left;">Global supply chain of biomass use and the shift of environmental welfare from primary exploiters to final consumers</p>
  <p style="font-style: italic; text-align: left;">Ji, X.*, Liu, Y., Meng, J., Wu, X.*</p>
  <p><a href="10.1016/j.apenergy.2020.115484" style="font-weight: bold; text-decoration: none;">Applied Energy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">A unified ecological assessment of a solar concentrating plant based on an integrated approach joining cosmic exergy analysis with ecological indicators</p>
  <p style="font-style: italic; text-align: left;">Fan, Y., Wu, X., Wu, X.F., Li, C., Yang, Q., Hayat, T., Alsaedi, A., Wang, P.*, Chen, G.* (Contributed equally as the 1<sup>st</sup> author)</p>
  <p><a href="10.1016/j.rser.2020.109934" style="font-weight: bold; text-decoration: none;">Renewable and Sustainable Energy Reviews</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Carbon emissions embodied in the global supply chain: Intermediate and final trade imbalances</p>
  <p style="font-style: italic; text-align: left;">Wu, X., Guo, J., Li, C., Chen, G.*, Ji, X.* </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Science of The Total Environment</a></p>
</div>

## 2019

<div class="article">
  <p style="font-weight: bold; text-align: left;">Global socio-hydrology: An overview of virtual water use by the world economy from source of exploitation to sink of final consumption</p>
  <p style="font-style: italic; text-align: left;">Wu, X., Guo, J., Li, C., Shao, L., Han, M., Chen, G.*</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Hydrology</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Energy use in world economy from household-consumption-based perspective</p>
  <p style="font-style: italic; text-align: left;">Wu, X., Guo, J., Ji, X., Chen, G.*</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Energy Policy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Quantifying global CH<sub>4</sub> and N<sub>2</sub>O footprints</p>
  <p style="font-style: italic; text-align: left;">Tian, W., Wu, X., Zhao, X., Ma, R., Zhang, B.*</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Environmental Management</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Global overview for energy use of the world economy: Household-consumption-based accounting based on the world input-output database (WIOD)</p>
  <p style="font-style: italic; text-align: left;">Chen, G.*, Wu, X.*, Guo, J., Meng, J., Li, C</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Energy Economics</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Energy use by globalized economy: Total-consumption-based perspective via multi-region input-output accounting</p>
  <p style="font-style: italic; text-align: left;">Wu, X., Guo, J., Meng, J., Chen, G.*</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Science of the Total Environment</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Water footprint of thermal power in China: Implications from the high amount of industrial water use by plant infrastructure of coal-fired generation system</p>
  <p style="font-style: italic; text-align: left;">Wu, X., Ji, X., Li, C., Xia, X., Chen, G.*</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Energy Policy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Freshwater costs of seawater desalination: Systems process analysis for the case plant in China</p>
  <p style="font-style: italic; text-align: left;">Liu, S., Zhang, G., Han, M.*, Wu, X., Li, Y., Chen, K., Meng, J., Shao, L., Wei, W., Chen, G.*</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>

## 2018

<div class="article">
  <p style="font-weight: bold; text-align: left;">An overview of arable land use for the world economy: From source to sink via the global supply chain</p>
  <p style="font-style: italic; text-align: left;">Wu, X., Guo, J., Han, M., Chen, G.*</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Land Use Policy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">The striking amount of carbon emissions by the construction stage of coal-fired power generation system in China</p>
  <p style="font-style: italic; text-align: left;">Wu, X., Guo, J., Chen, G.*</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Energy Policy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Contaminant transport from point source on water surface in open channel flow with bed absorption</p>
  <p style="font-style: italic; text-align: left;">Guo, J., Wu, X., Jiang, W.*, Chen, G.*</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Hydrology</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Ultra-high voltage network induced energy cost and carbon emissions</p>
  <p style="font-style: italic; text-align: left;">Wei, W., Wu, X., Li, J.*, Jiang, X., Zhang, P., Zhou, S., Zhu, H., Liu, H., Chen, H., Guo, J., Chen, G.*  (Contributed equally as the 1<sup>st</sup> author)</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>

## 2017

<div class="article">
  <p style="font-weight: bold; text-align: left;">Energy and water nexus in power generation: The surprisingly high amount of industrial water use induced by solar power infrastructure in China</p>
  <p style="font-style: italic; text-align: left;">Wu, X., Chen, G.* </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Applied Energy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Coal use for world economy: Provision and transfer network by multi-region input-output analysis</p>
  <p style="font-style: italic; text-align: left;">Xia, X.*, Chen, B., Wu, X., Hu, Y., Liu, D., Hu, C </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">A three-scale input-output analysis of water use in a regional economy: Hebei province in China</p>
  <p style="font-style: italic; text-align: left;">Liu, S., Wu, X., Han, M.*, Zhang, J., Chen, B., Wu, X.F., Wei, W., Li, Z  (Contributed equally as the 1<sup>st</sup> author)</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>

## 2016

<div class="article">
  <p style="font-weight: bold; text-align: left;">Progress and prospect of CCS in China: Using learning curve to assess the cost-viability of a 2×600MW retrofitted oxyfuel power plant as a case study</p>
  <p style="font-style: italic; text-align: left;">Wu, X., Yang, Q., Chen, G.*, Hayat, T., Alsaedi, A</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Renewable and Sustainable Energy Reviews</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Embodied energy analysis for coal-based power generation system-highlighting the role of indirect energy cost</p>
  <p style="font-style: italic; text-align: left;">Wu, X., Xia, X., Chen, G.*, Wu, X.F., Chen, B</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Applied Energy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Virtual water accounting for a building construction engineering project with nine sub-projects: a case in E-town, Beijing</p>
  <p style="font-style: italic; text-align: left;">Han, M., Chen, G.*, Meng, J., Wu, X., Alsaedi, A., Ahmad, B</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Critical Length of Contaminant Cloud in a Three-Layer Wetland: Multi-scale Analysis for Environmental Dispersivity</p>
  <p style="font-style: italic; text-align: left;">Li, Z.*, Wang, P.*, Sun, T., An, Y., Wu, X</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Wetlands</a></p>
</div>