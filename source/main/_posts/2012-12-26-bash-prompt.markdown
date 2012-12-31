---
layout: post
title: "Bash Prompt"
date: 2012-12-26 16:55
comments: true
categories:  bash
---
Tried to create a new bash prompt today.  It's intended to show your current
git branch in red if there have been any changes or green if there are no
uncommitted changes.  Otherwise it's the same as my old prompt, with yellow
path and cyan host name.  Here's the source gist:

<script src="https://gist.github.com/4383597.js"></script>

And a screenshot:
{% img /images/prompt.png prompt %}
