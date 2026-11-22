---
layout: archive
title: "Talks"
permalink: /talks/
author_profile: true
published: false
---

{% include base_path %}

*Currently, I haven't been invited to give any talks yet. (Waiting for the call! 📞)*

---

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
