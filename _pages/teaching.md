---
layout: archive
title: "Teaching"
permalink :/teaching/
author_profile: true
---

As a passionate educator, I strive to make complex concepts accessible and engaging. My teaching philosophy emphasizes clarity, curiosity, and practical applications, fostering an environment where learners can thrive and grow. Whether it’s cheminformatics, computational chemistry, or foundational concepts, I aim to empower students with knowledge and confidence.

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
