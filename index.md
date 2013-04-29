---
layout: page
title: Welcome
---

{% include JB/setup %}

<!-- My name is Alejandro Calderón-Urrea.  I'm a professor of Developmental Biology at California State University, Fresno. The purpose of this site is to introduce you to the different activities that are going on in my research/teaching program. Feel free to send me an e-mail with comments and suggestions. -->

{{ site.test }}

{% for item in site.menu.people.current limit:1 offset:0 %}
  {{ item.name }} is a {{ item.position }} interested in {{ item.interest }}.

<img src="{{ item.pic }}" alt="Smiley face">

{% endfor %}

<h1 id="Research">Research</h1>

{% include research.md %}

<h1 id="People">People</h1>

<h1 id="Publications">Publications</h1>

<h1 id="Positions">Positions</h1>

<h1 id="Courses">Courses</h1>

<h1 id="Links">Links</h1>

Research and teaching activities in our laboratory are possible due to funding from the following programs and funding agencies:

###California State University, Fresno:

College of Science and Mathematics Assign Time for Research

College of Science and Mathematics Faculty Sponsored Student Research

The students in my lab are recipients of Associated Students Inc. (ASI) Research Grants

###Extramural Funding and Agencies:

California Agricultural Research Initiative (ARI-CATI): “A novel biotechnology approach for plant protection against nematodes: the use of programmed cell death”. 2002-2005.

Program Director. NIH-MBRS-RISE: MBRS-RISE Program at California State University, Fresno. August 2005-July 2009.

CSUPERB: "Application of 4D microscopy to study early development in the plant parasitic nematode Meloidogyne incognita". 2005-2006.


<h1 id="contact">Contact</h1>

{% include contact.md %}