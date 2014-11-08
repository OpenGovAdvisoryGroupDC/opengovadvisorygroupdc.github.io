---
title: Documents
layout: default
permalink: /documents/
---

## Establishment Order and Bylaws

View the [Mayor's Order](mayors-order__2014-250) establishing the Open Government Advisory Group and the Advisory Group's Bylaws (forthcoming).

## Agency Reports

Pursuant to Mayor’s Order 2014-170, each agency was required to transmit an Open Government Report. These reports are made available below: 
{% for report in site.data.agency_reports %}
[{{report.agency}}](/documents/reports/html{{report.filename}}.html) (View original [PDF](/documents/reports/{{report.filename}}.pdf))
{% endfor %}