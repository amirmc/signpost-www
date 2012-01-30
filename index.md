---
layout: page
title: Welcome the Signpost holding page!
---
{% include JB/setup %}

Read more about [Signpost][] on the [Personal Container][] pages.

[Signpost]: http://signpostio.com
[Personal Container]: http://perscon.net

## Some random non-signpost-y stuff!

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

- Style this theme so it looks better (1 + 3)
- Add some place holder blog content - just to see how it looks
- Find some nice CC licenced photos - for front page etc

### Previous notice

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


