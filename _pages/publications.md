---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
You can also find my articles on <u><a href="{{ https://scholar.google.com/citations?user=GuZoTw4AAAAJ&hl=en) }}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Publications

- **Counterfeit Detection of Iranian Black Tea Using Image Processing and Deep Learning Based on Patched and Unpatched Images**  
  *Published 2024*  
  - *Horticulturae (Q1, Impact Factor: 3.1)*  
  - M. S. Besharati, R. Pourdarbani, S. Sabzi, D. Sotoudeh, M. Ahmaditeshnizi, G. García-Mateos  

- **SDPERL: A Framework for Software Defect Prediction Using Ensemble Feature Extraction and Reinforcement Learning**  
  *Submitted 2024*  
  - *Expert Systems with Applications (Q1, Impact Factor: 7.5)*  
  - M. Hesamolhokama*, A. Shafiee*, M. Ahmaditeshnizi*, M. Fazli, J. Habibi

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
