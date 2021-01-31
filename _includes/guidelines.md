{% assign element = site.data.elements[page.data] %}

# {{ element.label }}

__URI:__ <{{ site.url }}#{{ element.name }}>

__Definition:__ {{ element.definition }}

__ArchivesSpace Field:__ {{ element.aspace }}

{% if element.same_as_uri %}__Same As:__ <{{ element.same_as_uri }}>

{% endif %}__DPLA Obligation:__ {% include obligation_label.md %}

__Repeatable:__ {% if element.repeatable == true %}True{% else %}False{% endif %}

__Range:__ {% for r in element.range %}{% if r.uri %}[{{ r.label }}]({{ r.uri }})  {% else %}{{ r.label }}{% endif %}{% endfor %}

---

## Input Guidelines
