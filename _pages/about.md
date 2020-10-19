---
permalink: /
title: "Welcome, on board!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---




 Despite knowing the journey and where it leads, I embrace it, and I welcome every moment of it. 
 											-- Dr. Louise Banks, Arrival (2016)






Biography
======
Qingbiao Li is a 3nd year PhD student at ProrokLab, the Digital Technology Group (DTG) at the University of Cambridge under the supervision of [Dr Amanda Prorok](https://www.proroklab.org/). His research interests focus on communication-aware motion planning for multi-robot coordination. He is effectively investigating Graph Neural Networks (GNN) to build communication channels for multi-agent and multi-robot systems so that agents/robots can learn how to communicate between each other explicitly. His research can be applied in cooperative tasks for heterogeneous agents, including mobility-on-demand and automated warehouse. 

Prior to joining Cambridge,  he joined [Hamlyn Centre](https://www.imperial.ac.uk/hamlyn-centre/) at Imperial College London, found by [Prof Guang-Zhong Yang](https://ieeexplore.ieee.org/author/37276270800) and [Prof the Lord Ara Darzi](https://www.imperial.ac.uk/people/a.darzi) in the field of medical robots and healthcare for  the MRes in Medical Robotics and Image-Guided Intervention. He was supervised by [Prof Daniel Elson](https://www.imperial.ac.uk/people/daniel.elson) for eight-month research project about oxygen saturation (StO2) estimation, and graduated with Distinction for MRes degree. He also held a MEng  degree  in  Mechanical  Engineeringat  University of Edinburgh. 


He has published papers in medical imaging area (IJCARS) and robotics (IEEE IROS, IEEE Humanoids and AAMAS). He has served as a reviewer for IEEE IROS, IEEE ICRA, IEEE TRO and AAMAS.

Details of his CV can be found at [PDF](./files/CV_QingbiaoLi.pdf).



Publications
======
<!--   <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

  {% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}