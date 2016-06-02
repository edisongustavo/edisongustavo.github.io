---
layout: post
title: "Hello world"
date: 2016-06-02 18:10:00
description: Blog description and first post
share: true
---

# First post!

Ok, so I'm pretty new in this "blog business" however I like writing.

I will try to post technical stuff here. Maybe I'll post non-technical stuff too, however, expect those posts to be rarer.

I'm a computer scientist who graduated at [Universidade Federal de Santa Catarina](http://ufsc.br/) in Computer Science.


{% highlight yml %}
share: true
{% endhighlight yml %}

If you want to disable some of them - go to **_config.yml**:

{% highlight yml%}
share:
  facebook: true
  twitter: true
  gplus: true
  linkedin: true
  pinterest: true
  email: true
{% endhighlight yml%}

# Add new buttons

To add new buttons:

1. add icon name in **_config.yml**;
2. add section in **_includes/share.html**;
3. add styles in **css/theme.css**.