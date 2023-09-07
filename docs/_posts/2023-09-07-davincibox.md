---
title:  "DaVinci Resolve, but in a box"
excerpt_separator: <!--more-->
categories:
  - posts
tags:
  -
toc: false
---

My phrasing is gonna make this sound a lot grander than it actually is, but I'm here to announce [davincibox](https://github.com/zelikos/davincibox) as a thing I'm working on. <!--more-->

Any who have been following me from my Linux-focused YouTubing days are likely aware that, for a time, I was hell-bent on getting DaVinci Resolve to work well on everybody's[[1]](#1) favorite free desktop platform. The YouTubing part has subsided a lot in recent years, but when I have needed to do video production on Linux, Resolve has remained my video editing software of choice (I do always keep an eye on the FOSS video editors, though, such as [Kdenlive](https://kdenlive.org/)).

So, with that in mind, what the heck is "davincibox"?

A couple of years ago, I started using Fedora Silverblue. Basically, Silverblue is an image-based version of Fedora Workstation, using OSTree for atomic updates and easy rollbacks. This also means that, say, to install the required dependencies running DaVinci Resolve, you would normally need to layer those packages on top of your OS image. This is doable, but far from ideal. Fortunately, that's where containers come in handy, and tools like [distrobox](https://github.com/89luca89/distrobox) make using them very convenient. Instead of layering these dependencies, you can instead install them in a container, keeping a clean separation from your host OS. 

That's where Davincibox comes in. It's entirely possible to use distrobox (or toolbox) to [set this up manually](https://gist.github.com/bluesabre/8814afece711b0ca49de34c41e50b296), but why not simplify the process? Davincibox is a ready-to-go container that you can use with distrobox to then install and run DaVinci Resolve from (but you do still need to download DaVinci Resolve from Blackmagic's website). I have instructions for the setup process in the repo's README, as well as an optional—but very recommended—setup script to make the process even easier.

This is all done [on GitHub](https://github.com/zelikos/davincibox), so I would encourage any suggestions or feedback to happen there if you want to get involved. Specifically, more testing that davincibox and the setup script actually work on different Linux distros and hardware setups would be great. I only have an AMD graphics card myself, so I don't know if the Nvidia parts even work properly.

I've so far tested everything on my main machine with an AMD graphics card running [my own uBlue spin](https://github.com/zelikos/zeliblue), as well as in a few virtual machines running it, elementary OS 7, Vanilla OS 22.10, and Ubuntu 22.04.

 
<a id="1">[1]</a> *Unless you prefer FreeBSD or something else*