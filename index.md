---
layout: default
---

# How to make 3D scans of Classical Casts
{% if site.ucam_logo %}
<img src="{{ site.ucam_logo | relative_url}}" alt="University of Cambridge Museums Logo" />
{% endif %}
        
{% if site.class_logo %}
<img src="{{ site.class_logo | relative_url}}" alt="Classical Archaeology logo" width="100"/>
{% endif %}

{% if site.fitz_logo %}
<img src="{{site.fitz_logo | relative_url}}" alt="Fitzwilliam Museum Logo" width="100"/>
{% endif %}

Hello and welcome to this 2 hour workshop on how to make a 3D scan of one of the Classical Archaeology Museum's casts of classical sculptures. By the end of this workshop, you should be equipped to make a scan like this one of the Terme Boxer's head. We will be covering the basics of a technique called photogrammetry.

**If at anytime during this tutorial, you do not understand or need clarification, please stop me and ask.**

<div class="sketchfab-embed-wrapper"><iframe width="500" height="480" src="https://sketchfab.com/models/9ab4421881c74081aa1f02d792dcb857/embed" frameborder="0" allow="autoplay; fullscreen; vr" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

<p style="font-size: 13px; font-weight: normal; margin: 5px; color: #4A4A4A;">
<a href="https://sketchfab.com/models/9ab4421881c74081aa1f02d792dcb857?utm_medium=embed&utm_source=website&utm_campaign=share-popup" target="_blank" style="font-weight: bold; color: #1CAAD9;">Terme Boxer head</a>
by <a href="https://sketchfab.com/danielpett?utm_medium=embed&utm_source=website&utm_campaign=share-popup" target="_blank" style="font-weight: bold; color: #1CAAD9;">danielpett</a>
on <a href="https://sketchfab.com?utm_medium=embed&utm_source=website&utm_campaign=share-popup" target="_blank" style="font-weight: bold; color: #1CAAD9;">Sketchfab</a>
</p>
</div>


## Tutorial pages
{% assign tuts = site.tutorials | sort:"weight" %}
<ul>
{% for tutorial in tuts %}
<li><a href="{{site.baseurl}}{{ tutorial.url }}">{{ tutorial.title }}</a></li>
{% endfor %}
</ul>

This guide is released as CC0. Some contents will have retained rights (eg Thomas Flynn's scans and logos).
