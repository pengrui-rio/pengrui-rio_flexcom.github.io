---
title: Team
nav:
  order: 5
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

### Lab Director
{% include list.html data="members" component="portrait" filter="role == 'pi'" %}

### PhD/Mphil Students

{% include list.html data="members" component="portrait" filter="role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'Mphil'" %}

 
### Alumni

{% include list.html data="members" component="portrait" filter="role == 'Alumni'" %}
