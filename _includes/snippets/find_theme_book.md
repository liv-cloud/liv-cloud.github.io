{% comment %}
Waiting 1 attrib as bookname to find theme in "data/my_books.yml"
__return = theme name 
{% endcomment %}
        {%- for _var_tmp in site.data.my_books -%}
            {%- if _var_tmp.mybook == include.bookname -%}
                {%- assign __return = _var_tmp.theme -%}
            {%- endif -%}
        {%- endfor -%}
        {%- if __return == nil -%}
            {%- assign __return = site.data.my_books[0].theme -%}
        {%- endif -%}