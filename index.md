---
layout: default
title: Home
---

# Welcome to My Portfolio

This is my portfolio website where I showcase my projects and work.

## Featured Projects

{% for project in site.projects %}
- [{{ project.title }}]({{ project.url }}) - {{ project.description }}
{% endfor %}

## About Me

I'm a developer passionate about creating amazing projects. Check out my work above!

## Contact

Feel free to reach out to me through GitHub or other social platforms.
