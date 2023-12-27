---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}**,<br>
I am a physics Ph.D. student at UCI. My primary interests are understanding exoplanets and their hosts. Most of my research relies on time-series data to characterize transits and radial velocity signals. 

<div class="row">
{% include about/skills.html title="Research Interests" source=site.data.programming-skills %}
{% include about/skills.html title="Science Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html source=site.data.timeline%}
{% include about/publication.html  source=site.data.timeline%}
</div>
