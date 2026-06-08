---
title: "RSS feed - how will RSS be helpful past, present and the future."
date: 2026-06-08
draft: false
description: "Wished there should be a place where people won't bother to come to my website and see what posts, updates coming in but able to be notified somehow."
tags: ["learning", "dig-deeper"]
categories: ["technology"]
ShowToc: true
TocOpen: false
---

## What are we trying to solve here!

Wished there should be a place where people won't bother to come to my website and see what posts, updates coming in but able to be notified somehow.

Many solution exists:

1. News letters
2. Updates to someone who is intrested through emails
3. Telegram API's or any social media API's.

But why would someone share there personal information to me, too nerdy right. So then came up with RSS(Really simple syndication) which helps not only **us (humans)** but also our **predecessors(AI agents)** I call them so lol.

## What is this RSS?

Let me call it a protocol(yeah it's a protocol) [RFC5005](https://datatracker.ietf.org/doc/html/rfc5005) outlines the different syndications using sliding window solution to save bandwidth of network and read content on the web easy peezy.

So let's you want to read blogs(could be podcasts, news, publications) from multiple sites say it netflix engineering, linkedin engineering blogs, NDTV news , Google podcasts etc. You can't track what changes are made everytime going there and checking.

These blog sites , podcasters use RSS protocol which intern generates a computer readable format(specificall xml document).
Where you can use an RSS aggregator similar to [this](https://chromewebstore.google.com/detail/the-rss-aggregator/ffhafkagcdhnhamiaecajogjcfgienom?hl=en&pli=1) to get all your updates to your browser without tracking them individually.

`You can see my RSS xml [here](https://blog.madmanamrath.xyz/index.xml). Just go to the above aggreator and in add feed section paste the my RSS xml link, you will able to add my feed there. And see if your favourite blogger Rocky is using RSS feed so that you can add it too.`

## There is a catch in here.

RSS cannot have data exceeding 150KB, but how the heck does podcasts comes to RSS feed aggregator. They won't share the whole link in aggregator they just share the link in RSS xml data.

There are search engines similar to google podcast built on top of these podcasts RSS data. Some BitTorrent clients support RSS. RSS feeds which provide links to .torrent files allow users to subscribe and automatically download content as soon as it is published.

After 2010 the use has reduced dramatically and mac OS support started reducing for RSS. Windows, Android, all browsers support RSS till date.

There were papers published quoting 'Its time to bring back RSS' during social media times.

## But why I'm using it

Thought it to a cheaper solution and won't bother users to share their personal details or track them. Let me know if I can some other solution as well. Will post the credits here!

## How about AI agents or bots using RSS.

This is the topic which remained untouched, I'll take some time to do some research on this and update the document.
