---
title:  Contemplating Wordpress
subtitle: When To Undertake A New Framework
author: Todd Heitmann
description: Wordpress offers a great framework that I explored for dynamic content. Ultimately, I desired other features and stuck with pelican, but enjoyed the learning process.
summary: After some thought and discussion about static versus dynamic websites, I began considering switching to Wordpress. With much of the internet built on Wordpress, deeply understanding its data models and construction intrigued me. I knew that websites I built for friends or colleagues could be maintained by others if I did not have the time carved out to do so.
date: 2017-04-10
blog: Technology
tags: ["wordpress"]
image: contemplating-wordpress.jpg
imageheight: 800
imagewidth: 1200
status: published
---

After some thought and discussion about static versus dynamic websites, I began considering switching to Wordpress. With much of the internet built on Wordpress, deeply understanding its data models and construction intrigued me. I knew that websites I built for friends or colleagues could be maintained by others if I did not have the time carved out to do so.

### Learning Wordpress

Being a part-time graduate student at the University of Oklahoma offers a few perks, with access to [Lynda](https://www.lynda.com) being one of them. I immediately watched through a few classes at 2x speed to get basic understanding. After this, to quickly get through content, I turned once again to Team Tree House, [as I first learned]({filename}/Technology/how-i-built-this-website.md). The two week free trial was enough for me to go through the main topics, understanding theme creation and hooks for a basic knowledge. From there I began building on top of the [underscores](http://underscores.me) theme, creating something to update this blog.

### Everything Including The Kitchen Sink

While learning more about the details of Wordpress and beginning to understand the data models, I tried developing a theme for a new dynamic website for me to interact with. What I found under the hood caused me to pause my original pursuits. Continuing to learn hooks, I found each plugin bloated my site, injecting javascript, css, and increasing load times. I found I desired more control over every element in my website, which would not allow me to use plugins.

### Sticking With Pelican

Ultimately, I created a hack in Pelican to allow for some continuing updated content outside of typical blog posts. Sharing recently read articles by combining [Workflow](https://workflow.is) with [Working Copy](https://workingcopyapp.com) pushes content to [Github](https://github.com/toddheitmann/toddheitmann.com). When I publish, a custom python scripts removes the shared articles blog entries from the sitemap xml and all html files associated with them.

The obvious downside requires me to rebuild the website. Currently I run this from my home computer, but could automate it by using a shell script to pull and rebuild on the server. This trade off worked best for me to have semi dynamic content without overhauling everything to date.

### Moving Forward

While Wordpress wasn’t right for this website, I plan to build new websites for friends on it. This provides a non-technical person easy update capability, and the possibility for continued development should I become too busy. Overall, despite the many complaints, I consider it best for those needs, and obviously not my own.

What experiences do you have using Wordpress? Share your thoughts with me on twitter [@toddheitmann](https://twitter.com/toddheitmann) or [email me](mailto:me@toddheitmann.com).
