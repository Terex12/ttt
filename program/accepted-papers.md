---
layout: "multilevel_navbar"
background: '/img/bg-index.jpg'
---

## ACCEPTED PAPERS

<table border=10 frame=void rules=rows>
  <tr>
    <th style="width:40%">Title</th>
    <th >Author</th>
  </tr>
{% for paper in site.data.accepted-papers.paper_list %}
  <tr>
    <td>{{ paper.title }}</td>
    <td>{{paper.authors}}</td>
  </tr>
{% endfor %}
</table>

