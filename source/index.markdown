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

What will the conference be about? We've got a [session suggestions forum](http://polyglotconf.uservoice.com), or click on the "sessions & talks" tab at left to see what's been submitted so far.

Also check out the [Tutorials](/tutorials) on Friday, and the [Hackathon](/hackathon) on Sunday.

<header><div class="x-pattern"><h1 class="entry-title">Latest News</h1></div></header>
<ul id="recent_posts">
  {% for post in site.posts limit: site.recent_posts %}
  <li class="post">
    <p>{{ post.date | date: "%A, %B %d" }}:
    <br /><a href="{{ root_url }}{{ post.url }}">{{ post.title }}</a></p>
  </li>
  {% endfor %}
</ul>
