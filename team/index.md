---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team


Our research lab is comprised of a talented team of researchers who bring a wealth of knowledge and expertise to the table. Each team member has their unique research interests and background, which allows us to approach complex problems from a variety of perspectives. Our team consists of experts in software engineering, machine learning, control, and other related fields, allowing us to take a multi-disciplinary approach to our research.

Our lab values collaboration, and we work closely together to develop and implement innovative solutions that address the most pressing challenges facing the field of intelligent software systems. We foster a supportive and inclusive work environment where all team members are encouraged to share their ideas and expertise, creating a vibrant and dynamic research culture. Together, we are committed to advancing the field of Machine Learning System Engineering and contributing to the development of trustworthy intelligent software systems.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
