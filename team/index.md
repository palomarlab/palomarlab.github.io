---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Current team members

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

Past team members / Coming soon

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo11.jpg" %}=

{% endcapture %}

{% include grid.html style="square" content=content %}


{% include section.html background="images/background.jpg" dark=true %}

Fun in the lab! / Coming soon

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo11.jpg" %}=

{% endcapture %}

{% include grid.html style="square" content=content %}

