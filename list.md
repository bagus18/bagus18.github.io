---
layout: gawan
title: Note List
permalink: /note/list/
img: https://openclipart.org/image/2400px/svg_to_png/182517/paper-notes.png
---

<div class="home w3-animate-zoom">

  <h1 class="page-heading w3-text-indigo w3-animate-top">List Entry <a class="w3-right-align rss-subscribe" href="{{ "/feed.xml" | prepend: site.baseurl }}" title="subscribe via RSS"><i class="fa fa-rss w3-text-orange w3-right-align w3-animate-fading" aria-hidden="true"></i></a></h1>

  <ul class="post-list w3-ul">
    {% for post in site.posts %}
      <li>
        <span class="fa fa-angle-right w3-text-grey"> {{ post.date | date: "%-d %b %Y" }} <i class="w3-text-red fa fa-angle-double-right" aria-hidden="true"></i> <a class="post-link w3-text-blue" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></span>
      </li>
    {% endfor %}
  </ul>

 

</div>
