---
layout: wrapper
title: Compsocs UK
---

A number of computer science societies at UK universities who use IRC
have resurrected the shared channel `#compsoc-uk` on freenode as a
place for friendly discussion.

Webchat
-------

If you do not have a convenient IRC client, you can use
[freenode webchat](http://webchat.freenode.net/?channels=compsoc-uk)
to connect to the channel.

Bot
---

There is (at least one) utility bot in the channel. One of the
functions it provides is intended to make it easy to check which
university and society someone is from (as this question comes up
often).

Type `!whois <nick>` to find the description a user has set for
themselves.

Type `!whois.set <description>` to set the description for yourself.

Grand Tech Meetup
-----------------

Every year we organise a Grand Tech meetup, inviting all societies
and those interested for a weekend of talks, workshops, and social events.

The 2016 GTMU is currently being planned - join us on IRC to find out more!

**See [the GTMU pages](gtmu) for details.**

Known Societies
---------------

These societies have been seen in the channel:

{% assign socs = site.data.societies | sort: 'university' %}
{% for society in socs %}
 - [{{ society.title }}]({{ society.url }})
{% endfor %}

Future plans
------------

Hopefully, various group activities will be organised among the people
in `#compsoc-uk`. Perhaps when this becomes a proper website, those
events will be listed here.

This Website
------------

If you'd like to improve this website, it is hosted on GitHub pages,
in the repository
[Compsocs/compsocs.github.io](http://github.com/CompSocs/compsocs.github.io). Send
a pull request, and ping `barrucadu` (among others) in the channel if
it seems to be being ignored. Reputable individuals will probably be
given commit access.
