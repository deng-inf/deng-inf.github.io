---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

Below are the members of the IFIS group.

<!--{% include list.html data="members" component="portrait" filter="role == 'pi'" %}-->

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'ms'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad'" %}

{% include section.html background="images/background.jpg" dark=true %}

IFIS group outstanding graduates are as follows:

{% include list.html data="members" component="portrait" filter="role == 'gs-phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'gs-ms'" %}
{% include list.html data="members" component="portrait" filter="role == 'gs-undergrad'" %}

{% include section.html %}
