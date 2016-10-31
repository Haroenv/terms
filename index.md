---
layout: default
---

Some of the (linked data) terms I've used.

I'm not planning to abandon this, but it's still best not to trust on my ontologies, but rather choose more supported ones, like [vocab.datex.org/terms](http://vocab.datex.org/terms), [schema.org](https://schema.org) …

These terms are generated via [Jekyll](https://jekyllrb.com), and are located in the [_data](https://github.com/haroenv/terms/tree/gh-pages/_data) folder. To have a new set, you should add a new file in `_data`, and make a folder with the same name. In that folder you should copy the same `index.md` as in the other folders (can this be more efficient?). PRs welcome anyway!

## Contents

<https://haroen.me/terms/>

<ul>
{% for dataset in site.data %}
  <li><a href="{{dataset[0]}}">{{dataset[0]}}</a></li>
{% endfor %}
</ul>

## License

[CC0](LICENSE)

## References

* [Building JSON-LD APIs: Best Practices](http://json-ld.org/spec/latest/json-ld-api-best-practices/)
* [Linked Open Vocabularies (LOV)](https://lov.okfn.org/)
* [Schema.org](https://schema.org)
* [vocab.datex.org](https://vocab.datex.org)
* [JSON-LD playground](http://json-ld.org/playground/)
