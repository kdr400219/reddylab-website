---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Science is a team endeavor. We strive to foster an inclusive, collaborative, and rigorous research environment - that starts with our people.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi' and role != 'pet'" %}

{% include section.html %}

## Lab Pets

{% include list.html data="members" component="portrait" filter="role == 'pet'" %}

{% include section.html background="images/background.jpg" dark=true %}

## Lab Alumni

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'alumni'" %}

{% include section.html background="images/background.jpg" dark=true %}
