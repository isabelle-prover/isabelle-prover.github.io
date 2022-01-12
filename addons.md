# Isabelle Add-on Tools and Components

Quick link: <code>isabelle.systems/addons/<em>&lt;code&gt;</em></code>, e.g. <code>isabelle.systems/addons/linter</code>

{% assign categories = site.addons | group_by:"category" | sort:"name" %}

{% for group in categories %}
<h2>{{ group.name }}</h2>
<ul>
    {% for shortlink in group.items %}
    <li>
        <a href="{{ shortlink.redirect }}">{{ shortlink.title | slugify }}</a>: {{ shortlink.description }}
    </li>
    {% endfor %}
</ul>
{% endfor %}



---

Something missing? Something broken? Create a [pull request or issue](https://github.com/isabelle-prover/isabelle-prover.github.io) to let us know.
