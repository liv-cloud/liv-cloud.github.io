{% comment %}
to search in "data/my_books.yml", call :
include snippets/find_books.md _book_nb=# _chapter_nb=#

 ==> __return = a collection of pages
{% endcomment %}

{%- assign __return = site.books -%}
{%- assign __page_book = site.books | where: "book_nb", include._book_nb -%}
{%- assign __return = __page_book | where: "chapter", include._chapter_nb -%}
        