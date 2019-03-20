---
headling: Alert
text: Alert tekst
type: Info
classes: classes
role: role-tekst
aria: aria-tekst
---

<div class="alert {{type}} {{ classes }}" {% if role %}role="{{role}}"{% endif %} aria-label ="{{ aria }}">
  <div class="alert-body">
    {%- if title -%}
    <p class="alert-heading">{{ title | safe }}</p>
    {%- endif -%}
    <p class="alert-text">{{ text | safe }}</p>
  </div>
</div>





