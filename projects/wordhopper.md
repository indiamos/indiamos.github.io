---
layout: project
title:  "Wordhopper"
permalink: /projects/wordhopper
tags: PHP, Wordnik API
---

An assignment for Tom Igoe's class [Understanding Networks](http://itp.nyu.edu/understandingnetworks/Main/Syllabus):

> REST assignment. Communication in not-so-realtime. Deliver information to the user through the browser from somewhere else. Update the information they're seeing while they interact, preferably based on input from multiple sources.

The site is no longer live, but the behavior was as follows:

### /wordhopper/

At the root URL, you get the current word of the day from Wordnik, followed by a definition and a set of usage examples:

<a href="http://www.flickr.com/photos/indiamos/4054917815/" title="Wordhopper - ITPindia by indiamos, on Flickr"><img src="http://farm3.static.flickr.com/2705/4054917815_dff854a96f.jpg" alt="Wordhopper - ITPindia" /></a>

### /wordhopper/gastropod

If you tack a word onto the end of that URL, you get the word and its usage examples:

<a href="http://www.flickr.com/photos/indiamos/4055667774/" title="Wordhopper - ITPindia by indiamos, on Flickr"><img src="http://farm3.static.flickr.com/2505/4055667774_2eeab6c6f0.jpg" alt="Wordhopper - ITPindia" /></a>

### /wordhopper/monster/d

If you add a `/d` to the end of the URL, after your personally chosen word, you get all the available definitions for that word:

<a href="http://www.flickr.com/photos/indiamos/4055676722/" title="Wordhopper - ITPindia by indiamos, on Flickr"><img src="http://farm3.static.flickr.com/2658/4055676722_d5645d493c.jpg" alt="Wordhopper - ITPindia" /></a>

## Links

-   ITPindia: [Product of a RESTful night](http://itp.indiamos.com/blog/2009/10/29/product-of-a-restful-night/) (includes PHP source code)
