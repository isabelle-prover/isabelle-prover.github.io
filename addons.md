# Isabelle Add-On Tools and Components

{% assign path = "addons/" %}
{% assign quick_link_example = "linter" %}
{% include quick_link_note.html %}

{% assign categories = site.addons | group_by:"category" | sort:"name" %}
{% include categories.html %}
