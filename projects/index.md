---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

From concept to clinical translation, we develop affordable, accessible technologies that empower people with disabilities worldwide. Our projects address real-world healthcare challenges and enhance participation, independence, and quality of life. To support collaboration, education, and innovation, our projects are released under open-source licences. Software is typically licensed under Apache 2.0, hardware under CERN OHL v2, and documentation under CC BY 4.0. See individual project license for details.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
