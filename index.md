---
layout: default
---

<div class="parallax">
  <section id="landing" class="parallax__layer parallax__layer--base">
    <div class="section-content">
      <h1>{{ site.project_title }}</h1>
      <div class="team">
        <h2>Team Members</h2>
        {% for member in site.team_members %}
        <p>{{ member.name }}</p>
        {% endfor %}
        <h2>Mentor</h2>
        <p>{{ site.mentor_name }}</p>
      </div>
      <div class="links">
        <a href="{{ site.github_link }}" target="_blank">
          <i class="fab fa-github icon"></i>
        </a>
        <a href="{{ site.drive_link }}" target="_blank">
          <i class="fab fa-google-drive icon"></i>
        </a>
      </div>
    </div>
  </section>

  <section id="introduction" class="parallax__layer parallax__layer--back">
    <div class="section-content">
      <h2>Introduction</h2>
      <p>
        Write your project introduction here. Explain the main goals,
        motivation, and context of your project. This section should give
        readers a clear understanding of what your project aims to achieve.
      </p>
    </div>
  </section>

  <section id="methodology" class="parallax__layer parallax__layer--base">
    <div class="section-content">
      <h2>Methodology</h2>
      <p>
        Detail your project's methodology here. Include information about:
        - The approaches you used
        - Technologies and tools employed
        - Research methods
        - Data collection and analysis procedures
      </p>
    </div>
  </section>

  <section id="workflow" class="parallax__layer parallax__layer--back">
    <div class="section-content">
      <h2>Workflow and Discussion</h2>
      <p>
        Describe your project workflow and discuss the results here. Include:
        - Project timeline and milestones
        - Challenges faced and solutions implemented
        - Results and findings
        - Analysis and interpretation of results
        - Future improvements and recommendations
      </p>
    </div>
  </section>
</div>