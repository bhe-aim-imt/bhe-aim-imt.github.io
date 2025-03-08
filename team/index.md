---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

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

{% include section.html %}
<hr>
<h2>Graduate</h2>

{% capture content %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% endcapture %}

{% include grid.html style="square" content=content %}
