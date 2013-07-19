---
layout: page
title: A Gentleman and a Scala
tagline: Understanding math through code
---
{% include JB/setup %}

My name is Jason Liszka, and I'm a software engineer at Foursquare in New York.
This blog chronicles my attempt to understand math better through code.
I've always been interested in abstract math, but computation has always been more intuitive to me.
Realizing abstract structures in code makes them more concrete and makes it easier for me to wrap my puny human brain around them.

I'm a big fan of Scala and Haskell so you'll see a lot of code in those languages.

You should probably <a href="http://twitter.com/jliszka">follow me on twitter</a>.
I promise I won't spam your feed.

### Blog Archive 
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
