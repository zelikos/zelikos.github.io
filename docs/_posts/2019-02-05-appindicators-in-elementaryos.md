---
title:  "AppIndicators in elementary OS"
excerpt: "Thoughts on the removal of AppIndicators support in elementary OS."
categories:
  - # updates, guides, posts
tags:
  - linux
  - elementary os
toc: false
---
The latest version of elementary OS, 5.0 (codenamed Juno), has been fantastic since its debut back in October 2018. While the overall look and feel is the same as before, many aspects of the OS were further refined and pollished. All-in-all, Juno was a great release, however, like many things elementary, it wasn't without some bits of controversy. <!--more-->

A notable omission in 5.0 was support for application indicators (perhaps better known as "system tray icons").

![The right side of wingpanel, showing the Pantheon desktop system indicators](https://66.media.tumblr.com/450d1c48abec473dcadeec202a9b2546/tumblr_pmgxczDiiy1rohz0jo1_500.png)

elementary OS _does_ still support indicators. _System_ indicators. In other words, indicators intended to give quick information about the state of the system, rather than application-specific indicators.

A lot of people see this as a negative thing. After all, appindicator icons are part of the traditional desktop paradigm, right?

So what? Tradition does not always equal _best_. I understand that a lot of people like to do things the way they're used to, but, especially on elementary OS, appindicators just feel out of place to me.

Consider the layout of the Pantheon desktop: You have the wingpanel at the top, with application launcher on the left, date/time in the center, and system indicators on the right. At the bottom, you have the dock, where all of your pinned and currently-running applications are displayed.

![An image of my elementary OS desktop](https://66.media.tumblr.com/beaed6d34f5fe2e845275d6c6531cf0d/tumblr_pmgz7hwtRK1rohz0jo1_1280.png)

Since your applications are already displayed in the dock... why would you want a _separate_ set of icons up in the top-right, just for extra options of the respective application? If anything, those actions should be accessible by right-clicking an application's icon in the dock. Native elementary applications support (and encourage) this, as do some third-party apps such as Steam. Having a separate location for these sorts of quick-actions just doesn't make sense.

![Steam's quicklist in the elementary OS dock](https://66.media.tumblr.com/8da335de27671cc883171ed33d8bfa8f/tumblr_pmgz4eGXjy1rohz0jo1_500.png)

The elementary OS Human Interface Guidelines go into this, and how applications _should_ integrate with the system, in much more detail [here](https://elementary.io/docs/human-interface-guidelines#desktop-integration). It is also discussed in [this Github issue](https://github.com/elementary/wingpanel/issues/96#issuecomment-401412541).

Unfortunately, while I do believe that the elementary OS approach is better, the biggest problem is that many third-party applications _rely_ on an appindicator for certain actions. So, many of them actually _lose_ functionality on elementary OS.

For me, this isn't a huge issue. None of the applications that I regularly use suffer much from this, if at all. However, there are quite a few people out there that rely on apps that _need_ appindicator support to function completely. While I would urge people to find alternative applications that don't rely on it, this isn't always possible. So if you _are_ in that situation, there are guides available to restore appindicator support in elementary OS Juno, such as [this one](https://github.com/mdh34/elementary-indicators), or [this one](https://www.linuxuprising.com/2018/08/how-to-re-enable-ayatana-appindicators.html). Just remember that doing this is unsupported on elementary, and _may_ lead to issues.

All in all, I'm in favor of elementary OS's decision to remove appindicator support, and I completely understand their reasoning for doing so. But, I also understand why people are mad about it. This was definitely a controversial decision, but I hope it pays off for elementary in the long run.
