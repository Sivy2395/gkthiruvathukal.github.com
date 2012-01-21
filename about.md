---
layout: page
title: About
group: navigation
---


I am a full professor of computer science at [Loyola University
Chicago](http://www.luc.edu) in the [CS
Department](http://www.cs.luc.edu), where I also serve as the
department's computing director. Since 2009, I am serving as co-director
(with Steve Jones) of the [Center for Textual Studies and Digital
Humanities at Loyola University](http://www.ctsdh.luc.edu), where we are
both working with Peter Shillingsburg on tools to enable collaborative
textual scholarship (among other things). I also co-direct the CS
department's [Emerging Technologies Laboratory](http://www.etl.luc.edu)
with [Konstantin Läufer](http://laufer.cs.luc.edu), where we work on all
things concurrent, parallel, embedded, and distributed--so called
pervasive computing technologies.

I'm a member of the IEEE Computer Society and the Association for
Computing Machinery. At the IEEE Computer Society, I am an associate
editor in chief (AEIC) for [Computing in Science and
Engineering](http://www.computer.org/cise) (co-published by [American
Institute of Physics](http://www.aip.org/)) and [Computing
Now](http://computingnow.computer.org), which is the Computer Society's
foremost effort to engage its membership using new/social media. If you
are a student reading my page, I encourage you to become a student
member of the
[ACM](https://campus.acm.org/public/qj/QuickJoin/qj_control.cfm?form_type=Student)
and the [IEEE Computer
Society](http://www.computer.org/portal/web/membership/join). Not only
is being a member of these societies valuable to your career, it helps
you to maintain a commitment to lifelong learning and a connection to
others in the profession.

I hold a Ph.D. from the [Illinois Institute of
Technology](http://www.cs.iit.edu/) in Chicago, Illinois, where I was a
student from 1988-1995 (M.S. in 1990, Ph.D. in 1995). My research from
the beginning of my graduate studies was about [lightweight
object-oriented approaches to parallel
programming](http://works.bepress.com/gkthiruvathukal/47) (using actors)
and [dataflow](http://works.bepress.com/gkthiruvathukal/49), which
resulted in the development of two experimental messaging middleware
systems ([Distributed Memo](http://works.bepress.com/gkthiruvathukal/33)
and [Enhanced Actors](http://works.bepress.com/gkthiruvathukal/47)) to
support parallel programming, mostly based on C and C++ on Unix
platforms. I was a postdoctoral scientist at Argonne National Laboratory
from 1996-1998, where I worked with [Ian
Foster](http://www.mcs.anl.gov/~foster) on [wide-area (grid)
implementations of Message Passing
Interface](http://works.bepress.com/gkthiruvathukal/44) (MPI) and and
[interfacing then-emerging Java to the
grid](http://works.bepress.com/gkthiruvathukal/12). While I still have
an *eye*toward high-performance computing through projects in novel
computational approaches ([scalable I/O and
atomicity](http://works.bepress.com/gkthiruvathukal/13)) and filesystems
([peer-to-peer](http://works.bepress.com/gkthiruvathukal/28),
[layered/versioned](http://works.bepress.com/gkthiruvathukal/37),
[object-oriented](http://works.bepress.com/gkthiruvathukal/1) and
[service-oriented](http://works.bepress.com/gkthiruvathukal/48)
filesystems), my interests span all aspects of computer science with a
strong focus on software engineering. In recent years, I have been
pursuing some long-dormant interdisciplinary interests. I've recently
been involved in a fruitful collaboration with two English colleagues,
[Peter Shillingsburg](http://peter.shillingsburg.net/) and [Steven E.
Jones](http://stevenejones.org/), in the growing area of digital
humanities on tools for [collaborative textual
studies/scholarship](http://works.bepress.com/gkthiruvathukal/18) and
[platform studies](http://works.bepress.com/gkthiruvathukal/6). In the
latter case, Steven E. Jones and I have just completed a book, [Codename
Revolution: The Nintendo Wii
Platform](http://www.amazon.com/Codename-Revolution-Nintendo-Platform-Studies/dp/026201680X),
in the [MIT Press Platform Studies](http://platformstudies.com) series,
edited by Nick Montfort and Ian Bogost.

From 1989-1996, I was also employed in industry, both as a consultant
and full-time staff member (for [Tellabs](http://www.tellabs.com/),
[R.R. Donnelley and Sons Technical (Research)
Center](http://www.rrd.com/), and [Metromail](http://www.metromail.com),
which is now a part of [Experian](http://www.experian.com/).

In my spare time, I enjoy reading, history (and computing history),
politics, world travel, and music (piano). I enjoy spending time with
Nina (my wife), Rohan (my son), and Maya (my daughter). We have our
hands full but love every minute of it.

My research has been funded by the National Science Foundation (NSF),
DARPA, and the National Endowment for the Humanities (NEH). I've also
received industry support from Hewlett-Packard, Microsoft, and Hostway
Corporation.
## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

