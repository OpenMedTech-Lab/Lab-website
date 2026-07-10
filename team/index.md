---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Contributors

OpenMedTech Lab is a multidisciplinary team of volunteer researchers, engineers, clinicians, students, and collaborators from around the world, dedicated to developing affordable, accessible, and open-source medical technologies for global health. 

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

Together, we advance rehabilitation engineering, neurotechnology, robotics, and assistive technologies that empower people with disabilities and improve lives worldwide.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
