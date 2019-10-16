---
title: "Research"
layout: splash
permalink: /research/
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#009999"
  overlay_filter: "0.5"
  overlay_image: /assets/images/ocean_eddies.jpg
  caption: ""
excerpt: "Broadly, my interests are at the intersection of physical oceanography and biogeochemistry. I use statistical methods paired with models, observations, and theory to understand the transport and fate of tracers like oil, pathogens, and nutrients in the upper and coastal ocean, with emphasis on submesoscales."
intro: 
  - excerpt: ''
feature_row1:
  - image_path: "https://jennalynnpearson.files.wordpress.com/2019/10/ttd_bottom.gif" 
    alt: "ROMS simulation of passive tracers from two known sources."
    title: "Transport and Dispersion in Narragansett Bay"
    excerpt: 'Structure functions are tools to estimate difficult biogeochemical parameters, and transit-time distributions give information about the transport and fate of pollutants, pathogens, and other tracers. I bridge physical and biogeochemical fields by developing structure function theories for reactive tracers in anisotropic turbulence and analyzing transit-time distributions to understand how river influxes of nutrients as well as oyster parasites propagate and spread in Narragansett Bay.  
    
    
    To the right is a video of a passive tracer advected and diffused by the Regional Ocean Modeling System. The tracer was released at two known source sites for Perkinsus Marinus , an oyster parasite detrimental to both wild and farmed oyster populations in the Bay.'
    url: "https://github.com/jlpearso"
    btn_label: "Repository"
    btn_class: "btn--primary"
feature_row2:
  - image_path: "https://jennalynnpearson.files.wordpress.com/2019/10/front-6.gif" 
    alt: "placeholder image 2"
    title: "Biases in Surface Drifter Statistics"
    excerpt: 'Quasi-Lagrangian drifters are a growing observational platform capable of tracking submesoscale features (timescales of hours to days and horizontal spatial scales of 0.1-10km). Submesoscales play a crucial role in closing the energy budget, controlling biogeochemical distributions, and regulating the mixed layer depth and air-sea exchanges. Drifters are often entrained into submesoscale fronts, or remain in long-lived eddies for extended periods of time, preventing them from adequately sampling the entire domain. I am interested in quantifying statistical biases due to this sampling pattern as they relate to diagnosing spectral energy cascades and fluxes.  
    

Plotted are LASER drifters (purple arrows), and the scaled divergence field (blue to red) from ship-borne X-band radar measurements taken in the Gulf of Mexico in the winter of 2016. Fronts are known to be energetic, and associated with large amounts of turbulence, convergence, and dissipation. Note that the drifters tend to follow the front (dark blue line), and this is one class of bias, called an accumulation bias, that we find strongly affects drifters ability to sample representatively enough to estimate statistics of the entire velocity field.'
    url: "https://github.com/jlpearso"
    btn_label: "Repository"
    btn_class: "btn--primary"
feature_row3:
  - image_path: "https://jennalynnpearson.files.wordpress.com/2019/02/oceancolor.jpg" 
    alt: "placeholder image 2"
    title: "Anisotropic Velocity Structure Function Theory"
    excerpt: 'Upper ocean statistics are powerful metrics useful for classifying turbulent regimes, and provide an efficient and scale-selective means of testing model fidelity. However, traditional assumptions of isotropy (directional independence), homogeneity (insensitive to translations in space), and stationarity (insensitive to shifts in time) for oceanic statistics are often unrealized, especially in the coastal oceans and over the submesoscale range of scales. To move away from some of these assumptions, I develop structure function theories for anisotropic turbulence.'
    url: "https://github.com/jlpearso"
    btn_label: "Repository"
    btn_class: "btn--primary"
feature_row4:
  - image_path: "https://jennalynnpearson.files.wordpress.com/2018/08/screen-shot-2018-08-15-at-2-34-35-pm-e1550359856524.png"
    alt: "placeholder image 2"
    title: "Data Assimilation & Traffic Modelling"
    excerpt: 'Applying data assimilation schemes to traffic models is difficult given that the data come from a variety of sources, to include Lagrangian data from individually tracked cars and Eulerian data from placed sensors. To make robust yet simplified models, I incorporate both Eulerian and Lagrangian traffic flow observations using a variety of data assimilation schemes. Additionally, these methods allow estimation of parameters difficult to observe and therefore prescribe.'
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row1" type="right" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="left" %}
