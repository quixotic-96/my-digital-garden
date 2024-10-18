---
layout: page
title: Home
id: home
permalink: /
---

# Welcome!

<p style="padding: 3em 1em; background: #eee6ff; border-radius: 4px;">
  This is my hypertext commonplace. [[Choose your own adventure]] as you read through my notes on making and mending and watching things grow.
</p>

<strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

##### credits

<p style="font-size:75%;">This site was made with the accumulated years of encouragement from my brothers and my friends; the template is free, open-source, and <a href="https://github.com/maximevaillancourt/digital-garden-jekyll-template">available on GitHub here</a>.
</p>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
