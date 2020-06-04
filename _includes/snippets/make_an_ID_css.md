{% comment %}
to replace space " " by "_" in a name to mak an ID tag in HTML

call :
include snippets/make_an_ID_css.md _text=""

 ==> __return = a text
{% endcomment %}

{%- assign __tmp = include._text | replace: " ", "_" -%}
{%- assign __return = __page_book | where: "chapter", include._chapter_nb -%}
        