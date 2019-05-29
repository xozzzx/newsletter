---
  layout: newsletter
---

{% for staff_member in site.emailcontent %}
  <h2>{{ staff_member.title }} - {{ staff_member.weblink }}</h2>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}
