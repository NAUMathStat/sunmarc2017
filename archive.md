---
layout: page
title: Archive
---

Note that pages and posts are listed in reverse chronological order.

### Seminars ###
- Department Colloquium
    - [Fall 2016]({{ site.baseurl }}/colloquiumFall2016)
    - [Spring 2016]({{ site.baseurl }}/colloquiumSpring2016)
    - [Fall 2015]({{ site.baseurl }}/colloquiumFall2015)
    - [Spring 2015]({{ site.baseurl }}/colloquiumSpring2015)
- Algebra, Combinatorics, Geometry, and Topology (ACGT) Seminar
    - [Fall 2016]({{ site.baseurl }}/acgtFall2016)
    - [Spring 2016]({{ site.baseurl }}/acgtSpring2016)
    - [Fall 2015]({{ site.baseurl }}/acgtFall2015)
    - [Spring 2015]({{ site.baseurl }}/acgtSpring2015)
- Applied Math Seminar (AMS)
    - [Fall 2016]({{ site.baseurl }}/amsFall2016)
    - [Spring 2016]({{ site.baseurl }}/amsSpring2016)
    - [Fall 2015]({{ site.baseurl }}/amsFall2015)
    - [Spring 2015]({{ site.baseurl }}/amsSpring2015)
- Friday Afternoon Mathematics Undergraduate Seminar (FAMUS)
    - [Fall 2016]({{ site.baseurl }}/famusFall2016)
    - [Spring 2016]({{ site.baseurl }}/famusSpring2016)
    - [Fall 2015]({{ site.baseurl }}/famusFall2015)
    - [Spring 2015]({{ site.baseurl }}/famusSpring2015)
- Teaching Showcase
    - [Fall 2015]({{ site.baseurl }}/teachingFall2015)
    - [Spring 2015]({{ site.baseurl }}/teachingSpring2015)
    - [Fall 2014]({{ site.baseurl }}/teachingFall2014)

### Weekly Posts ###
{% for post in site.posts %}
- {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ site.baseurl }}/{{ post.url }})
{% endfor %}
