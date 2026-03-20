---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

{%
  include button.html
  type="email"
  text="ck.wong@lms.mrc.ac.uk"
  link="ck.wong@lms.mrc.ac.uk"
%}
{%
  include button.html
  type="phone"
  text="Coming soon"
  link="Coming soon"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/29ae631nw9czoQ1W9"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Coming soon"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Coming soon"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}
