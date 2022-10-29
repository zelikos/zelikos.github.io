---
title:  "Why I Use elementary OS"
excerpt: "Why elementary OS became my Linux OS of choice."
categories:
  - posts
tags:
  - linux
  - elementary os
  - linux mint
  - fedora
  - solus
toc: true
---
Ever since I began using Linux in 2016, I've gone through quite a few distributions in search of one to call "home."

I started with [Linux Mint](https://linuxmint.com/) and [Ubuntu](https://www.ubuntu.com/desktop), I've dabbled in [openSUSE](https://www.opensuse.org/) and [Fedora](https://getfedora.org/), and, for quite a while, my favorite distro was [Solus](https://getsol.us/home/).

Three years later, the one that finally put a stop to my distro-hopping was [elementary OS](https://elementary.io/).

So, _why_ did I settle on elementary OS, above all other Linux distributions? <!--more-->

# The Pantheon Desktop

![An image of my elementary OS desktop](https://66.media.tumblr.com/4ee13078b24aef726640bcb76fb5b09e/tumblr_pm9jb48kWr1rohz0jo1_1280.png)

The main thing you'll notice about elementary OS is its desktop environment, Pantheon. Pantheon looks great, but it's also a bit controversial in the Linux community; people like to complain that it's too restrictive, that you can't have desktop icons, or that there isn't a minimize button on windows, for example. However, even as someone who had used Windows for over a decade, none of these things really bother me.

Before settling on elementary, I distro-hopped _a lot_. As a newcomer to Linux, being able to tweak and customize my desktop to my heart's content was amazing. Fast-forward a few years, though, and the realization finally set in: I tended to spend more time _tweaking_ my desktop than _using_ it. Even though the Pantheon desktop doesn't allow much customization, the default look and feel is just fine for me, and without the urge to tweak, I'm much more productive using it.

A great thing about Pantheon is that it has very intuitive keyboard shortcuts. Most of them are based around the Super key (the Windows key on many keyboards); as of elementary OS 5.0, by default, pressing the Super key by itself brings up a keyboard shortcut overlay.

![The keyboard shortcut overlay on elementary OS 5.0 Juno](https://66.media.tumblr.com/aa6d27b39a244570be1f7bdf26002053/tumblr_pmdg1d0arx1rohz0jo1_1280.png)

Not shown on the overlay, but something I'd like to point out to those who complain about the lack of a minimize button, is the Super+H shortcut, which minimizes the active window. For many people, old habits die hard, but I think it's much easier to use a keyboard shortcut---or click an application's dock icon---to minimize a window than it is to click on a small minimize button.

Even with those options, though, I don't usually minimize windows. Instead, I prefer using multiple workspaces and Pantheon's Multitasking View.

![Pantheon's Multitasking View; two windows are side-by-side (_Notes-Up_ and _Go For It!_), with a preview of 3 other workspaces at the bottom](https://66.media.tumblr.com/8acbf36f58267c3b09a3cd7645de8c2d/tumblr_pmdjfmITip1rohz0jo1_1280.png)

Accessible with either Super+Down or Super+S, the Multitasking View let's you see every application you have open on the current workspace. At the bottom of the view, you can also see all of your active workspaces, along with the icon of any open application on its respective workspace. While in the Multitasking View, you have a few ways to cycle between workspaces: Super+Left and Right (which also work outside of the Multitasking View), or by scrolling your mouse wheel.

Overall, Pantheon may be simple at first glance, but it certainly doesn't lack functionality.

# AppCenter

![The elementary OS AppCenter](https://66.media.tumblr.com/6e3bc09dd72082e2c66c81529e528155/tumblr_pmdk6pBYOf1rohz0jo2_1280.png)

AppCenter is one of the key applications of elementary OS; it features a wide variety of free-and-open-source applications, built on Vala and GTK+, that follow the elementary OS Human Interface Guidelines. These curated apps are guaranteed to match elementary's look and feel, ensuring a cohesive experience for users.

One problem with open source software development is funding. With AppCenter, the elementary team aims to solve this problem with a pay-what-you-want model. Developers are able to set a suggested price for their apps, but users can choose any price they want---including zero. Users can also go back and pay for an app later if they choose.

AppCenter has _a lot_ of great applications. One of those is [Notes-Up](https://appcenter.elementary.io/com.github.philip-scott.notes-up), a notes manager with an easy-to-use markdown editor. As I'm starting this blog, I've been using Notes-Up to write this post, since Write.as supports Markdown. There may be other, more purpose-built apps for doing this, but Notes-Up does let me preview the final form of the post, as well as having an easy-to-access local copy of it. Very nice.

![Notes-Up, a notebook app for elementary OS, which features a Markdown editor for note-taking.](https://66.media.tumblr.com/655d95006ba6a33ec3684a16141320ea/tumblr_pmdns3fskC1rohz0jo1_1280.png)

Some other favorites include: [AppEditor](https://appcenter.elementary.io/com.github.donadigo.appeditor), an app that lets you customize the menu entries of applications; [Eddy](https://appcenter.elementary.io/com.github.donadigo.eddy.desktop), which allows users to install .deb packages of applications that aren't available in AppCenter; [Go For It!](https://appcenter.elementary.io/com.github.jmoerman.go-for-it), a productivity app which uses the Todo.txt format, and has a built-in productivity timer (which is great for those that use the [Pomodoro Technique](https://en.wikipedia.org/wiki/Pomodoro_Technique)); [Melody](https://appcenter.elementary.io/com.github.artemanufrij.playmymusic), an alternative music player especially suited for those with large local music libraries.

There's also [Ephemeral](https://appcenter.elementary.io/com.github.cassidyjames.ephemeral), a privacy-focused web browser that protects against tracking and automatically deletes your browsing history when closed. I've made a video going over Ephemeral in a bit more detail, which you can find [here](https://youtu.be/DkPvrUM5JcM).

# Conclusion

Since all parts of elementary OS are free and open source, you _could_ use parts of it on other Linux distros. Pantheon is fairly well-supported on Fedora, and many AppCenter applications are available on Flathub---you can also just build them from the source code.

However, I'd much rather use them on elementary; since Pantheon is developed _by_ the elementary team, you can be sure that it will work best _on_ elementary OS. While many AppCenter apps _are_ on Flathub, in many cases, they're only there due to the community, rather than the developers themselves, which can cause unanticipated problems. So, if you want to use elementary applications, the best way is on elementary OS itself; it's much easier to support the developers through AppCenter, anyway.

Finally, elementary OS is built atop Ubuntu, with version 5.0 (Juno) being built upon Ubuntu 18.04, the latest long-term support release. This provides a stable foundation and the ability to run virtually any application that works on Ubuntu proper.

With the Pantheon desktop, AppCenter, and a rock-solid Ubuntu base, [elementary OS](https://elementary.io) has become not only my favorite Linux distribution, but my favorite operating system entirely.
