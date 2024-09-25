---
layout: default
title: Projects
permalink: /projects/
---

<section class="hero-section">
    <div class="page-padding">
        <div class="padding-top padding-large">
            <div class="bigcontainer">
                <div class="hero-grid">
                </div>
            </div>
        </div>
    </div>
</section>

<section class="projects-section">
  <div class="padding-top padding-large">
    <div class="container mt-5">
      <h1 class="text-left mb-4">My Projects</h1>
      <p class="text-left mb-2">A collection of my work across various fields, including financial modeling, machine learning, and more.</p>
      <div class="line mb-4"></div>
      <div class="row g-4">
        {% for project in site.projects %}
          <div class="col-md-4">
            <div class="card project-card">
              <a href="{{ project.url }}">
                <img class="card-img-top" src="{{ project.image }}" alt="Project {{ project.title }} Image">
                <div class="card-body">
                  <h5 class="card-title">{{ project.title }}</h5>
                  <p class="card-text">{{ project.summary }}</p>
                </div>
              </a>
            </div>
          </div>
        {% endfor %}
      </div> <!-- End Row -->
    </div> <!-- End Container -->
  </div>
</section>