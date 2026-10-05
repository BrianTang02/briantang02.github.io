---
layout: academic
permalink: /
title: "About"
description: "Yuanchen Tang, a second-year Computer Science Ph.D. student at UIUC working at the intersection of computer science and economics."
redirect_from:
  - /about/
  - /about.html
---
<section class="intro" aria-labelledby="intro-title">
  <p class="eyebrow">Computer science &amp; economics</p>
  <h1 id="intro-title">Yuanchen Tang<span class="name-detail"><span lang="zh">唐元宸</span> <span class="name-divider">/</span> Brian</span></h1>
  <p class="intro-lead">I study how learning and incentives shape the way people and agents interact.</p>
  <p>I am a second-year Ph.D. student in Computer Science at the <a href="https://illinois.edu/">University of Illinois Urbana-Champaign</a>, where I am fortunate to be advised by <a href="https://rutamehta.cs.illinois.edu/">Prof. Ruta Mehta</a> and <a href="https://www.bhaskar-ray-chaudhury.com/">Prof. Bhaskar Ray Chaudhury</a>. My research lies at the intersection of computer science and economics, particularly algorithmic game theory and machine learning. Recently, I have developed an interest in the interplay between AI and economics.</p>
  <p>Previously, I received my B.S. in Computer Science from the <a href="https://cfcs.pku.edu.cn/english/research/turing_program/introduction1/index.htm">Turing Class</a> at <a href="https://www.pku.edu.cn/">Peking University</a>, where I was fortunate to be supervised by <a href="https://cfcs.pku.edu.cn/english/people/faculty/xiaotiedeng/index.htm">Prof. Xiaotie Deng</a>. I also had a wonderful research internship working with <a href="https://zstevenwu.com/">Prof. Steven Wu</a> at Carnegie Mellon University in the summer of 2024.</p>
  <ul class="interest-list" aria-label="Research interests">{% for interest in site.data.academic.interests %}<li>{{ interest }}</li>{% endfor %}</ul>
  <div class="intro-actions"><a class="button" href="{{ '/files/Yuanchen_Tang_CV.pdf' | relative_url }}">View CV <span class="file-label">PDF</span></a><a class="text-link" href="mailto:{{ site.author.email }}">Get in touch <span aria-hidden="true">↗</span></a></div>
</section>
<section class="content-section" id="publications" aria-labelledby="papers-title">
  <div class="section-heading"><h2 id="papers-title">Selected papers</h2><a class="text-link" href="{{ '/publications/' | relative_url }}">All publications <span aria-hidden="true">↗</span></a></div>
  {% include academic-papers.html %}
</section>
<section class="content-section" aria-labelledby="personal-title">
  <div class="section-heading"><h2 id="personal-title">Beyond research</h2></div>
  <p>I have played table tennis for over ten years and also enjoy basketball and baseball. I am a big Stephen Curry fan. Music is another constant in my life: I have a good sense of relative pitch and love listening to voices weave through a melody.</p>
  <p>I enjoy meeting people and noticing patterns in everyday social interactions. That curiosity often finds its way back into the questions I ask in research.</p>
  <p>My <a href="https://en.wikipedia.org/wiki/Erd%C5%91s_number">Erdős number</a> is 3.</p>
</section>
