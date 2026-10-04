---
layout: academic
title: "Curriculum vitae"
permalink: /cv/
description: "Education, research, publications, honors, and skills of Yuanchen Tang. Updated October 2026."
redirect_from:
  - /resume
---
<header class="page-intro">
  <p class="eyebrow">Academic background</p>
  <h1>Curriculum vitae</h1>
  <p>Yuanchen Tang <span class="inline-note">· Updated {{ site.data.academic.updated }}</span></p>
  <a class="button" href="{{ '/files/Yuanchen_Tang_CV.pdf' | relative_url }}" download>Download CV <span class="file-label">PDF</span></a>
</header>
<section class="content-section" aria-labelledby="education-title">
  <div class="section-heading"><h2 id="education-title">Education</h2></div>
  {% include academic-education.html %}
</section>
<section class="content-section" aria-labelledby="interests-title">
  <div class="section-heading"><h2 id="interests-title">Research interests</h2></div>
  <p>My research lies at the intersection of computer science and economics, particularly machine learning, algorithmic game theory, and reinforcement learning. I am also interested in AI economics.</p>
</section>
<section class="content-section" aria-labelledby="cv-papers-title">
  <div class="section-heading"><h2 id="cv-papers-title">Papers</h2></div>
  {% include academic-papers.html %}
</section>
<section class="content-section" aria-labelledby="experience-title">
  <div class="section-heading"><h2 id="experience-title">Research experience</h2></div>
  {% include academic-research.html %}
</section>
<section class="content-section" aria-labelledby="awards-title">
  <div class="section-heading"><h2 id="awards-title">Selected honors &amp; awards</h2></div>
  <ul class="award-list">{% for award in site.data.academic.awards %}<li><span>{{ award.title }}</span><span class="entry-date">{{ award.year }}</span></li>{% endfor %}</ul>
</section>
<section class="content-section" aria-labelledby="skills-title">
  <div class="section-heading"><h2 id="skills-title">Skills &amp; interests</h2></div>
  <dl class="skills-list">
    <dt>Programming</dt><dd>C++, Python, Lean, LaTeX</dd>
    <dt>Languages</dt><dd>Chinese (native), English (fluent). TOEFL iBT: 107/120.</dd>
    <dt>TOEFL scores</dt><dd>Reading 29 · Listening 30 · Speaking 23 · Writing 25 (best 27)</dd>
    <dt>Sports</dt><dd>Table tennis (over 10 years), basketball, baseball</dd>
  </dl>
</section>
