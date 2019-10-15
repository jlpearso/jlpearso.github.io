---
title: "Research"
# layout: collection
permalink: /research/
author_profile: true
# collection: research
# entries_layout: grid
header:
  image: /assets/images/2dturb_header.jpg
  caption: "[Simulated Ocean Turbulence.](https://ocean-next.fr/expertise/natl60/)"
---

<div class="container">
            <div class="row">
                <div class="col-lg-12 text-center">
                    <h2 class="section-heading text-muted">
                    <h3 class="section-subheading text-muted">
                        I am a graduate student at <a href="http://brown.edu">Brown University</a>
                        <a href="https://www.brown.edu/academics/earth-environmental-planetary-sciences/">Department of Earth, Environmental, and Planetary Sciences</a>. These are my current and past research projects..
                    </h3>
                </div>
            </div>
        </div>
<div class="container">
        <div class="row">
            {% for project in site.data.projects %}
                <div class="col-md-4 col-sm-4 portfolio-item">
                    <a href="{{ project.url }}" class="portfolio-link" data-toggle="modal">
                        <div class="portfolio-hover">
                            <div class="portfolio-hover-content">
                                <i class="fa fa-plus fa-3x"></i>
                            </div>
                        </div>
                        <img src="assests/images/{{ project.pic }}" class="img-responsive" alt="">
                    </a>
                    <div class="portfolio-caption">
                        <h4>{{ project.title }}</h4>
                        <p class="text-muted">{{ project.description }}</p>
                    </div>
                </div>
            {% endfor %}
            </div>
        </div>
