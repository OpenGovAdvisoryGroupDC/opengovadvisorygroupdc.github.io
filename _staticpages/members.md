---
title: Members
permalink: /members/
redirect_from: "/members.html"
layout: default
---
### Members of the Open Government Advisory Group

![Photo of the members of the Open Government Advisory Group](/assets/images/ALM_0202.jpg "Photo of Members")

{% for member in site.data.members %}* {% if {{member.github}} %}[{{member.name}}](https://github.com/{{member.github}}) {% else %} {{member.name}} {% endif %}- {{member.affiliation}}
{% endfor %}

Download a [YAML file of the members](/assets/data/members.yml).