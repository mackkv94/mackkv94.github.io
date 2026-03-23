---
permalink: /
title: "Welcome"
excerpt: "Professional portfolio and personal website"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Welcome to my personal website. Here you'll find an overview of my work, including research publications, blog posts, projects, and my professional background.

---

# Recent Publications
{% for post in site.publications reversed limit:3 %}
  * **[{{ post.title }}]({{ post.url }})** — {{ post.venue }}, {{ post.date | date: "%Y" }}
{% endfor %}

[View all publications &rarr;](/publications/)

---

# Recent Blog Posts
{% for post in site.posts limit:3 %}
  * **[{{ post.title }}]({{ post.url }})** — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[View all blog posts &rarr;](/blog/)

---

# Featured Projects
{% for post in site.projects limit:3 %}
  * **[{{ post.title }}]({{ post.url }})** — {{ post.excerpt | strip_html | truncate: 120 }}
{% endfor %}

[View all projects &rarr;](/projects/)

---

# Resume Highlights

## Education
* **Ph.D. in Electrical Engineering** — Clarkson University, 2018–Present
* **M.Sc. in Electrical Engineering** — Clarkson University, 2018
* **B.Sc. in Electrical Engineering** — Clarkson University, 2016

[View full resume &rarr;](/cv/)

---

# Files & Resources
A collection of downloadable papers, reports, and supplementary materials is available in the [Files](/files/) section.
