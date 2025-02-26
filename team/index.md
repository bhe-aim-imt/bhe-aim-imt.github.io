---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team



{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'professor'" %}
{% include list.html data="members" component="portrait" filter="role == 'researcher'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'master' and description == 'Master Student, 2023'" %}
{% include list.html data="members" component="portrait" filter="role == 'master' and description == 'Master Student, 2024'" %}
{% include list.html data="members" component="portrait" filter="role == 'master' and description == 'Master Student, 2025'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad'" %}

{% include section.html background="images/background.jpg" dark=true %}


