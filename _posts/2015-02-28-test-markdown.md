---
layout: post
title: Not Hotdog
subtitle: the simplest version yet
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
---

David Smith - aka [@revodavid](https://twitter.com/revodavid) recently posted on Twitter about his recreation of the ["Not Hotdog"] - https://twitter.com/revodavid/status/981639949362647040. (https://medium.com/@timanglade/how-hbos-silicon-valley-built-not-hotdog-with-mobile-tensorflow-keras-react-native-ef03260747f3) app 🌭, and I can't lie I was pretty jealous. 

I've been wanting to make my own recreation of this app for a long time, especially since I started going through [fast.ai](http://www.fast.ai/)'s updated [Deep Learning course](http://course.fast.ai/).
Naturally, my first thought was to create this myself, using the fastai library. And then I realized it was 11pm and I needed to be up at 6am for a flight the next day... 

Fortunately for me, Brian Peek was one step ahead of me. He made a [nice writeup](https://docs.microsoft.com/en-us/sandbox/demos/nothotdog) of how to use the [Azure Computer Vision API](https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/) to create and deploy an Azure Function to determine if a photo was of a notdog (or not).

Brian's NotHotdog website: https://nothotdogweb.azurewebsites.net/

It seemed cool, and I wanted to try it out... but I don't know about you, but I get even lazier than usual 



Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
