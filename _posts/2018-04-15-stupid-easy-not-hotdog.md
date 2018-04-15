---
layout: post
title: Not Hotdog
subtitle: the simplest version yet
gh-repo: shanamatthews/demos
gh-badge: [star, fork, follow]
tags: [demo,cog-services,azure]
---

David Smith - aka [@revodavid](https://twitter.com/revodavid) recently posted on Twitter about his recreation of the ["Not Hotdog"](https://medium.com/@timanglade/how-hbos-silicon-valley-built-not-hotdog-with-mobile-tensorflow-keras-react-native-ef03260747f3) app 🌭- and I can't lie I was pretty jealous.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">I recreated Jian Yan&#39;s &quot;Not Hotdog&quot; application using R and the <a href="https://twitter.com/Azure?ref_src=twsrc%5Etfw">@Azure</a> Custom Vision API: <a href="https://t.co/SO3jjxQ35D">https://t.co/SO3jjxQ35D</a> <a href="https://twitter.com/hashtag/rstats?src=hash&amp;ref_src=twsrc%5Etfw">#rstats</a></p>&mdash; David Smith (@revodavid) <a href="https://twitter.com/revodavid/status/981639949362647040?ref_src=twsrc%5Etfw">April 4, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

I've been wanting to make my own recreation of this app for a long time, especially since I started going through [fast.ai](http://www.fast.ai/)'s updated [Deep Learning course](http://course.fast.ai/).
Naturally, my first thought was to create this myself, using the fastai library... and then I realized it was 11pm and I needed to be up at 6am for a flight the next day.

Fortunately for me, Brian Peek was one step ahead of me. He made a [nice writeup](https://docs.microsoft.com/en-us/sandbox/demos/nothotdog) of how to use the [Azure Computer Vision API](https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/) to create and deploy an Azure Function to determine if a photo was of a notdog (or not).

{: .box-note}
Brian's NotHotdog website: <https://nothotdogweb.azurewebsites.net/>

It seemed cool, and I wanted to try it out... but I had some issues:

1. It was 11pm
1. I had a flight at 8:30am
1. The project was set up as a VS C# solution
1. I didn't have Visual Studio installed on the laptop I had with me

Fortunately, what I did have was an Anaconda distro including VSCode and Jupyter. Python to the rescue! 🐍

Here's what I did to get my very own nothotdog classifier up and running in ~30 minutes:
1. 
