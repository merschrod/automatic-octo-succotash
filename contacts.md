---
layout: default
maintainer: "Erika"
---


# Here is my contacts page

## students

{% for thing in list %}
{% for students in site.students %}
 - {{ student.name }}, project: {{ student.project }}, program: {{ student.program }}
{% endfor %}

## other stuff
using a variable: {{ site.email }}

using a different variable <{{ site.email2 }}>

<erika@mun.ca>

Maintained by {{ page.maintainer }}
