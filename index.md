---
---

# Where the magic happens...

An engaging 1-3 sentence description of your lab.

{% include section.html %}

## Highlights

{% capture text %}

Check out our newest breaking news here!

{%
  include button.html
  link="blog"
  text="Check out the news"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="blog"
  title="Breaking News"
  text=text
%}

{% capture text %}

Check the publications here!

{%
  include button.html
  link="research"
  text="Browse our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Publications"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Checkout our projects here!

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  text=text
%}

{% capture text %}

Team members are listed here!

{%
include button.html
link="team"
text="Meet our team"
icon="fa-solid fa-arrow-right"
flip=true
style="bare"
%}

{% endcapture %}

{%
include feature.html
image="images/photo.jpg"
link="team"
title="Our Team"
flip=true
style="bare"
text=text
%}