---
inFeed: true
hasPage: true
inNav: false
inLanguage: en
starred: false
keywords:
  - component
  - user
  - input
  - lifecycle
  - maybe
  - item
  - loaded
  - state
  - ideal
  - design
description: 'Modern UI teams are designing components first; Interfaces are merely the thoughtful composition of components. This leaves an often glaring hole for users on "the unhappy path" - The places where users may, intentionally or not, stray from your idealized flow.'
datePublished: '2016-02-11T18:43:02.662Z'
dateModified: '2016-02-11T18:42:57.886Z'
author:
  - name: Vince Speelman
    url: 'https://medium.com/@vinspee'
    avatar: {}
related: []
app_links:
  - type: android
    app_name: Medium
    app_store_id: '828256236'
    package: com.medium.reader
  - url: 'medium:/p/5bfe9b3d6d85'
    type: ios
    app_name: Medium
  - url: 'medium://p/5bfe9b3d6d85'
    type: android
  - url: 'https://medium.com/swlh/the-nine-states-of-design-5bfe9b3d6d85'
    type: web
title: States
sourcePath: _posts/2016-02-08-the-nine-states-of-design-the-startup.md
published: true
authors: []
publisher:
  name: Medium
  domain: medium.com
  url: 'https://medium.com'
  favicon: 'https://cdn-static-1.medium.com/_/fp/icons/favicon-new.TAS6uQ-Y7kcKgi0xjcYHXw.ico'
url: states/index.html
_type: Article
_context: 'http://schema.org'

---
<article style=""><h1>The Nine States of Design - The Startup</h1><p>Modern UI teams are designing components first; Interfaces are merely the thoughtful composition of components. This leaves an often glaring hole for users on "the unhappy path" - The places where users may, intentionally or not, stray from your idealized flow.</p><img src="https://s3-us-west-2.amazonaws.com/the-grid-img/p/009ff2f398001e066c647a6d397b5569782abbfc.png" /></article>

Modern UI teams are designing components first; Interfaces are merely the thoughtful composition of components. This leaves an often glaring hole for users on "the unhappy path" --- The places where users may, intentionally or not, stray from your idealized flow. As we learn to craft systems rather than pages, we must invest effort into shaping these often missed states of design and create with a component lifecycle that can support everyone. Here's the lifecycle as I see it:

# States

## 1.Nothing

What happens before your component does anything? Maybe it's the first time a user sees it. Maybe it's not activated yet. Essentially, the component exists but hasn't started.

[Jonas Treub][0] makes sure framer gets you up to speed.

# 2\. Loading

The dreaded state. In a perfect world, no one would ever see this; There are plenty of ways to keep your loading state subtle and unobtrusive. Facebook does a pretty good job of this:

Facebook uses a "dummy post" rather than a traditional loading spinner.

# 3\. None 

Your component has initialized, but it's empty. No data. No Items. Now may be a good time to get the user to act ("Do this thing!"), or to reward them ("Good job, everything is taken care of").

# 4\. One 

You have some data. On an input, this may be after the first keystroke. In a list, it might be when you have one item (or one left)

[0]: https://dribbble.com/jonastreub