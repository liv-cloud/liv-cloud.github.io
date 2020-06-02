{% comment %}
to search in "data/my_books.yml", call :
include snippets/find_datas_books.md _book_nb=# _data=""

parameters :
    book_title: 
    book_theme : 
    chapters:

_data [book_title, book_theme, chapters]

 ==> __return = 1 data
{% endcomment %}

{%- assign __return = nil -%}
{%- assign __return = site.data.my_books[include._book_nb].book_number[include._data] -%}
        