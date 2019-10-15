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
                    <h2 class="section-heading">Teaching</h2>
                    <h3 class="section-subheading text-muted">
                        I am an assistant professor in the <a href="http://columbia.edu">Columbia University</a>
                        <a href="http://eesc.columbia.edu">Department of Earth and Environmental Sciences</a>. These are the courses I am currently teaching.
                    </h3>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row">
            {% for course in site.data.courses %}
                <div class="col-md-4 col-sm-4 portfolio-item">
                    <a href="{{ course.url }}" class="portfolio-link" data-toggle="modal">
                        <div class="portfolio-hover">
                            <div class="portfolio-hover-content">
                                <i class="fa fa-plus fa-3x"></i>
                            </div>
                        </div>
                        <img src="img/teaching/{{ course.pic }}" class="img-responsive" alt="">
                    </a>
                    <div class="portfolio-caption">
                        <h4>{{ course.title }}</h4>
                        <p class="text-muted">{{ course.description }}</p>
                    </div>
                </div>
            {% endfor %}
            </div>
        </div>
