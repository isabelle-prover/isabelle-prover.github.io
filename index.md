# Isabelle Quick Access Links

Quick link: <code>isabelle.systems/<em>&lt;code&gt;</em></code>, e.g. <code>isabelle.systems/afp</code>

<ul>
  {% for shortlink in site.shortlinks %}
    <li>
      <a href="{{ shortlink.redirect }}">{{ shortlink.title | slugify }}</a>: {{ shortlink.description }}
    </li>
  {% endfor %}
</ul>

---

Something missing? Something broken? Create a [pull request or issue](https://github.com/isabelle-prover/isabelle-prover.github.io) to let us know.
