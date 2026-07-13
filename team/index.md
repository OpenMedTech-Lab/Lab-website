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

Together, we advance rehabilitation, neurotechnology, robotics, and assistive technologies that empower people with disabilities and improve lives worldwide. We are proud to work closely with open-source organisations and not-for-profit charities in advancing our mission.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/oshw.png" link="https://oshwa.org/" %}
{% include figure.html image="images/osms.jpg" link="https://opensourcemedicalsupplies.org/" %}
{% include figure.html image="images/CRP.jpg" link="https://www.crp-bangladesh.org/" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
