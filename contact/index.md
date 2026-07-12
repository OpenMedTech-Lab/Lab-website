---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Connect with us to explore collaborations, research partnerships, and open-source innovations that advance accessible and affordable healthcare technologies worldwide.

{%
  include button.html
  type="email"
  text="md.malam@connect.polyu.hk"
  link="md.malam@connect.polyu.hk"
%}
{%
  include button.html
  type="phone"
  text="+61 426-604-383"
  link="+61 426-604-383"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/Y1r4rpFUTt2k2VjC9"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
[//]: # (This is a hidden single-line comment)
{% endcapture %}

{% capture col2 %}
Ability not Disability
{% endcapture %}

{% capture col3 %}
[//]: # (This is a hidden single-line comment)
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
