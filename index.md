---
layout: default
---

Describing myself is a little difficult but

:page_with_curl: [CV] -- (https://drive.google.com/file/d/17ldxgW-yb7o9KAq5j4vBpmPXMw58_wUN/view?usp=sharing).

:L: [LinkedIn](https://www.linkedin.com/in/dare-osewa/).

# Hobbies

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## AWS

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.date | date: "%B %d, %Y" }}</p>
    </li>
  {% endfor %}
</ul>


