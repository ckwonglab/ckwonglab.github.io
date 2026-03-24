---
title: Team
nav:
  order: 3
  tooltip: About our team
---

### **We are hiring!**
We are looking for postdoctoral scientists with expertise in physiology, metabolism, immunology, or neuroscience! Please [contact me](mailto:ck.wong@lms.mrc.ac.uk) to discuss these opportunities further.

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

Work in progress

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
