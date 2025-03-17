---
title: Team
nav:
  order: 1
  tooltip: About our team
---



{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'professor'" %}
{% include list.html data="members" component="portrait" filter="role =='researcher'" %}

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'phd' and description == 'PhD Student, 2023'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd' and description == 'PhD Student, 2024'" %}
{% include list.html data="members" component="portrait" filter="role =='master' and description == 'Master Student, 2023'" %}
{% include list.html data="members" component="portrait" filter="role =='master' and description == 'Master Student, 2024'" %}
{% include list.html data="members" component="portrait" filter="role =='master' and description == 'Master Student, 2025'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad' and description == 'Bachelor Student, 2021'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad' and description == 'Bachelor Student, 2022'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad' and description == 'Bachelor Student, 2023'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad' and description == 'Bachelor Student, 2024'" %}

<h2 style="text-align: center;">Graduate</h2>
