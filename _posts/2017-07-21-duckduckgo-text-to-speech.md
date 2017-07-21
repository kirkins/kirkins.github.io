---
layout: post
title: DuckDuckGo Text to Speech Goodie
categories:
- Perl
- Javascript
- html5
---

# DuckDuckGo Text to Speech

_Module for DuckDuckGo that catches queries of users looking for text to speech and serves an interactive widget._

<iframe width="560" height="315" src="https://www.youtube.com/embed/weCrfH8spiI" frameborder="0" allowfullscreen></iframe>

---

[pull request](https://github.com/duckduckgo/zeroclickinfo-goodies/pull/4357) 

This widget consists of a server-side perl script that checks if a query is looking for text to speech.

The sever-side of the widget will also catch phrases passed into a query, for example "text to speech hello friend"
will open the widget and initialize it with the widget with the phrase "hello friend".

The front-end is mainly a javascript wrapper for HTML5 voice capabilities. 3 sliders pass values for volume, speech, and pitch into an HTML5 
speech synthesis object.

There is also a dropdown for voices. All browsers with voice capabilities make an object called `voices` availible.
This object is queried to populate the dropdown, so any future updates to voices shipped with browsers will pass through
to the widget.

The code contained in this widget can be seen in this [pull request](https://github.com/duckduckgo/zeroclickinfo-goodies/pull/4357).
