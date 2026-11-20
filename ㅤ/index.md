---
layout: default
title: Archive
---

## Welcome to the Isekai Archive.

<!--<center><img style="border-radius:8px;" width="100%" src="../assets/img/banner5.jpg" alt="Banner"></center>-->
<!--![Header](https://capsule-render.vercel.app/api?type=Waving&color=timeGradient&height=100&animation=fadeIn&section=header&text=IDK&fontSize=100)-->

A type of <b>wallet</b> containing <i>money.</i>

<ul>
  {% for post in site.blog %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<br />
<br />
<div align="left">
<a class="left" href="/blog/">← Previous</a>
</div>

<a onclick="topFunction()" id="btn-to-top">Top</a> 
