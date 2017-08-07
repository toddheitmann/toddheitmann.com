---
title: How I Built This Website
subtitle:  Design, Development and Deployment
author: Todd Heitmann
description: Learning website coding can be daunting with the proliferation of resources. Let's look at how I built this website, knowing zero HTML, CSS or JavaScript.
summary: It would be unfair to say I knew nothing of programing before beginning the learning process. For my job as a Petrophysicist, I use python often, but more in a hackish way. I rarely write classes or good object oriented code. I leave most my data in arrays or lists as often I write scripts with a fast approaching deadline. When writing full workflows, I try to apply best practices to achieve maximum computational efficiency, which requires object oriented programing.
date: 2015-12-02
blog: Technology
tags: ["python", "markdown", "learning"]
image: how-i-built-this-website.jpg
imageheight: 899
imagewidth: 1200
status: published
---

### Background

It would be unfair to say I knew nothing of programing before beginning the learning process. For my job as a Petrophysicist, I use python often, but more in a hackish way. I rarely write classes or good object oriented code. I leave most my data in arrays or lists as often I write scripts with a fast approaching deadline. When writing full workflows, I try to apply best practices to achieve maximum computational efficiency, which requires object oriented programing.

This background in coding helped me learn at a faster pace, but is not necessary. The next resource I introduce requires zero knowledge of code.

### [Team Tree House](http://www.teamtreehouse.com)

As often in life, you get what you pay for. I must begin by saying that Team Tree House requires a monthly subscription of $25. However, I believe this approach is best based on the quality of material, speed of learning, and available resources. Also, you can pause your subscription at any time if you need to take a break.

One benefit of Team Tree House is the structured format. They have specific tracks that bring you up to speed in a sequential manner, assuming zero previous knowledge. This allows the user to jump right in, without endless google searches for relevant material at the appropriate skill level.

Helping you jump straight in, Team Tree House provides a web based text editor. This allows you to code from the beginning, without having to learn what a .html, .css or .js file is or how to read it. You easily follow along in your own window.

The structured nature of each class allows for smooth progression from one topic to the next. Each class features several pauses where you take a brief quiz or actually practice code in a mini-test. This requires you to learn the material, rather than watch an entertaining video. Each class builds on the previous, growing the user's knowledge base step by step.

Overall, I find the material well worth the cost in money and time. To get this site up and running, I focused more on front end development, completing both the front end development track and the web design track. I'd like to add some back end knowledge to complement the front end work I performed. I plan on completing the full stack JavaScript track shortly.

### [chriskrycho.com](http://www.chriskrycho.com)

Nothing beats learning to code from good, well documented examples. Chris, a friend from OU, gives great examples through his [github](https://github.com/chriskrycho) account. Poking around his [personal website](http://www.chriskrycho.com) presents well structured html, Sass and JavaScript.

Chris writes about coding and gives ideas for improvement. He pointed me to [ImageOptim](https://imageoptim.com/) for lossless compression of image files. This helped the [homepage](../index.html) performance tremendously. His example of putting the markdown [source](md/how-i-built-this-website.md) with each post shows how easy compiling from markdown using [pandoc](http://pandoc.org/) can be, and inspired me to do the same. If you write academic papers, be sure to [check out](http://www.chriskrycho.com/2015/academic-markdown-and-citations.html) how he to easily sites resources in different formats and different file types.  A similar [post](http://kieranhealy.org/blog/archives/2014/01/23/plain-text/) by Duke Professor Kieran Healy shows the fully complicated process academic publishing can be.

### Design

The overall design focused on a simple layout that drew the reader into the article. It removes any clutter or distractions so the reader can focus on the content. To accomplish this, I went with a dark gray text, off-white background and crimson accent.

For this reason, I chose to ignore [parallax scrolling](https://en.wikipedia.org/wiki/Parallax_scrolling). While there are some fun simpler [examples](http://dustn.tv/), in my opinion, they distract the reader from the content. Whole [websites](http://shibui.me/web/scroll/index.html) revolve [around](http://www.spaceneedle.com/home/) scroll events, which I think detracts from the message. The fun nature of this form of scrolling is compelling, but I decided to make the website simpler.

The original design used [slick](http://kenwheeler.github.io/slick/) for a carousel sliding homepage. In the iPhone simulator on Chrome, this interaction added a bit of creativity and some fun to scrolling a simple blog. However, after use on an actual iPhone the process was cumbersome and not as ascetically pleasing as first anticipated. Therefore, I redesigned it using the same principles, but with a scrolling layout.

I dislike the standalone nature of the website construction, but with limited skills, this allowed maximum control, at the quickest pace, with considerable learning. Rather than use [Pelican](http://docs.getpelican.com/en/3.6.3/) or [Django](https://www.djangoproject.com/), each home webpage was individually coded, then I wrote a python script to bulk process markdown files. This might be costly in a future redesign.

### Future Work

I am very pleased with the implementation of the website, its responsiveness and final design. As with any research paper or business proposal, a future works section is a must. Here are a few items I will focus on adding.

As more posts are added to the archives, the load times for the homepage will increase significantly and require much data from mobile devices. As I learn more JavaScript, I would like to add a button to append slides using AJAX, creating a type of "infinite scroll" homepage. This requires me to learn more backend, server side development.

Another area to improve on is the use of CSS. I learned the basics and even "advanced" classes in CSS from Team Tree House, but it is still quite limited from a productivity standpoint. I need to add Less or Sass to my repertoire. This hopefully allows a better handle on quick page design.

The short time to go from nothing to a live website was faster than I expected. I hope you find this website an encouraging, challenging or intriguing place!

Have an idea for future work or updates? Find a design flaw or coding mistake? Any questions about how to get started on your own computer? Reach out to me on twitter [@toddheitmann](https://twitter.com/toddheitmann) or [email me](mailto:me@toddheitmann.com).
