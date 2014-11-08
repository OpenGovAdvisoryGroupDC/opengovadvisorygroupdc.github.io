---
title: Meetings
layout: default
permalink: /meetings/
---

## Upcoming Meetings of the Open Government Advisory Group
{% for meeting in site.meetings %}
* [{{meeting.date | date: "%B %d, %Y "}}]({{meeting.url}})
{% endfor %}