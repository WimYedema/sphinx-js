.. js:attribute:: {{ name }}

   {% if type -%}
     **type:** {{ type|indent(3) }}
   {%- endif %}

   {% if description -%}
     {{ description|indent(3) }}
   {%- endif %}

   {{ content|indent(3) }}


