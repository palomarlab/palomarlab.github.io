---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are located at Laboratory 106, Conjunto E - Ciudad Universitaria (UNAM), Mexico City

{%
  include button.html
  type="email"
  text="vpalomar[at]umich[dot]edu"
  link="vpalomar@umich.edu"
%}
{%
  include button.html
  type="phone"
  text="(555) XXX-XXXX"
  link="+52-555-XXX-XXXX"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo1.png"
  caption="L-103 Conjunto E
Circuito Exterior S/N Ciudad Universitaria, Coyoacán, CP 04510
Ciudad de Mexico, Mexico."
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo2.png"
  caption=" "
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
_
{% endcapture %}

{% capture col2 %}
_
{% endcapture %}

{% capture col3 %}
_
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
