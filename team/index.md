---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

## Principle Investigator

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}


## Students

{% include list.html data="members" component="portrait" filter="role != 'pi' and role != 'alumni'" %}

## Mascot

{% include list.html data="members" component="portrait" filter="role == 'mascot'" %}

{% include section.html background="images/background.jpg" dark=true %}

We work with a wide range of outstanding groups from around the world, and we're always on the lookout for new and unique perspectives. We want to push the frontier of photonic quantum information and train a new generation of researchers and engineers.

{% include button.html icon="fa-solid fa-handshake-angle" text="Join the Team" link="join" style="button" %}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filter="role == 'alumni'" %}

{% include section.html background="images/background.jpg" dark=true %}

Our team thrives on collaboration across disciplines and institutions, bringing together innovative ideas and diverse perspectives to tackle the challenges of photonic quantum systems. Whether you’re interested in joining us or learning more about our research, we encourage you to explore the exciting work we’re doing.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
