---
layout: default
title: Soupcan Browser Extension
has_children: true
permalink: /library/browser-extension/
---

# Soupcan
{: .no_toc }

Soupcan is a browser extension that brings together many trans-supportive features into one package for Twitter.
For example, it highlights transphobic users in red and takes reports from the community to keep this list updated
and accurate. It allows you to hide or mask content from transphobes. In the future I plan to make features such
as auto-blocking transphobes, auto-suggesting sources to reply with trans-supportive content, and anything else
you might suggest!

You can download it right now on the Chrome Web Store or at Firefox Add-ons:

> [![image](https://storage.googleapis.com/web-dev-uploads/image/WlD8wC6g8khYWPJUsQceQkhXSlv1/mPGKYBIR2uCP0ApchDXE.png)](https://chrome.google.com/webstore/detail/soupcan/hcneafegcikghlbibfmlgadahjfckonj)

> [![image](https://blog.mozilla.org/addons/files/2015/11/get-the-addon.png)](https://addons.mozilla.org/en-US/firefox/addon/soupcan/)

It's still a work in progress so there may be some hitches. Reach out to me on Twitter if you have any issues, I'll
be happy to help you out.

## Guide

1. How do I report a user as a transphobe?
  Just right click on their username or name and choose Report transphobe from the Soupcan menu.
  > ![image](https://user-images.githubusercontent.com/130214958/235623288-86e4bf34-ebb1-4f1f-9637-20c6237eb96b.png)
2. How do I report someone who was unfairly marked?
  The same as above but instead click "Appeal".

## Rules for use
Please see the [Terms of Service](https://bethylamine.github.io/library/browser-extension/tos)

Additionally, if you're marked as a transphobe, or your account is too new, you won't be able to use the extension. If this
is an issue or you feel like you've been falsely marked please DM me on Twitter @bethylamine.

## Features

Right now, it shows trans-antagonistic Twitter accounts with red highlight. You can also send in reports of other accounts
and they will show up orange in your browser until the reports are approved and then it will show up red. You can also appeal
falsely-flagged accounts with the "Appeal" feature. You can access options via the extension icon > Options e.g.

> ![image](https://user-images.githubusercontent.com/130214958/235313180-bdbf0f82-3b59-4d1f-891a-911de3adb292.png)

There are a few options right now:

> ![image](https://github.com/bethylamine/bethylamine.github.io/assets/130214958/283a74ed-c3e9-4e77-8a7c-1475a3442da5)

Soon, other features will be rolled in to improve QoL and to offer more trans-supportive features. Check out the github project
[here](https://github.com/bethylamine/soupcan).

## Mark reasons

* **Manually marked** -- Marked in Shinigami Eyes (n.b. not all users marked by Shinigami Eyes are in the database)
* **Reported by extension creator** -- Marked manually by @bethylamine
* **Reported by moderation team** -- Marked manually by a community moderator
* **Reported by \<X\> users** -- Got enough reports to be marked red by community, from X number of users
* **Marked via content \[\<X\>\]**[^1] -- Transphobic content found in their name, bio and/or tweets, with a score of X
* **Marked by hashtag usage**[^1] -- Used transphobic hashtag (in sincerity) in a tweet that got some traction
* **Marked by likes**[^1] -- Had a like pattern of transphobic tweets
* **Marked via GPT**[^1] -- Tweets relating to gender or trans issues were deemed transphobic by ChatGPT
* **Marked via TransphobeB**[^1] -- User existed on the @TransphobeB blocklist (This reason is the most likely to be false positive.)

## Why the name 'Soupcan'?
It's a reference to [SOPHIE - VYZZE](https://www.youtube.com/watch?v=RBGYQnjxMmI) the lyrics go "Make it pop red and white, tomato soup can"

<video onloadstart="this.volume=0.25" controls>
  <source src="https://github.com/bethylamine/bethylamine.github.io/assets/130214958/3edb3495-201a-4d1d-9875-fc7b814eeaa5" type="video/mp4">
Your browser does not support the video tag.
</video>

[^1]: Automatically labelled
