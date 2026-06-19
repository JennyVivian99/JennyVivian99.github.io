---
layout: archive
title: "Integrated Forest Restoration"
permalink: /integratedforestrestoration/
author_profile: true
---
{% include base_path %}
  {% for post in site.integratedforestrestoration %}
{% endfor %}

## Background
The Integrated Forest Restoration Special Interest Network within the [Ecological Society of Australia](https://www.ecolsoc.org.au/category/research-chapters/integrated-forest-restoration/) was created after one of the biggest ESA conferences (ESA 2024), following the willingness of Jenny Vivian to create a supportive network for the promotion of integrated forest restoration, thus considering multiple aspects of the ecosystem and cutting-edge techniques. During ESA2024, it was clear the need to connect different experts and early-career researchers from different spheres of studies, who have the same objective: to restore forest ecosystems. To ensure the re-establishment of the forest ecosystems in degraded lands, and threatened by climate change, the comprehension of multiple environmental aspects is fundamental: soil, vegetation, animals and abiotic traits must all be considered. 

## Aim
Forest restoration requires an interdisciplinary approach, which takes into account advances and knowledge from multiple scientific spheres. The aim of this Special Interest Network (SIN) is to provide resources for cutting-edge approaches related to forest restoration coming from multiple scientific spheres (e.g., soil science, tree biology, climatic models), which is the reason for the “Integrated” word of the SIN. Through this hub, geologists, ecologists, biologists, and experts in other environmental fields can gain fundamental knowledge to improve the likelihood of success in forest restoration. As the ecological systems are complex networks of multiple interacting spheres, the study and development of restoration plans must take into account the numerous processes, abiotic and biotic compartments of the forest. Forest restoration requires the spilling of knowledge from the studies done in different spheres, to ensure a comprehensive and educated development of the ecosystem. 

Furthermore, the Integrated Forest Restoration Special interest network aims to encourage discussions, knowledge sharing and collaborations among people involved in forest restoration but who work in focused geographic and academic areas (e.g., on soil microbes, plant traits, mammals). 

Taking advantage of advances in cross-sectors is imperative to achieve the restoration goals and properly manage the ecosystem to ensure its conservation in Australia, but also all over the world. 

## Engagement
News, cutting-edge techniques and articles focused on the topic of integrated forest restoration will be shared monthly through e-mail. To sign up, please click [HERE](https://docs.google.com/forms/d/e/1FAIpQLSc3THm26QpPJuVaX5vZumHaCjOhydnHefc6R6IGIIKJ5H91PQ/viewform)

Specifically, the e-mails will include: 
-forest restoration advances related to the different aspects of the ecosystem
-cutting-edge techniques for forest restoration management, implementation and monitoring; 
-information on seminars and video resources; 
-opportunities for collaborations. 
Resources and links to videos and organised meetings are also listed in the posts below.

## Contacts
Chair of Integrated Forest Restoration: Jenny Vivian, PhD candidate at UniSC: jennyvivian99@gmail.com
For enquiries and to get in touch: integratedforestrestoration@gmail.com 

## Posts
<ul>
  {% for post in site.integratedforestrestoration reversed %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <!-- Optional: Add a date or description if you have them in your front matter -->
      <!-- <span>{{ post.date | date: "%B %d, %Y" }}</span> -->
    </li>
  {% endfor %}
</ul>
