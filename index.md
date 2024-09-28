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
                        <h2 >Aspiring Analyst</h2>
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
                                <p>I graduated from UC Berkeley, where I studied Integrated Biology and Economics, bridging my passion for healthcare with finance. With coursework in health economics, financial economics, and econometrics, I’m focused on financial and data analysis in biotech. I’m preparing for the CFA exam in May to deepen my knowledge in capital markets and foundational finacial concepts.</p>
                            </div>
                            <div class="line"></div>
                            <div class="aboutme-inner-item">
                                <h5>EXPERIENCE</h5>
                                <p>I had the opportunity to conduct market research at UCSF’s Catalyst Program, where I worked with a team to develop a Target Product Profile (TPP) and present it to industry experts. Additionally, I applied data analysis skills in R and Python during my laboratory research, helping to drive insights from complex datasets.</p>
                            </div>
                            <div class="line"></div>
                            <div class="aboutme-inner-item">
                                <h5>INTERESTS</h5>
                                <p>I like to stay active through swimming and running. I also enjoy learning new things, cooking, and spending time gardening.</p>
                            </div>
                            <div class="aboutme-inner-item">
                                <p></p>
                                <p><strong>Favorite Books:</strong> <em>Behave</em> by Robert Sapolsky, <em>The Omnivore's Dilemma</em> by Michael Pollan, and <em>Animal Spirits</em> by George Akerlof and Robert Shiller.</p>
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



