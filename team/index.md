---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our team is a group of passionate researchers and students who are dedicated to advancing the state of the art in software engineering. We are committed to conducting high-quality research that has a positive impact on the software development process.
Please explore our team members below to learn more about our research interests and backgrounds.

{% include section.html %}

## Principle Investigator

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}


## Students

{% include list.html data="members" component="portrait" filter="role != 'pi' and role != 'alumni' and role != 'mascot' " %}

## Mascot

{% include list.html data="members" component="portrait" filter="role == 'mascot'" %}

{% include section.html background="images/background.jpg" dark=true %}

We are now actively looking for self-motivated PhD students who are interested in software engineering research, especially in program analysis, test generation, and mobile computing. We value student supervision as an important mission and will work closely with you if you become our student. Please send us your CV and a copy of your transcript to us via email if you are interested.

{% include button.html icon="fa-solid fa-handshake-angle" text="Join the Team" link="jobs" style="button" %}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filter="role == 'alumni'" %}

{% include section.html background="images/background.jpg" dark=true %}

Our team thrives on collaboration across disciplines and institutions, bringing together innovative ideas and diverse perspectives to tackle the challenges during software analysis and testing. Whether you’re interested in joining us or learning more about our research, we encourage you to explore the exciting work we’re doing.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photos/group-photo-1.jpeg" %}
{% include figure.html image="images/photos/group-photo-2.jpeg" %}
{% include figure.html image="images/photos/group-photo-3.jpeg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
