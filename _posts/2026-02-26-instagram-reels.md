---
layout: post
title: Pixyll Does Instagram Reels
date: 2026-02-26 04:30
summary: Pixyll now handles Instagram Reels.
tags: jekyll video instagram 
---


## Embed Instagram Reels

Simply include `instragram-reel.html` with an appropriate reel ID and you'll get an embedded player. 

{% raw %}`{% include instagram-reel.html reel_ID="DVq19N3F28z"%}`{% endraw %}

Result:

{% include instagram-reel.html reel_ID="DVq19N3F28z" %}

You can include the caption by adding `caption=true` with the include directive.

{% raw %}`{% include instagram-reel.html reel_ID="DVq19N3F28z" caption=true %}`{% endraw %}

Result:

{% include instagram-reel.html reel_ID="DVq19N3F28z" caption=true  %}