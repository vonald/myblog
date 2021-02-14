---
author: stephen_strandlines
date: 2020-02-26 21:14:38+00:00
draft: false
title: Having moved my blog to Wordpress, the first task
type: post
url: /having-moved-my-blog-to-wordpress-the-first-task/
categories:
- uncategorised
kind:
- Note
post_format:
- Status
tags:
- blogging
- IndieWeb
---

Having moved my blog to Wordpress, the first task was to choose an IndieWeb-friendly theme. Over at [IndieWeb.org](https://indieweb.org/WordPress/Themes) there is advice aplenty on what themes work well - I won’t pretend to understand it all yet. I have used [Autonomie](https://indieweb.org/Autonomie#Issues) by [Matthias Pfefferle](https://indieweb.org/User:Notiz.blog). I like it’s minimalist look - no doubt some tinkering will occur.

The second task was to find a way to easily post to the blog without involving the ghastly Wordpress app. To this end I dug into [Drafts 5](https://getdrafts.com), which I haven’t used in an age. Initially I edited the Post to Wordpress template that is available to download from the [Action Directory](https://actions.getdrafts.com). This was easy to set up but I quickly spotted a problem. For some reason that is beyond me, when I posted to Wordpress using this action comments would be closed, overriding the default that I have set. I tried to rectify this but no joy.

Another option is to email a post to Wordpress via Jetpack. I set up an Action in drafts which emails my text. Relevant tags are typed in the first line. The second line is a duplicate of the first few words of the blog post minus any markdown formatting - the reason for this will become obvious. The rest is the body of the post. Using this method seems not to interfere with the ‘comments on’ setting.

One slight hitch I discovered when emailing a post was that Wordpress automatically created a post title - not something I use as a rule - using the current date. This is where that second duplicate line comes in. By inserting a title shortcode in the Drafts action which calls this line, Wordpress uses this as a title instead of the date. While I don’t generally display the titles on the blog it should look better in RSS feeds than a date would. Probably not the most elegant solution but this does all mean I can type a post with tags and send it to Wordpress in one click. And I’m all for fewer clicks.
