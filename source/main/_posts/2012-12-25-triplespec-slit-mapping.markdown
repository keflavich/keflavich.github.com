---
layout: post
title: "TripleSpec Slit Mapping"
date: 2012-12-25 01:04
comments: true
categories: github
---
Working on a [TripleSpec Slit Mapping project on github](https://github.com/keflavich/tspec_mapping).
In its previous iteration, we assumed a fixed offset of 0.5" per step, and no
pointing errors.  This method uses the slit viewer to derive a pointing
solution using [astrometry.net](astrometry.net), then apply that solution to
each slit position to make a map.

Work is largely based on [this post idea](http://adamginsburg.blogspot.com/2012/10/using-guider-images-to-achieve.html)

