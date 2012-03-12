---
layout: page
title: "Welcome to Polyglot 2012"
comments: false
sharing: true
footer: true
---

We are very excited to be bringing you the first Polyglot __un__-conference. An entirely non-denominational software
development conference that is about software development and nothing but.

The event is being held in Vancouver, BC at SFU Harbour Centre, on *Saturday, May 26th, 2012*. Tickets are $35 and [available now through Eventbrite »](https://polyglotconf2012.eventbrite.com/)

For more information, see the [Event](/event), [Tutorials](/tutorials), and [FAQ](/faq) sections.

## News

<div class="blog-index">
  {% assign index = true %}
  {% for post in paginator.posts %}
  {% assign content = post.content %}
    <article>
      {% include article.html %}
    </article>
  {% endfor %}
</div>

