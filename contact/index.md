---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact / Join our lab

We are located at Laboratory 103, Conjunto E - Ciudad Universitaria (UNAM), Mexico City

{%
  include button.html
  type="email"
  text="vmiguelpalomar[at]quimica[dot]unam[dot]mx"
  link="vmiguelpalomar@quimica.unam.mx"
%}
{%
  include button.html
  type="phone"
  text="+52-555-622-5377"
  link="+52-555-622-5377"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
link="https://www.google.com/maps/place/Conjuntos+D+y+E+de+la+Facultad+de+Qu%C3%ADmica/@19.322907,-99.1803111,17z/data=!3m1!4b1!4m6!3m5!1s0x85ce0010115cfbaf:0xcb7a0dd9e8c3c947!8m2!3d19.322907!4d-99.1777362!16s%2Fg%2F11cn9tzg7y?entry=ttu"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo4.png"
  caption="Lab 103 Conjunto E
Circuito Exterior S/N Ciudad Universitaria, Coyoacán, CP 04510
Ciudad de Mexico, Mexico."
link="https://bioquimica.quimica.unam.mx/"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo1.png"
  caption=" We are looking for motivated people to join the lab at undergrad, graduate student, or postdoc levels. We will work together for you to join one of several programs UNAM offers, or to get funding. Please contact us if you are interested."
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

