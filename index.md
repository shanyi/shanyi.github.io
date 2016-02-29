---
layout: home
permalink: /
title: 
---

Hi, I am Ziwei Huang ([@_hzw](http://twitter.com/_hzw)). I am  studying neuroscience in [Kavli Institute of System Neuroscience, NTNU](http://www.ntnu.edu/kavli/employees/roudi). See my [CV](http://huangziwei.com/cv/) here.

### Recent Posts

<div class="tiles">

{% for post in site.posts limit:5%}
	{% include post-list.html %}
{% endfor %}
</div><!-- /.tiles -->