# Isabelle Quick Access Links

{% assign path = "" %}
{% include quick_link_note.html %}

{% assign categories = site.shortlinks | group_by:"category" | sort:"name" %}
{% include categories.html %}
