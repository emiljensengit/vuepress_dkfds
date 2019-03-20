<template>
    <div class="alert {{ classes }}" {% if role %}role="{{role}}"{% endif %} aria-label ="{{ aria }}">
        <div class="alert-body">
            {%- if title -%}
            <p class="alert-heading">{{ title | safe }}</p>
            {%- endif -%}
            <p class="alert-text">{{ content | safe }}</p>
        </div>
    </div>
</template>