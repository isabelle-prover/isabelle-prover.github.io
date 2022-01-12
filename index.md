# Isabelle Quick Access Links

{% assign path = "" %}
{% assign quick_link_example = "doc" %}
{% include quick_link_note.html %}

{% assign categories = site.shortlinks | group_by:"category" | sort:"name" %}
{% include categories.html %}
