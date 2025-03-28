---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are open to all kinds of cooperation! Please use the following information to contact us!

{%
  include button.html
  type="email"
  text="lili.wei@mcgill.ca"
  link="lili.wei@mcgill.ca"
%}
{%
  include button.html
  type="twitter"
  text="Twitter"
  link="LiliWei_SE"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/McConnell+Engineering+Building/@45.5060618,-73.576432,17z/data=!3m2!4b1!5s0x4cc91a48f562953b:0x2c3c521ba15284bf!4m6!3m5!1s0x4cc91a464578f1ff:0xb044114ae799c08c!8m2!3d45.5060618!4d-73.576432!16s%2Fg%2F11j00rzhzy?entry=ttu&g_ep=EgoyMDI1MDMyNC4wIKXMDSoJLDEwMjExNjM5SAFQAw%3D%3D"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/mcgill-photo-1.jpg"
  caption="The campus of McGill University"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/mcgill-photo-2.jpg"
  caption="McConnell Engineering Building"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}