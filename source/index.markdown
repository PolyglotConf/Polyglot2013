---
layout: page
title: "Welcome to Polyglot 2012"
comments: false
sharing: true
footer: true
---

We are very excited to be bringing you the first Polyglot __un__-conference. A
non-denominational and very pragmatic software development conference that is
about software development and nothing but.

### What does Polyglot mean?

*Polyglot: a person who speaks, writes, or reads a number of languages.*

For those of us in the software development business, polyglot refers to the
practice of knowing and utilizing multiple languagues, frameworks and stacks to
build software. In many ways, and particularly for web developers, we all seem
have at least bit of polyglot going on these days.

The core idea of the Polyglot Conference is to celebrate this diversity and
break us out of our typically language-specific user groups and conferences to
come together to talk about the challenges and interests that we all have in
common.

### What is an Un-conference?

Simply put, it's an attendee driven conference. Attendees propose the sessions,
organize and plan the tracks for the day and facilitate the sessions and
discussions during the event.

In order give everyone a bit of a preview of the sessions for the event people
have already started proposing their topics on our [user voice](http://polyglotconf.uservoice.com/) site. Please
take a look and add your own.

### When is it?

The event is being held in Vancouver, BC at SFU Harbour Centre, on *Saturday,
May 26th, 2012*. Tickets are $35 and [available now through Eventbrite »](https://polyglotconf2012.eventbrite.com/)

**But wait! There's more!** Check out the [Tutorials](/tutorials) on Friday, and the [Hackathon](/hackathon) on Sunday.

Still have more questions? Check out the [FAQ](/faq).

<header><div class="x-pattern"><h1 class="entry-title">Latest News</h1></div></header>
<ul id="recent_posts">
  {% for post in site.posts limit: site.recent_posts %}
  <li class="post">
    <p>{{ post.date | date: "%A, %B %d" }}:
    <br /><a href="{{ root_url }}{{ post.url }}">{{ post.title }}</a></p>
  </li>
  {% endfor %}
</ul>
