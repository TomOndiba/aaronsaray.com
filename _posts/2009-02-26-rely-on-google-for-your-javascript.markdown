---
layout: post
title: Rely on Google for your Javascript?
tags:
- javascript
- Misc Web Design
---
After reviewing the [Google Javascript API](http://code.google.com/apis/ajaxlibs/) project, I am torn.  Pro's and cons below... What do YOU think?

**PRO**

  * Proper caching done

  * Shared javascript location - no need to re-download if multiple sites use same library

  * Easy to include method, can be as specific as needed for versioning (you can include major, major.minor, etc.)

**CON**

  * If google goes down, you go down.  Well, if caching is done right that doesn't matter. Plus I'm sure you rely on your host not to go down either...

  * If google ends the service, like they shut down other services, you have to re-architect again.

So, are YOU going to use it?
