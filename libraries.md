# Isabelle Libraries

{% assign path = "libraries/" %}
{% include quick_link_note.html %}

{% assign categories = site.libraries | group_by:"category" | sort:"name" %}
{% include categories.html %}
