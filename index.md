---
layout: default
---

<section class="parallax-section" id="landing">
  <div class="section-content">
    <h1>{{ site.sections.landing.title }}</h1>
    <p>Members: {{ site.sections.landing.members }}</p>
    <p>Mentor: {{ site.sections.landing.mentor }}</p>
    <a href="{{ site.sections.landing.github_link }}" class="icon-link"><img src="/assets/github-icon.png" alt="GitHub"></a>
    <a href="{{ site.sections.landing.drive_link }}" class="icon-link"><img src="/assets/drive-icon.png" alt="Google Drive"></a>
  </div>
</section>

<section class="parallax-section" id="introduction">
  <div class="section-content">
    <h2>{{ site.sections.introduction.title }}</h2>
    {{ site.sections.introduction.content | markdownify }}
  </div>
</section>

<section class="parallax-section" id="methodology">
  <div class="section-content">
    <h2>{{ site.sections.methodology.title }}</h2>
    {{ site.sections.methodology.content | markdownify }}
  </div>
</section>

<section class="parallax-section" id="workflow">
  <div class="section-content">
    <h2>{{ site.sections.workflow.title }}</h2>
    {{ site.sections.workflow.content | markdownify }}
  </div>
</section>