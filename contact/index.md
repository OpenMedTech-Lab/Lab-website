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
  text="mdmonzurul.alam@sydney.edu.au"
  link="mdmonzurul.alam@sydney.edu.au"
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
  image="images/bhpi.jpg"
  link="https://www.bhpi.edu.bd/"
  caption="BHPI"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/crp-savar.jpg"
  link="https://www.crp-bangladesh.org/"
  caption="CRP"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
<!-- This is a single-line comment and will not be visible in the preview -->
{% endcapture %}

{% capture col2 %}
Ability Not Disability - Empowering Lives Through Open and Accessible Innovation.
{% endcapture %}

{% capture col3 %}
<!-- This is a single-line comment and will not be visible in the preview -->
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
