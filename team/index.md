---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Collaborators

{% include section.html %}

{% include collab_list.html data="collab" component="collab_portrait"%}

