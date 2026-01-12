---
layout: page
title: Articles
permalink: /articles/
---

# Articles

## Documenting Protestant Decline, Defending Biblical Faith

---

This section contains in-depth explorations of the major causes of Protestant Christianity's decline from the Reformation to the present day, examined from a Reformed Presbyterian Covenanter perspective.

Each article seeks to:
- **Expose error** with historical accuracy and theological precision
- **Defend truth** by presenting the biblical alternative
- **Exalt Christ** by pointing readers to the Gospel

---

### Latest Articles

{% for article in site.articles reversed %}
- **[{{ article.title }}]({{ article.url }})** — {{ article.date | date: "%d %B %Y" }}  
  {{ article.excerpt }}
{% endfor %}

---

### Categories

Our articles are organised into six major themes:

1. **Ecclesiastical Apostasy** — Doctrinal and liturgical corruption within the visible church
2. **Philosophical & Cultural Apostasy** — Intellectual movements undermining biblical authority
3. **Ecclesiological Degradation** — Distortions in church government and worship
4. **Political & Social Corruption** — State interference and moral compromise
5. **Modern Apostasy** — Contemporary errors and false teachings
6. **Loss of Distinctives** — Abandonment of Reformed heritage and Covenanted commitments

---

*More articles will be added regularly. Please check back often, or subscribe via [RSS](/feed.xml).*
