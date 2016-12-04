---
layout: default
title: Maxwelldu's Blog
---
<h2>{{ page.title }}</h2>
<p>My Blog:</p>
<ul>
　{% for post in site.posts %}
　　　<li>{{ post.date | date_to_string }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
　{% endfor %}
</ul>

<p><b>Find me on:</b></p>

<ul>
<li><a href="http://github.com/maxwelldu/">Github</a></li>
</ul>

<p><br /><b>Contact Information:</b></p>
<blockquote>
欢迎所有朋友加我微信：happypeter1983
</blockquote>
