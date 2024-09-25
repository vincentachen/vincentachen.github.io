---
layout: default
title: "Vincent A. Chen"
---


<section class="hero-section">
    <div class="page-padding">
        <div class="padding-top padding-large">
            <div class="bigcontainer">
                <div class="hero-grid">
                    <div class="hero-grid-left">
                        <img src="/assets/images/headshotcircle.png" alt="Vincent Alexander Chen" class="profile-img">
                    </div>
                    <div class="hero-grid-right">
                        <h1 class="display-4">Hi, I'm Vincent!</h1>
                        <h2 >UC Berkeley Grad</h2>
                        <p>B.A. Integrated Biology and B.A. Economics</p>
                        <div class="social-links">
                            <a href="https://www.linkedin.com/in/vincentchenberkeley" target="_blank" class="icon-link">
                                <i class="fab fa-linkedin"></i>
                            </a>
                            <a href="mailto:vinnychen@berkeley.edu" class="icon-link">
                                <i class="fas fa-envelope"></i>
                            </a>
                            <a href="https://github.com/vincentachen" target="_blank" class="icon-link">
                                <i class="fab fa-github"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<section class="aboutme">
    <div class="page-padding">
        <div class="bigcontainer">
            <div class="padding-top padding-large">
                <div class="aboutme-grid">
                    <div class="aboutme-text"> About Me</div>
                    <div class="margin-bottom margin-large">
                        <div class="aboutme-inner-grid">
                            <div class="aboutme-inner-item">
                                <h5>EDUCATION</h5>
                                <p>I am passionate about healthcare technology, health economics, and financial analysis. My goal is to apply my skills in data analysis and project management to help companies optimize their healthcare solutions.</p>
                            </div>
                            <div class="line"></div>
                            <div class="aboutme-inner-item">
                                <h5>EXPERIENCE</h5>
                                <p>I am passionate about healthcare technology, health economics, and financial analysis. My goal is to apply my skills in data analysis and project management to help companies optimize their healthcare solutions.</p>
                            </div>
                            <div class="line"></div>
                            <div class="aboutme-inner-item">
                                <h5>INTERESTS</h5>
                                <p>I am passionate about healthcare technology, health economics, and financial analysis. My goal is to apply my skills in data analysis and project management to help companies optimize their healthcare solutions.</p>
                            </div>
                            <div class="line"></div>                                                        
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<section class="selected-projects">
    <div class="page-padding">
        <div class="padding-top padding-medium">
            <div class="bigcontainer">
                <div class="padding-bottom padding-large">
                    <div class="margin-bottom margin-medium">
                        <div class="margin-bottom margin-small">
                            <h6>MY WORK</h6>
                        </div> 
                        <div class="margin-bottom margin-medium">
                            <div class="line"></div>
                        </div>
                        <div class="selected-projects-heading">
                            <div class="aboutme-text">Selected Projects</div>
                            <a href="/projects" class="button small w-inline-block">
                                <div class="button-inner">
                                    <div class="button-inner-text">All Projects</div>
                                </div>
                            </a>
                        </div> 
                    </div> 
                    <div class="selected-projects-wrapper">
                        <div class="row g-4">
                            {% assign featured_projects = site.projects | where: "tags", "featured" %}
                            {% for project in featured_projects limit: 3 %}
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
                    </div>    
                </div> 
            </div> 
        </div> 
    </div> 
</section> 



