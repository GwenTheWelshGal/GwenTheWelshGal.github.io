---
layout: post
title: Lesbian Wednesday Addams Twitter Bot
date: 2022-11-17 18:00 +0000
updated: 2022-11-21 22:45 +0000
categories: [Programming, Twitter Bots, Python, Projects]
excerpt_separator: <!--more-->
---

I have added that Twitter bot that I was working on in October 2022. You can read about it in a little bit of detail on the [Projects]({{ site.baseurl }}/projects/) page. It's not the perfect Twitter bot, but at least it works. The error catching does not work the way I want it to as of the time of publication, which I find quite frustrating.
<!--more-->
**Addendum - November 21, 2022:**

For the most part, it appears to be running flawlessly, except for the occasional error that comes up. At least the way it is logging things, it is telling me what the error code is, but how to catch them and print a custom error message is something that vexes me these days. Perhaps in the near future I will be able to sort that out. The plan is for the error message to tell me what has happened and hopefully tell me which tweet in the tweetlist is the culprit.

The last error I got was a 187 error, telling me that the status was a duplicate. What it basically means is that the same thing was posted in the last 24 hours from the time that it happened. The only solution I can see, and one I'm actively working on, is to increase the randomization of the tweetlist such that more of them are formatted strings and there's more than the 120, 130 different tweet strings to choose from. Half of them are formatted strings and involve random integers or random inputs from other arrays earlier in the Python file containing those tweets.

Sometimes, I think it's my imagination that's holding me back.