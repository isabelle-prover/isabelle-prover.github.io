# Isabelle Libraries

Quick link: <code>isabelle.systems/libraries/<em>&lt;code&gt;</em></code>, e.g. <code>isabelle.systems/libraries/afp</code>

{% assign categories = site.libraries | group_by:"category" | sort:"name" %}
{% include categories.html %}
