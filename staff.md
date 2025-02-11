---
layout: page
title:  Staff
description: A listing of all the course staff members.
---
<!-- # Staff

Staff information is stored in the `_staffers` directory and rendered according to the layout file, `_layouts/staffer.html`. -->

## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
<!-- 
{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %} -->

### Office Hours

* Monday afternoons (1:30 PM - 3:30 PM)
* Friday mornings (9:30 AM - 11:30 AM)

See [weekly schedule](schedule.md) for details.