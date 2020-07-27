---
layout: single
title: " "
excerpt: " "
header:
  overlay_color: "#000"
  overlay_filter: "0"
  overlay_image: /assets/images/near-ilulissat.jpg
author_profile: true
---

I am a climate scientist, geobiologist, and climate policy scholar. I serve at [Rutgers University](http://www.rutgers.edu/) as Director of the [Rutgers Institute of Earth, Ocean & Atmospheric Sciences](http://eoas.rutgers.edu/) and as a professor in
the [Department of Earth & Planetary Sciences](http://geology.rutgers.edu/).  

I also co-direct Rutgers' transdisciplinary [Coastal Climate Risk & Resilience (C2R2) initiative](http://c2r2.rutgers.edu), a training program which brings graduate students in the natural sciences, social sciences, engineering, and urban planning together with coastal stakeholders to tackle the challenges that climate change poses to the world's coastlines.

I'm one of the directors of the [Climate Impact Lab](http://www.impactlab.org), a collaboration of more than two dozen climate scientists, economists, data scientists and policy scholars, working to bring Big Data approaches to the assessment of the economic risks of climate change.

<div style="float: left; margin: 20px; max-width: 150px; box-shadow: 10px 10px 5px #888888; border:  1px solid gray;"><a href="http://www.climateprospectus.org" target="_blank"><img src="/assets/images/EconomicRisksOfCC.jpg"></a></div>

My [research](research/) focuses on understanding uncertainty in past and future climate change, with major emphases on sea-level change and on the interactions between physical climate change and the economy.

I am a lead author of the [Intergovernmental Panel on Climate Change’s](http://www.ipcc.ch/) forthcoming (2021) Sixth Assessment Report, the U.S. Global Change Research Program's 2017 [_Climate Science Special Report_](https://science2017.globalchange.gov) and [_Economic Risks of Climate Change: An American Prospectus_](http://www.climateprospectus.org/). I was a contributing author to the [Intergovernmental Panel on Climate Change](http://www.ipcc.ch)’s Fifth Assessment Report, and have served on sea-level rise expert groups for several states and cities. 

In addition to the  Rutgers  [Department of Earth & Planetary Sciences](http://geology.rutgers.edu/) and the
[Rutgers Institute of Earth, Ocean, and Atmospheric Sciences](http://eoas.rutgers.edu/), I am also a member of the [Rutgers Climate Institute](http://climatechange.rutgers.edu) and the [Rutgers Energy Institute](http://rei.rutgers.edu/). I am affiliated with Rutgers graduate programs in [Atmospheric Sciences](http://atmos.rutgers.edu), [Geological Sciences](http://eps.rutgers.edu), [Oceanography](http://marine.rutgers.edu), [Statistics](http://statistics.rutgers.edu), and [Planning and Public Policy](http://policy.rutgers.edu/).


Prior to joining the Rutgers faculty, I served as a [AAAS Science & Technology Policy Fellow](http://fellowships.aaas.org/) in the [U.S. ](http://www.energy.gov)[Department of Energy](http://www.energy.gov)'s Office of Policy and International Affairs and as a [Science, Technology, and Environmental Policy](http://www.princeton.edu/step/) postdoctoral research fellow at Princeton University. I received my Ph.D. in geobiology from Caltech and my undergraduate degree in geophysical sciences from the University of Chicago. 

 
#### [In the media](http://www.google.com/search?hl=en&gl=us&tbm=nws&q="Robert+Kopp"+OR+"Bob+Kopp"+Rutgers)

* [Science on the Hill (June 2020)](https://bit.ly/2YbqNPi)
* [NJTV News (December 2019)](https://bit.ly/35PRhXP)
* [_The Conversation_ (Apil 2019)](https://theconversation.com/climate-research-needs-to-change-to-help-communities-plan-for-the-future-113427)
* [Resources Radio (January 2019)](https://soundcloud.com/resourcesradio/demystifying-sea-level-rise-with-robert-kopp-of-rutgers-university)
* [Radio Times with Mary Cummings-Jordan [WHYY] (November 2018)](https://goo.gl/H2Q4oa)
* [Science Friday (November 2018)](https://goo.gl/JVgHNp)
* [E&E News Off Topic (November 2018)](https://goo.gl/M2FfqL)
* [Reddit AMA (December 2017)](https://doi.org/10.15200/winn.151213.32636)
* [_New York Times_ (November 2017)](https://nyti.ms/2hLb7MS)
* [_The Conversation_ (June 2017)](https://goo.gl/EvRo1X)
* [_The Conversation_ (November 2016)](https://goo.gl/OWovmZ)
* [_The Conversation_ (June 2016)](https://goo.gl/nOadXV)
* [Radio Times with Marty Moss-Coane [WHYY] (February 2016)](http://goo.gl/zWLUsW)
*  [PRI's The World (February 2016)](http://goo.gl/RuhXl3)
* [_New York Times_ Sunday Review (June 2015)](http://nyti.ms/1JyXkk7)
* [_Rutgers Today_ (Dec. 2014)](http://news.rutgers.edu/feature/earth-scientists-urgent-mission-takes-shape-rutgers/20141217)
* [Radio Times with Marty Moss-Coane [WHYY] (July 2014)](http://goo.gl/DfPnc9)
* [_New York Times_ Sunday Review (Nov. 2012)](http://nyti.ms/TcArGg)

<div id="index" style="width: 100%" >
     {% for post in site.posts limit:1 %}
    <h2><a href="{{ site.url}}/posts/">Recent Posts</a></h2>
    {% endfor %}
  {% for post in site.posts limit:3 %}    
    <article>
      {% if post.link %}
        <h4 class="link-post"><a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a> <a href="{{ post.link }}" target="_blank" title="{{ post.title }}"><i class="fa fa-link"></i></a></h4>
      {% else %}
        <h4><a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></h4>
        <p>{{ post.excerpt | strip_html | truncate: 160 }}</p>
      {% endif %}
    </article>
    {% endfor %}
	
	</div><!-- /#index -->


