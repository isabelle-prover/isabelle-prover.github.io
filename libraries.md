# Isabelle Libraries

{% assign path = "libraries/" %}
{% assign quick_link_example = "afp" %}
{% include quick_link_note.html %}

{% assign categories = site.libraries | group_by:"category" | sort:"name" %}
{% include categories.html %}
