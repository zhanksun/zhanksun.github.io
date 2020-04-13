---
#layout: archive
title: "Talks and Presentations"
permalink: /talks/
author_profile: true
---

## Universities & Institutions

* Data Science Applications Interest Group Seminars (DSAIG), College of Business, City University of Hong Kong, 2017/10.
* Weatherhead School of Management, Case Western Reserve University, 2016/02.
* Department of Management Sciences, City University of Hong Kong, 2016/01.
* Faculty of Business and Economics, University of Hong Kong, 2016/01.
* Faculty of Business, Hong Kong Polytechnic University, 2015/12.
* School of Management, University of Science & Technology of China, 2015/12.
* Haskayne School of Business, University of Calgary, Canada, 2015/02.
* School of Business, University of Alberta, Canada, 2014/10.
* Department of Industrial Engineering, Tsinghua University, 2014/03.
* Department of Statistics and Operations Research, UNC-Chapel Hill, 2013/10.
* Statistical and Applied Mathematical Sciences Institute, Cary, NC, 2013/03.

## Conferences

* INFORMS Annual Meeting, Seattle, WA, November 2019.
* INFORMS Healthcare Conference, MIT, Boston, MA, July 2019.
* CSAMSE 12th Annual Conference, Chengdu, China, July 2019.
* INFORMS APS Conference, Brisbane, Australia, July 2019.
* MSOM International Conference, NUS, Singapore, July 2019.
* The Tenth POMS-HK International Conference, Hong Kong, January 2019.
* The Fifth Young Scholars Workshop in Management Science, Xiamen, January 2019.
* INFORMS Annual Meeting, Phoenix, AZ, November 2018.
* CSAMSE 11th Annual Conference, Ningbo, China, July 2018.
* INFORMS International Meeting, Taipei, June 2018.
* The Ninth POMS-HK International Conference, Hong Kong, January 2018.
* INFORMS Annual Meeting, Houston, TX, November 2017.
* POMS 28th Annual Conference, Seattle, WA, May 2017.
* INFORMS Annual Meeting, Nashville, TN, November 2016.
* CSAMSE 9th Annual Conference, Hefei, China, July 2016.
* POMS 27th Annual Conference, Orlando, FL, May 2016.
* INFORMS Annual Meeting, Philadelphia, PA, November 2015.
* INFORMS Annual Meeting, San Francisco, CA, November 2014.
* INFORMS Annual Meeting, Minneapolis, MN, October 2013.
* INFORMS Annual Meeting, Phoenix, AZ, October 2012.
* UNC-CH University Research Day, March 2012.



{% if site.talkmap_link == true %}
<p style="text-decoration:underline;"><a href="/map.html">Academic Footprint</a></p>
{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
