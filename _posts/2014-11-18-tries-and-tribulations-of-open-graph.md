---
layout: post
title:  "The Tries and Tribulations of Open Graph"
date:   2014-11-18 15:27:14
categories: blog
tags: update
description: "Implementing Open Graph tags on my site has had its fair share of struggles"
url: "/2014-11-18-tries-and-tribulations-of-open-graph/"
image: "http://embed.wistia.com/deliveries/3f705c4e4c2ef9b70e6df638f9589b53619e1be0.bin"
---

__"Oh, maybe I should implement Open Graph tags on my site so when people share links on Facebook, they look awesome!!!"__

Awesome idea, Jordan. Too bad that's not as easy as it seems. First, I don't really know much of anything about Open Graph tags. Thankfully [Facebook's documentation](https://developers.facebook.com/docs/opengraph) is really good here, especially when trying to figure out images and what sizes they should be. Second, it turns out I knew _practically nothing_ about Jekyll frontmatter. This was an amazing crash course in setting this stuff up.

Initially I started with [this great post](http://davidensinger.com/2013/04/adding-open-graph-tags-to-jekyll/) by [Dave Ensinger](http://davidensinger.com/about/) and started modifying the code he included to better fit the data structre I've been using for things in my particular Jekyll setup as well as where I'm hosting my images (which happens to be elsewhere, and I'm simply adding direct links to the external service).

I found that keeping my open graph tag logic in a [Jekyll include](http://jekyllrb.com/docs/templates/#includes) has given me a lot of ease-of-use for accessing this logic (which is pretty messy in my layouts view). Jekyll includes are something I hadn't yet experimented with but am now _very_ stoked to make use of going forward!

Through some solid "Argh!" and "Are you serious?" and "Wow, I can't believe it took me that long to realize that." moments, I've got it mostly working. Now to just figure out why some of my variables aren't populating--which I'm suspecting is a weird issue resulting from my current GitHub pages and CNAME installation, but that remains to be seen.

As always, onward and upward!

Jordan