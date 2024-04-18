---
layout: single
title: " "
excerpt: " "
header:
  image: /assets/images/near-ilulissat.jpg
author_profile: true
---

I am a climate and sea-level scientist and a climate policy scholar. I serve at [Rutgers University](http://www.rutgers.edu/) as a distinguished professor in
the [Department of Earth & Planetary Sciences](http://eps.rutgers.edu/).  I lead Rutgers' [Earth System Science and Policy Lab](https://earthscipol.net/); please see the Lab website if you are interested in our work or in joining our team. 

I direct the [Megalopolitan Coastal Transformation Hub](https://www.coastalhub.org/) (MACH), an NSF-funded consortium led by Rutgers. MACH works within the Philadelphia-New York City-New Jersey region to both 1) facilitate flexible, equitable, and robust multidecadal planning to manage climate risk, and 2) advance the scientific understanding of how interactions among coastal climate hazards, changing landforms, and human decisions shape climate risk.  

I'm one of the directors of the [Climate Impact Lab](http://www.impactlab.org), a collaboration of more than three dozen climate scientists, economists, data scientists and policy scholars, working to bring Big Data approaches to the assessment of the economic risks of climate change.

My [research](research/) focuses on understanding uncertainty in past and future climate change, with major emphases on sea-level change, the interactions between physical climate change and the economy, and the use of climate risk information to inform decisionmaking.

I am a lead author of the [Intergovernmental Panel on Climate Change’s](http://www.ipcc.ch/) 2021 Sixth Assessment Report, the U.S. Global Change Research Program's 2017 [Fourth National Climate Assessment](https://science2017.globalchange.gov) and [_Economic Risks of Climate Change: An American Prospectus_](http://www.climateprospectus.org/). I have also served on sea-level rise expert groups for several states and cities. 

From 2021-2023, I served as Founding Co-Director of the [Rutgers Office of Climate Action](https://climateaction.rutgers.edu/). From 2017-2021, I served as director of the [Rutgers Institute of Earth, Ocean, and Atmospheric Sciences (EOAS)](http://eoas.rutgers.edu/). In addition to the  [Department of Earth & Planetary Sciences](http://geology.rutgers.edu/) and EOAS, I am also a member of the [Rutgers Climate Institute](http://climatechange.rutgers.edu) and the [Rutgers Energy Institute](http://rei.rutgers.edu/). I am affiliated with Rutgers graduate programs in [Atmospheric Sciences](http://atmos.rutgers.edu), [Geological Sciences](http://eps.rutgers.edu), [Oceanography](http://marine.rutgers.edu), [Statistics](http://statistics.rutgers.edu), and [Planning and Public Policy](http://policy.rutgers.edu/).


Prior to joining the Rutgers faculty, I served as a [AAAS Science & Technology Policy Fellow](http://fellowships.aaas.org/) in the [U.S. ](http://www.energy.gov)[Department of Energy](http://www.energy.gov)'s Office of Policy and International Affairs and as a [Science, Technology, and Environmental Policy](http://www.princeton.edu/step/) postdoctoral research fellow at Princeton University. I received my Ph.D. in geobiology from Caltech and my undergraduate degree in geophysical sciences from the University of Chicago. 

 
#### [In the media](http://www.google.com/search?hl=en&gl=us&tbm=nws&q="Robert+Kopp"+OR+"Bob+Kopp"+Rutgers)

* [Deep Convection (August 2023)](https://deep-convection.org/2023/08/28/episode-3-bob-kopp/)
* [Radio Times [WHYY] (August 2021)](https://bit.ly/3CJi5ds)
* [Climate Now (April 2021)](https://bit.ly/3b5iria)
* [Science on the Hill (June 2020)](https://bit.ly/2YbqNPi)
* [NJTV News (December 2019)](https://bit.ly/35PRhXP)
* [Resources Radio (January 2019)](https://soundcloud.com/resourcesradio/demystifying-sea-level-rise-with-robert-kopp-of-rutgers-university)
* [Radio Times [WHYY] (November 2018)](https://goo.gl/H2Q4oa)
* [Science Friday (November 2018)](https://goo.gl/JVgHNp)
* [E&E News Off Topic (November 2018)](https://www.eenews.net/articles/fact-has-become-a-political-issue/)

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


