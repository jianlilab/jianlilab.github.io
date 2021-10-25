
## Alumni


{% for alum in site.data.alumni %}
<hr>
<div id = "{{alum.name}}" style="padding-top: 60px; margin-top: -60px;">
<p><strong>{{alum.name}}</strong> {% if alum.position %} - <em>{{alum.position}}</em> {% endif %}<br>
{% if alum.startdate %} {{alum.startdate}} - {% endif %} {% if alum.enddate %} {{alum.enddate}} <br> {% endif %}
{% if alum.current %} Currently: {{alum.current}} {% endif %} </p>
</div> {% endfor %}
---
