---
title       : NYMviz
subtitle    : Visualizing the New York Marathon 2002 Results
author      : CEL
job         : Coursera DSS "Developing Data Products"
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
output      : 
    html_document:  
        css:    styles.css


--- bg:url(assets/img/New_York_marathon_Verrazano_bridge.jpg)

<hgroup><h2 class="ovr">A Diverse Event</h2></hgroup>

<p class="ovr">Each year, on the first Sunday in November, thousands of runners participate in the <a href="http://en.wikipedia.org/wiki/New_York_City_Marathon">New York City Marathon</a>, which is at once among the premier annual events in elite distance running and the largest marathon in the world.</p>

<p class="ovr">A dataset of a random sample of 1000 runners taken from the finishers of the 2002 New York City Marathon is available as part of the <a href="http://cran.r-project.org/web/packages/UsingR/UsingR.pdf">Package 'UsingR'</a> (see p. 74).  We will create an interactive online application allowing the user to visualize the characteristics of this population and appreciate its diversity along several dimensions: </p>
<ul>
<li class="ovr"><span>gender</span></li>
<li class="ovr"><span>age</span></li>
<li class="ovr"><span>time to finish the race</span></li>
</ul>

<cite>image: By Martineric from Lille, France (Marathon de New York: Verrazano Bridge) [<a href="http://creativecommons.org/licenses/by-sa/2.0">CC BY-SA 2.0</a>], <a href="http://commons.wikimedia.org/wiki/File%3ANew_York_marathon_Verrazano_bridge.jpg">via Wikimedia Commons</a></cite>

--- 

## Both Genders Display a Broad Range of Talents

While the central tendency of male runners' finish time is quicker than that of their female counterparts, there is substantial overlap in abilities between the two genders.



<img src="assets/fig/unnamed-chunk-1.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" width="900px" height="450px" />

---

## Practically All Ages Are Represented

Although the overall trend to slower race times with increased age is evident, what is even more striking is the broad range of performance at each cohort.

<img src="assets/fig/unnamed-chunk-2.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" width="750" height="500" />

---

## NYMviz: A Statistical Appreciation of the Marathon

<span class="callout">NYMviz</span> will allow the user to interact with several views of the 2002 New York Marathon results to reveal visualizations of the distributions of finish times within the entire sample as well as by gender and age.

By engaging the user to activate various views of the dataset, <span class="callout">NYMviz</span> will create a stronger impression of the major features of the dataset than could be achieved by a static presentation of plots and tables alone.

It is our hope that <span class="callout">NYMviz</span> will convey the unique hybrid nature of major marathon events as elite athletic competitions (led by a handful of world-class runners) that are also mass celebrations of an active lifestyle that provide aspirational opportunities for everyone.

## It may even inspire someone to get out and run!
