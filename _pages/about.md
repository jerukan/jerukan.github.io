---
permalink: /
title: "Yo what's up"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a first year PhD student in Computer Science at Purdue advised by [Prof. Sotiris Nousias](https://sotirisnousias.com/). I do computational imaging things.

I was a Master's student in ECE (Machine Learning & Data Science) at UC San Diego, and was co-advised by [Prof. Nick Antipa](https://www.nickantipa.com/) and [Prof. Sophia Merrifield](https://cordc.ucsd.edu/people/sophia-merrifield/). My research was using deep-sea video for the rigid 6DoF pose estimation of buried objects in the seabed.

During my undergrad, I majored in Probability and Statistics at UC San Diego, and did oceanographic research with X-Band and HF radar for [CORDC](https://cordc.ucsd.edu/).

This page is still under construction.

<h2 id="publications">Publications</h2>

{% include base_path %}

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also view on <a href="{{site.author.googlescholar}}">Google Scholar</a>.</div>
{% endif %}

<p class="pub-legend"><span class="pub-legend__swatch"></span> Highlighted work.</p>

<div class="pub-list">
  {% assign publications = site.publications | sort: 'date' | reverse %}
  {% for post in publications %}
    {% include archive-single-publication.html %}
  {% endfor %}
</div>

{% include publication-authors.html %}
