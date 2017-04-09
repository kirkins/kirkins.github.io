---
layout: post
title: Evil Chrome Extension
categories:
- javascript
---

# Evil Chrome Extension
Exploring malicious possibilities of chrome extensions to raise awareness.

[Evil Chrome Extension](https://github.com/kirkins/Evil-Chrome-Extension) consists of a chrome extension and server. The extension is
used for tracking and controlling browsers. The server is used to record information and act as a central point of control: 

## Features


* Log users geolocation and send to server if they visit a map site _(as user is already expecting the geolocation pop-up)_.
* Log each website user visits by timestamp
* Keylogging on each page user visits, sent to server every 5 seconds.
* Ability to swap target links. _(e.g. switch login links with fake pages)_.
