---
title: "Clim-land - Publications"
layout: gridlay
excerpt: "Clim-land -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## Research highlights

**At the end of this page, you can find the [list of publications](#full-list-of-publications). **

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
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="40%" style="float: left" />
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

## List of publications 
 (<sup>#</sup> indicates equal contribution, and <sup>✽</sup> indicates the corresponding author.)

## 2024

<div class="article">
  <p style="font-weight: bold; text-align: left;">Mapping spatially-explicit cropland-related soil erosion in China from 1980 to 2018 at a 30 m resolution</p>
  <p style="font-style: italic; text-align: left;">Xie, Y.<sup>#</sup>, Zhang, T.<sup>#</sup>, Zhang, Z., <strong>Wu, X.</strong><sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Submitted</a></p>
</div>

## 2023

<div class="article">
  <p style="font-weight: bold; text-align: left;">Mapping the spatial heterogeneity of global land use and land cover from 2020 to 2100 at a 1 km resolution</p>
  <p style="font-style: italic; text-align: left;">Zhang, T., Cheng, C.*<sup>✽</sup>, <strong>Wu, X.</strong>*<sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Scientific Data</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Mapping the heterogeneity of global methane footprint in China at the subnational level</p>
  <p style="font-style: italic; text-align: left;">Guo, M., Cheng, C.*<sup>✽</sup>, <strong>Wu, X.</strong>*<sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Environmental Management</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Impacts of production structure changes on global CH<sub>4</sub> emissions: Evidences from income-based accounting and decomposition analysis</p>
  <p style="font-style: italic; text-align: left;">Cheng, X.<sup>#</sup>, <strong>Wu, X.</strong><sup>#</sup>, Guan, C., Sun, X., Zhang, B.<sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Ecological Economics</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Evaluating temporal-spatial variations of wetland ecosystem service value in China during 1990–2020 from the donor side based on cosmic exergy</p>
  <p style="font-style: italic; text-align: left;">Xu, Y.<sup>#</sup>, Xie, Y.<sup>#</sup>,<strong>Wu, X.</strong><sup>✽</sup>, Xie, Y., Zhang, T., Zou, Z., Zhang, R., Zhang, Z.<sup>✽</sup> </p>
  <p><a href="10.1016/j.landusepol.2023.106588" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Mutual complementarity of arable land use in the Sino-Africa trade: Evidence from the global supply chain</p>
  <p style="font-style: italic; text-align: left;">Ji, X.<sup>✽</sup>, Su, P., Liu, Y., Wu, G., <strong>Wu, X.</strong> </p>
  <p><a href="10.1016/j.landusepol.2023.106588" style="font-weight: bold; text-decoration: none;">Land Use Policy</a></p>
</div>


## 2022


<div class="article">
  <p style="font-weight: bold; text-align: left;">Global pastureland use as reflected in inter-regional supply chain</p>
  <p style="font-style: italic; text-align: left;">Li, C.<sup>#</sup>, <strong>Wu, X.</strong><sup>#</sup>, Chen, K., Chen, G.<sup>✽</sup>  </p>
  <p><a href="10.1007/s11356-023-25278-0" style="font-weight: bold; text-decoration: none;">Journal of Environmental Management</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Water cost for water purification: Renewability assessment of a typical wastewater treatment plant in China</p>
  <p style="font-style: italic; text-align: left;">Xie, Y.<sup>#</sup>, Zeng, L.<sup>#</sup>, Wang, P.<sup>✽</sup>, <strong>Wu, X.</strong><sup>✽</sup>, Feng, T. </p>
  <p><a href="10.1007/s11356-023-25278-0" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Global temporal evolution of CH<sub>4</sub> emissions via geo-economic integration</p>
  <p style="font-style: italic; text-align: left;">Wang, X.<sup>#</sup>, Tian, W.<sup>#</sup>, Guan, C., <strong>Wu, X.</strong><sup>✽</sup>, Sun, X., Zhang, B.<sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Environmental Management</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">An improved extended exergy accounting method for assessing the sustainability of the Chinese society</p>
  <p style="font-style: italic; text-align: left;">Meng, Z., Jin, P., <strong>Wu, X.</strong>, Zhang, B.<sup>✽</sup>, Guo JL </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>


## 2021

<div class="article">
  <p style="font-weight: bold; text-align: left;">Is solar power renewable and carbon-neutral: Evidence from a pilot solar tower plant in China under a systems view</p>
  <p style="font-style: italic; text-align: left;"><strong>Wu, X.</strong>, Li, C., Shao, L., Meng, J., Zhang, L.<sup>✽</sup>, Chen, G.<sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Renewable and Sustainable Energy Reviews</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Energy use flows in the supply chains of the world economy: A full account of both primary and intermediate inputs</p>
  <p style="font-style: italic; text-align: left;"><strong>Wu, X.</strong><sup>#，✽</sup>, Guo, J.<sup>#</sup>, Chen, G.<sup>✽</sup>, Wu, X.F., Meng, J., Alhodaly, M., Wakeel, M. </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Pastureland use of China: Accounting variations from different input-output analyses </p>
  <p style="font-style: italic; text-align: left;">Li, C.<sup>#</sup>, <strong>Wu, X.</strong><sup>#</sup>, Chen, G.<sup>✽</sup>, Han, M., Chen, K., Yangzong, C., Lo, D., Alsaedi, A., Hayat, T. </p>
  <p><a href="10.1016/j.landusepol.2021.105597" style="font-weight: bold; text-decoration: none;">Land Use Policy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Multi criteria analysis ranking of solar photovoltaic modules manufacturing countries by an importing country: A case of Uganda</p>
  <p style="font-style: italic; text-align: left;">Mukisa, N.<sup>✽</sup>, Zamora, R., Tek, L., <strong>Wu, X.</strong>, Chen, G </p>
  <p><a href="10.1016/j.scitotenv.2020.144841" style="font-weight: bold; text-decoration: none;">Solar Energy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Extended carbon footprint and emission transfer of world regions: With both primary and intermediate inputs into account</p>
  <p style="font-style: italic; text-align: left;"><strong>Wu, X.</strong><sup>#，✽</sup>, Li, C.<sup>#</sup>, Guo, J., Wu, X.F., Meng, J., Chen, G.<sup>✽</sup> </p>
  <p><a href="10.1016/j.scitotenv.2021.145578" style="font-weight: bold; text-decoration: none;">Science of The Total Environment</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Can constructed wetlands be more land efficient than centralized wastewater treatment systems? A case study based on direct and indirect land use</p>
  <p style="font-style: italic; text-align: left;">Fan, Y.<sup>#</sup>, <strong>Wu, X.</strong><sup>#</sup>, Shao, L., Han, M., Chen, B., Meng, J., Wang, P.<sup>✽</sup>, Chen, G.<sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Science of The Total Environment</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Unveiling land footprint of solar power: A pilot solar tower project in China</p>
  <p style="font-style: italic; text-align: left;"><strong>Wu, X.</strong><sup>✽</sup>, Shao, L., Chen, G.<sup>✽</sup>, Han, M., Chi, Y., Yang, Q., Alhodaly, M., Wakeel, M. </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Environmental Management</a></p>
</div>

## 2020

<div class="article">
  <p style="font-weight: bold; text-align: left;">Global supply chain of biomass use and the shift of environmental welfare from primary exploiters to final consumers</p>
  <p style="font-style: italic; text-align: left;">Ji, X.<sup>✽</sup>, Liu, Y., Meng, J., <strong>Wu, X.</strong><sup>✽</sup> </p>
  <p><a href="10.1016/j.apenergy.2020.115484" style="font-weight: bold; text-decoration: none;">Applied Energy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">A unified ecological assessment of a solar concentrating plant based on an integrated approach joining cosmic exergy analysis with ecological indicators</p>
  <p style="font-style: italic; text-align: left;">Fan, Y.<sup>#</sup>, <strong>Wu, X.</strong><sup>#</sup>, Wu, X.F., Li, C., Yang, Q., Hayat, T., Alsaedi, A., Wang, P.<sup>✽</sup>, Chen, G.<sup>✽</sup> </p>
  <p><a href="10.1016/j.rser.2020.109934" style="font-weight: bold; text-decoration: none;">Renewable and Sustainable Energy Reviews</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Carbon emissions embodied in the global supply chain: Intermediate and final trade imbalances</p>
  <p style="font-style: italic; text-align: left;"><strong>Wu, X.</strong>, Guo, J., Li, C., Chen, G.<sup>✽</sup>, Ji, X.<sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Science of The Total Environment</a></p>
</div>

## 2019

<div class="article">
  <p style="font-weight: bold; text-align: left;">Global socio-hydrology: An overview of virtual water use by the world economy from source of exploitation to sink of final consumption</p>
  <p style="font-style: italic; text-align: left;"><strong>Wu, X.</strong>, Guo, J., Li, C., Shao, L., Han, M., Chen, G.<sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Hydrology</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Energy use in world economy from household-consumption-based perspective</p>
  <p style="font-style: italic; text-align: left;"><strong>Wu, X.</strong>, Guo, J., Ji, X., Chen, G.<sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Energy Policy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Quantifying global CH<sub>4</sub> and N<sub>2</sub>O footprints</p>
  <p style="font-style: italic; text-align: left;">Tian, W., <strong>Wu, X.</strong>, Zhao, X., Ma, R., Zhang, B.<sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Environmental Management</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Global overview for energy use of the world economy: Household-consumption-based accounting based on the world input-output database (WIOD)</p>
  <p style="font-style: italic; text-align: left;">Chen, G.<sup>#，✽</sup>, <strong>Wu, X.</strong><sup>✽</sup>, Guo, J., Meng, J., Li, C</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Energy Economics</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Energy use by globalized economy: Total-consumption-based perspective via multi-region input-output accounting</p>
  <p style="font-style: italic; text-align: left;"><strong>Wu, X.</strong>, Guo, J., Meng, J., Chen, G.<sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Science of the Total Environment</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Water footprint of thermal power in China: Implications from the high amount of industrial water use by plant infrastructure of coal-fired generation system</p>
  <p style="font-style: italic; text-align: left;"><strong>Wu, X.</strong>, Ji, X., Li, C., Xia, X., Chen, G.<sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Energy Policy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Freshwater costs of seawater desalination: Systems process analysis for the case plant in China</p>
  <p style="font-style: italic; text-align: left;">Liu, S., Zhang, G., Han, M.<sup>✽</sup>, <strong>Wu, X.</strong>, Li, Y., Chen, K., Meng, J., Shao, L., Wei, W., Chen, G.<sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>

## 2018

<div class="article">
  <p style="font-weight: bold; text-align: left;">An overview of arable land use for the world economy: From source to sink via the global supply chain</p>
  <p style="font-style: italic; text-align: left;"><strong>Wu, X.</strong><sup>#</sup>, Guo, J.<sup>#</sup>, Han, M., Chen, G.<sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Land Use Policy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">The striking amount of carbon emissions by the construction stage of coal-fired power generation system in China</p>
  <p style="font-style: italic; text-align: left;"><strong>Wu, X.</strong>, Guo, J., Chen, G.<sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Energy Policy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Contaminant transport from point source on water surface in open channel flow with bed absorption</p>
  <p style="font-style: italic; text-align: left;">Guo, J., <strong>Wu, X.</strong>, Jiang, W.*, Chen, G.<sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Hydrology</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Ultra-high voltage network induced energy cost and carbon emissions</p>
  <p style="font-style: italic; text-align: left;">Wei, W.<sup>#</sup>, <strong>Wu, X.</strong><sup>#</sup>, Li, J.<sup>✽</sup>, Jiang, X., Zhang, P., Zhou, S., Zhu, H., Liu, H., Chen, H., Guo, J., Chen, G.<sup>✽</sup>  </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>

## 2017

<div class="article">
  <p style="font-weight: bold; text-align: left;">Energy and water nexus in power generation: The surprisingly high amount of industrial water use induced by solar power infrastructure in China</p>
  <p style="font-style: italic; text-align: left;"><strong>Wu, X.</strong>, Chen, G.<sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Applied Energy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Coal use for world economy: Provision and transfer network by multi-region input-output analysis</p>
  <p style="font-style: italic; text-align: left;">Xia, X.<sup>✽</sup>, Chen, B., <strong>Wu, X.</strong>, Hu, Y., Liu, D., Hu, C </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">A three-scale input-output analysis of water use in a regional economy: Hebei province in China</p>
  <p style="font-style: italic; text-align: left;">Liu, S., <strong>Wu, X.</strong>, Han, M.<sup>✽</sup>, Zhang, J., Chen, B., Wu, X.F., Wei, W., Li, Z<sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>

## 2016

<div class="article">
  <p style="font-weight: bold; text-align: left;">Progress and prospect of CCS in China: Using learning curve to assess the cost-viability of a 2×600MW retrofitted oxyfuel power plant as a case study</p>
  <p style="font-style: italic; text-align: left;"><strong>Wu, X.</strong><sup>#</sup>, Yang, Q.<sup>#</sup>, Chen, G.<sup>✽</sup>, Hayat, T., Alsaedi, A</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Renewable and Sustainable Energy Reviews</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Embodied energy analysis for coal-based power generation system-highlighting the role of indirect energy cost</p>
  <p style="font-style: italic; text-align: left;"><strong>Wu, X.</strong><sup>#</sup>, Xia, X.<sup>#</sup>, Chen, G.<sup>✽</sup>, Wu, X.F., Chen, B</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Applied Energy</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Virtual water accounting for a building construction engineering project with nine sub-projects: a case in E-town, Beijing</p>
  <p style="font-style: italic; text-align: left;">Han, M., Chen, G.<sup>✽</sup>, Meng, J., <strong>Wu, X.</strong>, Alsaedi, A., Ahmad, B</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Journal of Cleaner Production</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Critical Length of Contaminant Cloud in a Three-Layer Wetland: Multi-scale Analysis for Environmental Dispersivity</p>
  <p style="font-style: italic; text-align: left;">Li, Z.<sup>✽</sup>, Wang, P.<sup>✽</sup>, Sun, T., An, Y., <strong>Wu, X.</strong></p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Wetlands</a></p>
</div>

## 2015 and Before

<div class="article">
  <p style="font-weight: bold; text-align: left;">Renewability and sustainability of biogas system: Cosmic exergy based assessment for a case in China</p>
  <p style="font-style: italic; text-align: left;">Wu, X.F., Chen, G.<sup>✽</sup>, <strong>Wu, X.</strong>, Yang, Q., Alsaedi, A., Hayat, T., Ahmad, B. </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Renewable and Sustainable Energy Reviews</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Taylor dispersion in a packed pipe with wall reaction: Based on the method of Gill’s series solution</p>
  <p style="font-style: italic; text-align: left;">Wang, P., Li, Z.<sup>✽</sup>, <strong>Wu, X.</strong>, An, Y. </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">International Journal of Heat and Mass Transfer</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Analysis of rural household energy consumption and renewable energy systems in Zhangziying town of Beijing</p>
  <p style="font-style: italic; text-align: left;">Li, X.<sup>#</sup>, Lin, C.<sup>#，✽</sup>, Wang, Y., Zhao, L., Duan, N., <strong>Wu, X.</strong></p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Ecological Modelling</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Vertical specialization, global trade and energy consumption for an urban economy: A value added export perspective for Beijing</p>
  <p style="font-style: italic; text-align: left;">Xia, X.<sup>✽</sup>, Hu, Y., Chen, G., Alsaedi, A., Hayat, T., <strong>Wu, X.</strong></p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Ecological Modelling</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Structure decomposition analysis for energy-related GHG emission in Beijing: Urban metabolism and hierarchical structure</p>
  <p style="font-style: italic; text-align: left;">Xia, X.<sup>✽</sup>, Hu, Y.<sup>✽</sup>, Alsaedi, A., Hayat, T., <strong>Wu, X.</strong>, Chen, G.</p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Ecological Informatics</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Sustainability of a typical biogas system in China: Emergy-based ecological footprint assessment</p>
  <p style="font-style: italic; text-align: left;">Wu, X.F., Yang, Q.<sup>✽</sup>, Xia, X., Wu, T., <strong>Wu, X.</strong>, Shao, L., Hayat, T., Alsaedi, A., Chen, G.<sup>✽</sup> </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Ecological Informatics</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Ecological accounting for an integrated “pig–biogas–fish” system based on emergetic indicators</p>
  <p style="font-style: italic; text-align: left;">Wu, X.F.<sup>#</sup>, <strong>Wu, X.</strong><sup>#</sup>, Li, J.<sup>#</sup>, Xia, X., Mi, T., Yang, Q., Chen, G.<sup>✽</sup>, Chen, B., Hayat, T., Alsaedi, A. </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Ecological Informatics</a></p>
</div>

<div class="article">
  <p style="font-weight: bold; text-align: left;">Bibliometric indicators for sustainable hydropower development</p>
  <p style="font-style: italic; text-align: left;">Han, M.<sup>#</sup>, Sui, X.<sup>#</sup>, Huang, Z.<sup>✽</sup>, <strong>Wu, X.</strong>, Xia, X., Hayat, T., Alsaedi, A. </p>
  <p><a href="10.1016/j.ecolecon.2023.107967" style="font-weight: bold; text-decoration: none;">Ecological Informatics</a></p>
</div>