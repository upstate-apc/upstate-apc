---
title: "APC Lab - Team"
layout: gridlay
excerpt: "APC Lab: Team members"
sitemap: false
permalink: /team/
---

# Open positions

We are always looking for new group members with passion, talent, and grit! You will be involved in determining the important and interesting questions, creating and improving instrumental setups, performing measurements, and making discoveries.


{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

</div>
