---
title: Agency Reports
layout: default
permalink: /documents/
---

Pursuant to Mayor’s Order 2014-170, each agency was required to transmit an Open Government Report. These reports are made available below: 
{% for report in site.data.agency_reports %}
[{{report.agency}}]({{report.filename}}.html) (View original [PDF]({{report.filename}}.pdf))
{% endfor %}