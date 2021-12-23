# Isabelle Quick Access Links

Quick link: <code>isabelle.systems/<em>&lt;code&gt;</em></code>, e.g. <code>isabelle.systems/afp</code>

{% assign categories = site.shortlinks | group_by:"category" | sort:"name" %}

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
