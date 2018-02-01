---
layout: page
title: "Zastávky"
generator: pagination
provider: site.zastavky
sort_by: ordering
sort_type: ascending
max_page: 999
---

<ul>
{% for Z in page.pagination.items %}
	<li>
	   <a href="{{ Z.url }}">{{ Z.title }}</a>
	   {% if Z.details.request %}
	     <small>(na znamení)</small>
	   {% endif %}
	</li>
{% endfor %}
</ul>
