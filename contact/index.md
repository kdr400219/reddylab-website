---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is part of the Department of Molecular Medicine at the University of South Florida Morsani College of Medicine in beautiful Tampa, Florida. Feel free to contact us for job opportunities, potential collaborations, reagents, and more! 

{%
  include button.html
  type="email"
  text="reddylab2025@gmail.com"
  link="reddylab2025@gmail.com"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/ohcLUge1j9ThrZAs5"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/USF.jpg"
  caption="University of South Florida"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/Tampa.jpg"
  caption="Tampa, FL"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
