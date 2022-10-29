---
title:  "elementary OS vs Fedora"
excerpt: "Comparisons between elementary OS and Fedora, two of my favorite Linux-based operating systems."
categories:
  - posts
tags:
  - linux
  - elementary os
  - fedora
  - gnome
toc: true
---
# Intro

After a long, long period of distro-hopping, I had settled on [elementary OS](https://elementary.io) as my distro of choice. That installation lasted over 18 months, but a little over two weeks ago I made the switch to [Fedora](https://start.fedoraproject.org/). I wasn't necessarily unhappy with elementary OS, so...what prompted the switch?

# Long Background Info

Prior to settling on elementary, my favorite desktop environment was GNOME; I love the Activities Overview, and seeing the GNOME desktop in action played a big part in my switch to Linux to begin with. However, the experience was plagued by some performance issues. These were most noticeable in the form of stuttery animations in the Overview; it didn't break usability or anything, but it did make the desktop feel slower than it may have actually been.

I had tried elementary OS in the middle of the distro-hopping phase sometime after version 0.4.1 was released. At the time, I was still high on the idea of being able to tweak and customize my desktop--I also really liked KDE Plasma at the time--and so elementary OS, while really nice to look at, didn't really make sense for me at the time.

Then came elementary OS 5.0 Juno.

This was a couple years into my distro-hopping, and by that point I had tried out a number of distros, some multiple times each, and I was starting to realize that I'd much rather have great defaults with maybe *some* customization available, instead of OK defaults with tons of customization. GNOME was only just beginning to see the performance improvements, and animations still felt choppy, so elementary OS Juno came at a good time for me. It was in the beta that I first looked at it, and after being tired of tweaking and customizing so many other desktops, I was enamored by Pantheon. It was restrictive, but the default look and feel was *amazing*. Much like GNOME, it also has an emphasis on multitasking via dynamic workspaces; it's not quite like GNOME's Activities Overview, but similar enough. Add the AppCenter ecosystem on top after Juno left beta, and elementary OS finally put an end to my long distro-hopping phase.

Or so I thought.

# Why I Switched to Fedora

Fast-forward to about a month ago. It was sometime after Fedora announced that 33 would have Btrfs by default. I'd heard of it before, I knew it was the default filesystem on openSUSE, but I had never really researched it much. Since Fedora made that announcement, I decided to look into Btrfs more, and it sounded interesting. So, why did I opt to switch to Fedora after spending so much time with elementary?:

* Now that GNOME had seen a lot of performance improvements, I wanted to give it another good try on my main PC for a proper comparison between it and Pantheon
* When I first built the PC in 2017, I had set up the partitioning so it'd be easy to distro-hop, and had a lot more space allocated to my root partition than I really needed. I could've just resized it, but, Btrfs subvolumes seemed like a more compelling option since I didn't plan on frequent distro-hopping anymore
* I had an issue with my screen flickering, that I *think* started when Ubuntu--and therefore elementary--upgraded to kernel 5.4; something that I could have solved by manually upgrading the kernel, but since I had thoughts of switching anyway, this issue only gave me more reason to do so (at the time, I also wasn't sure that the kernel was the problem)

Now, part of the reason I hadn't done so sooner was because my NAS needed a hard drive replaced for quite a while, which I was unable to do due to financial reasons. So, I definitely didn't want to uproot my system when I couldn't perform backups. By this time, though, I was able to get the hard drive replaced and my NAS was up-and-running again, so after testing installation and configurations on my laptop, I took the plunge into Fedora on my main PC after 500+ days on elementary OS.

I expected that it would be a short-term change; my main reasonings were to test out a mostly-vanilla GNOME, as well as trying a more cutting edge OS with Wayland support and the upcoming PipeWire. At the time of writing this, though...I'm *very* torn between the two.

# GNOME vs Pantheon

I'll start by discussing GNOME and Pantheon, the flagship desktop environments of Fedora and elementary OS respectively.

GNOME is a *very* different experience if you come from a Windows background; the default state of the desktop is simply the panel at the top, and then just your wallpaper visible below that, no desktop icons or anything like that. In my case, before switching over to Linux I had already largely moved away from using desktop icons as I preferred using the file explorer and/or working in the apps directly. So, from the beginning, GNOME's minimalist approach really appealed to me.

My favorite thing about the GNOME desktop is the activities overview. At the press of one key, the Super key, you get access to a lot of functionality: the Dash on the left, containing your favorited and currently-open apps; a panel on the right with a preview of all of your open workspaces; an overview of the apps on your current workspace filling up the middle.

You also have access to what I would argue is the best feature: system-wide search that can also be expanded by other GNOME apps. You can search through all of your apps, all of your files, all of the settings categories; you can initiate a web search, or, with GNOME Games, search for and launch one of your games. KDE Plasma has similar functionality with KRunner, but GNOME having the powerful search on top of the overall minimal design makes for a *very* nice experience. I love it.

GNOME does also have an app grid that shows all of your installed apps, but I rarely even use it in favor of using the Dash or just searching.

Pantheon is similar to GNOME. You get a panel at the top, and a dock at the bottom with your favorited and currently-open apps; no desktop icons here, either. Unlike GNOME's Dash, elementary OS's dock is visible on an empty desktop. I wouldn't say the similarities *end* there, as Pantheon has a similar feature set to GNOME, but things are done differently.

On the left side of the panel, you'll find an application launcher, which also doubles as a search; it's not as extensive as GNOME's, as it focuses on searching your apps, as well as searching for actions within those apps, rather than acting as a system-wide search. That said, I do find myself using Pantheon's app launcher to open apps a *lot* more than I use GNOME's app grid.

Pantheon also features dynamic workspaces like GNOME---accessed via the Multitasking View---although with a horizontal layout rather than GNOME's vertical layout. Both work similarly, but have a few differences:

* GNOME allows you to drag individual apps from one workspace to another, directly from the workspace previews; in Pantheon, you have to go to the workspace the app is on and drag it from there
* Pantheon allows you to rearrange entire workspaces, with all the apps on the workspace moving with it; GNOME doesn't seem to have a way to do this
* GNOME's workspace preview shows the layout of the apps on the respective workspace; Pantheon's multitasking view instead shows the icons of whatever apps are on the respective workspace, rather than a full preview
* GNOME's Activities Overview displays open windows more sensibly; the windows in the overview are generally arranged more closely to their relative locations on the desktop, whereas Pantheon's Multitasking View isn't as good here: a window that was on the right side of your desktop will often go to the left side in the overview and vice versa

A big difference between the two is how these features are accessed: with GNOME, everything is all-in-one in the Activities Overview. Pantheon takes a more modular approach; the multitasking view is entirely separate from the application launcher, with no way to launch apps from it. Instead, it's focused on workspace management. The application launcher is focused on launching apps, as well as searching for and activating extra actions these apps might provide; i.e. searching for an app in [AppCenter](https://appcenter.elementary.io/) (elementary's "app store"), opening a specific settings page, or launching a new private window of your web browser.

For convenience, I think I prefer GNOME's all-in-one approach. From a technical viewpoint though, I appreciate Pantheon's modular approach.

I won't go into it in much detail, but there's also the default styling of each desktop; GNOME has its own default stylesheet, Adwaita, and Pantheon uses the unnamed(?) elementary stylesheet. Overall, while GNOME's Adwaita does look good, I prefer elementary's style. The elementary team is also working on a [brand new stylesheet](https://blog.elementary.io/platform-changes-in-elementary-os-6/) (dubbed greenfield, based on their [GitHub repository](https://github.com/elementary/stylesheet)) for the upcoming elementary OS 6, and it looks *amazing*.

One key advantage GNOME has over Pantheon is extensions, which can provide extra functionality to the GNOME shell. For example, two popular extensions, ArcMenu and Dash to Dock, let me put together a very similar layout to Pantheon.

There are a lot of extensions available, but the biggest downside is that new releases of GNOME can often break them. The more popular extensions usually keep up with new GNOME releases just fine, but it's worth remembering that it isn't a stable API.

In my case, I like keeping my use of extensions to a minimum as I'm fairly comfortable with the vanilla GNOME workflow. The extensions I do use give me an experience closer to Pantheon, though, so...

Choosing between the two desktops is *very* hard for me, but Pantheon just barely edges out GNOME.

# elementary (and Ubuntu) vs Fedora -- Technical differences

That was a lot to say on the desktop environments, and honestly this section is probably gonna be shorter. As it's based on Ubuntu, many of my comparisons between elementary OS and Fedora will largely be a matter of Ubuntu vs Fedora; the biggest differences that elementary OS have with Ubuntu are the Pantheon desktop, and the AppCenter ecosystem. So, that being said, let's start with availability of apps.

My order of preference for installing apps these days is Flatpak -> the distro's repositories -> snap or AppImage -> adding an external repository (like a PPA on Ubuntu, or COPR on Fedora). With that in mind...both distros have my app needs covered, because most of what I install comes from [Flathub](https://flathub.org), and everything else is filled out by snaps or just from the distro's repos. For anything I do need to install from the distro's repos, though, Fedora does have elementary OS beat: Fedora has a 6-monthly release cycle, whereas elementary OS is based on the LTS releases of Ubuntu, meaning ~2 years between major releases. While elementary's first-party apps, and those in AppCenter, are kept updated through most of that cycle, everything else comes from the Ubuntu repos. Fedoras packages are updated more frequently than elementary's non-curated ones.

That being said, aside from Mesa drivers, I rarely actually *need* any of those non-curated packages to be updated so frequently. I might like being on the cutting edge, but the LTS base is perfectly fine.

While I do largely prefer Flatpaks to snaps, I do still use some snaps, and they generally work better on Ubuntu-based distros like elementary.

In Fedora's favor, though, I do *like* being on the cutting edge even if I don't need to be, and the Fedora repos do have the Pantheon desktop available, as well as many elementary apps. The Pantheon desktop has some missing parts, though, and there are some quirks that aren't present on elementary---understandable since Pantheon was first developed with Ubuntu in mind, with work ongoing to make it more distro-agnostic. Still, it is usable.

That said, I prefer Pantheon to GNOME, and while I do appreciate the work being done to package and maintain Pantheon on Fedora, the most complete Pantheon experience *is* on elementary OS, as is their AppCenter ecosystem.

Finally, I want to talk APT vs DNF. APT is the package manager used by Ubuntu, whereas DNF is used in Fedora. APT feels faster to me, but DNF's output is a *lot* easier to read, even while providing more information; doing a `dnf search <package>` lists the results by different criteria, whereas `apt search <package>` is one long alphabetical list (the `--names-only` flag for apt helps this somewhat).

# Ideals

Perhaps the biggest reason I favor elementary OS is because I believe that they truly want to push desktop Linux forward, a noteworthy example being the [AppCenter for Everyone](https://www.indiegogo.com/projects/appcenter-for-everyone#/) initiative. They also provide great documentation for developers to [get started writing apps](https://developer.elementary.io/). It doesn't quite cover everything, but it's a great starting point.

I also want to clarify that the above isn't meant to be a knock *against* Fedora or GNOME, I'm just much more familiar with the elementary side of things, having gone through their documentation myself and writing a [simple app](https://appcenter.elementary.io/com.github.zelikos.rannum/) of my own.

# Going Forward

Going forward, I'll stick with Fedora at least until Fedora 33 comes around, as I want to see how the upgrade process goes. My plan beyond that is to wait until elementary OS 6 is released before switching back, but I might do so sooner. Not sure yet. We'll see if Fedora 33 with GNOME 3.38 blows my mind or not.

After I switch back, I do expect to keep Fedora around in GNOME Boxes; it runs surprisingly well in a VM.

Both operating systems are fantastic, and while elementary OS remains my favorite, Fedora has turned out to be a *very* solid #2.

Gonna miss DNF when I'm back on elementary, though...
