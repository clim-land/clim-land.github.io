---
title: "Clim-land - Home"
layout: homelay
excerpt: "Allan Lab at Leiden University &rarr; LMU."
sitemap: false
permalink: /
---
# Use this website as a template for your academic research group

This website is powered by [Jekyll](https://jekyllrb.com) and uses some [Bootstrap](http://www.getbootstrap.com) and  [Bootswatch](http://www.bootswatch.com). We tried to make it simple yet adaptable, so that it is easy for you to re-use it for your purpose. 

### Getting started
All pages are written in [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) for easy editing, and [Jekyll](https://jekyllrb.com) uses Liquid for the data-driven pages. The publicaion list, news items, and group members are stored as `.yml` data sheets (plain text) in the `_data folder`, so that one can update the website easily. The pages are in the `_pages` folder. Updating and maintaining is easy using [Github](http://www.github.com) (not worldpress-easy, but there are other advantages (see e.g. [this](https://www.taniarascia.com/make-a-static-website-with-jekyll/), or [this](http://www.webdesignerdepot.com/2015/11/jekyll-against-the-rest-of-the-world/)). [Jekyll](https://jekyllrb.com) takes all the markdown and data files, and creates beautiful `html` files in the `_site` folder.

If you never used [Jekyll](https://jekyllrb.com), read the [wikipedia article](https://en.wikipedia.org/wiki/Jekyll_(software)) article and check out [their website](https://jekyllrb.com). Same for [Github](http://www.github.com), which will host your first website draft. 

Create and open a github account, go to [our repository](https://github.com/allanlab/allanlab), and click 'fork'. This is now your copy of the website, and you can change and adapt it as you want. You don't have to link to us or mention us (but of course we appreciate it). Then change the name of the repository to "your_username" and the name of the branch to "gh-pages".  Your website is now automatically published under *your_username.github.io/your_username/*. Except that it probably still looks like our website. 

To modify the webpage, you can either do everything on on github.com (go to a file, click "edit", then "commit", "push"), or install  [Jekyll](https://jekyllrb.com) on your computer and play with your local copy that you sync with the branch on github.com.  The former is much easier in the beginning, but a bit less convenient once you start rewriting everythint. To get it to work on your computer (and to learn a bit more about [Jekyll](https://jekyllrb.com)), [here](https://www.taniarascia.com/make-a-static-website-with-jekyll/) and [here](https://scotch.io/tutorials/getting-started-with-jekyll-plus-a-free-bootstrap-3-starter-theme) are tutorials on how to use it and how set it up locally. Also, consider using the [Github desktop app](http://www.desktop.github.com), I found it helpful.  

### Customization
Now let's make this *your* website. 

First, go to the `news.ylm`, `publist.ylm`, and `team.ylm` files in the `_data` folder and insert your own data into the data fields. Watch out:  [Jekyll](https://jekyllrb.com) is quite strict about extra or missing spaces etc. Adhere to the format. In the beginning, test each change: commit, push, and check the published website.

For publications, you can add a "1" in the highlight field, then it will be featured prominently. You can add important  news items (red, "news1"), and less important  news items (blue, "news2").

For the news items, just keep adding them. The first 10 will be displayed on the 'home' page.

For the `team.ylm` file

Next, change the content of all files in the `_pages` folder.  To change the title in the homepage, go to `homelay.html` in the `_layout` folder.

Lastly, change the footer and perhaps header appropriately (in `_include`).

You might also want to change the style or theme. I imported style files (in sass) from Bootstrap/Bootwatch, you can replace them with your own (in the `_sass directory`). For small changes, just work on the override stuff in the `main.sass` file in the `CSS` folder. Or change some variables in the `_variables.sass` file, like the background color etc. 

As said, [Jekyll](https://jekyllrb.com) takes all the markdown and data files, and creates beautiful `html` files in the `_site` folder.In the end, either upload these files  to your server, or buy yourself a domain and check the instructions on github on how to host it there.

### Copyright / credit

You can use this template as you please. You don't have to link to us or mention us (but of course we appreciate it). We also welcome it if you send us an email with a link to your website, perhaps we'll publish a list here at some point. 

Comments welcome.

Code released under the MIT License. 

**News: This is the Climate Change and Land Use Research Group！** Wu Xudong's research group is affiliated with the School of Soil and Water Conservation, Beijing Forestry University, and is dedicated to the study of climate change, land use, and economic impacts of disasters.


<div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="4000" data-pause="hover" >
    <!-- Menu -->
    <ol class="carousel-indicators">
        <li data-target="#carousel" data-slide-to="0" class="active"></li>
        <li data-target="#carousel" data-slide-to="1"></li>
        <li data-target="#carousel" data-slide-to="2"></li>
        <li data-target="#carousel" data-slide-to="3"></li>
        <li data-target="#carousel" data-slide-to="4"></li>
        <li data-target="#carousel" data-slide-to="5"></li>
        <li data-target="#carousel" data-slide-to="6"></li>
    </ol>

    <!-- Items -->
    <div class="carousel-inner" markdown="0">
        <div class="item active">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/autumn.jpg" alt="Slide 1" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/xiangshan.jpg" alt="Slide 2" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/SaphireSTM2.jpg" alt="Slide 3" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/lab.jpg" alt="Slide 4" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/Fig_Science_Web.jpg" alt="Slide 5" />
        </div>       
         <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/BSCCO2gap2.jpg" alt="Slide 6" />
        </div>
    </div>
  <a class="left carousel-control" href="#carousel" role="button" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="right carousel-control" href="#carousel" role="button" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>


We are a dynamic research group, at the [Leiden Institute of Physics](http://www.physics.leidenuniv.nl) and soon at [LMU](https://www.physik.lmu.de/en/index.html). Our aim is to explore and understand quantum materials, including strange metals, high-temperature superconductors, and quantum critical electron matter. To this end, we develop new quantum sensing and quantum imaging instrumentation to get the key quantum mechanical degrees of freedom. We want to be able to build the perfect instruments to answer the scientific questions we deem most important (see [Research](research)). 


We are very much looking forward to being part of [LMU physics](https://www.physik.lmu.de/en/index.html)! We will build up our instruments right in the center of the city, in the “Sommerfeldkeller”, where Sommerfeld himself worked. We will exchange ideas with world class groups working in quantum physics, cold-atom many-body physics, and 2d quantum materials.

Our move to LMU will likely start around Summer 2024, depending on the state of renovations. 

Currently, we are located at Leiden University, the birthplace of superconductivity and home to Kamerlingh Onnes, Lorentz, Huygens, Einstein, de Sitter, and others (see e.g. [the wall of signatures from Ehrenfest lecturers](https://www.lorentz.leidenuniv.nl/history/colloquium/muur_heel.html)). 

We are grateful for funding from Leiden University, [LMU ](https://www.lmu.de) [NWO](www.nwo.nl) ([Vidi talent scheme](http://www.nwo.nl/en/research-and-results/programmes/Talent+Scheme) and the [Frontiers in Nanoscience program](https://www.universiteitleiden.nl/en/research/research-projects/science/frontiers-of-nanoscience-nanofront)), and from an [ERC starting and consolidator grants](https://erc.europa.eu/funding/starting-grants).

 **We are  looking for passionate new PhD students, Postdocs, and Master students to join the team** [(more info)]({{ site.url }}{{ site.baseurl }}/vacancies) **!**




<figure class="fourth">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/Logo_BFU1.jpg" style="width: 210px">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/homboldt2.jpg" style="width: 120px">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/Logo_PIK1.jpg" style="width: 120px">

</figure>
