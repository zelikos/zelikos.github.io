---
title:  "Thoughts on PeerTube & LBRY"
excerpt:
categories:
  - posts
tags:
  - peertube
  - lbry
  - youtube
toc: false
---
Recently, I synced my YouTube channel with LBRY, so most of my video content is now also available there. I like LBRY, because it's "a free, open, and community-run digital marketplace," as they put it [on their website](https://lbry.io). At first glance, it comes across as a decentralized alternative to platforms like YouTube, as most of what you'll see in the LBRY app is video content (although, I've also seen some FOSS games there recently). However, there's another free, open, and decentralized YouTube alternative you may be aware of: PeerTube.

PeerTube is built on ActivityPub, as part of the fediverse: there isn't just one single PeerTube server, but rather a number of separate servers that federate with one another. In other words, different servers can communicate with one another; content that's hosted on one server is accessible by users on another (provided that said server isn't blocked).

LBRY, on the other hand, is built on blockchain technology. I'm much less familiar with how it works, but from what I understand, content on the LBRY blockchain is distributed among every user, with no servers required.

So... Which is better? <!--more-->

With PeerTube, if you have the means, you can have your very own PeerTube instance to host your content; you have complete control over it, and it's all available to the rest of the fediverse.

![A screenshot of ShareTUBE, one of many PeerTube instances.](https://spee.ch/0fcb29889612966cc2d3ea92cff8ff2d376e509c/sharetube-a-peertube-instance-2019-02-21.png)

Though, what if you _don't_ have the means to host your own instance? Then you're still reliant on someone _else's_ server. If that server goes down, then there goes everything you uploaded to it. Other than that, you may have a limit to how much you can upload, depending on the instance. Overall though, I _do_ still believe that federation is better than relying on a single, central entity (i.e. YouTube).

So, how about LBRY? As mentioned before, it runs on blockchain tech, rather than a federation of many instances/servers like how PeerTube is. In very simple terms, it's even *more* decentralized than the fediverse. In the case of LBRY, access to your published content is controlled by _you_---or more specifically, by whomever has access to your local LBRY wallet. If you lose access to that wallet, though, you do lose access to to *managing* the content associated with it, but the content itself remains on the network.

As for why it's even called a "wallet"... LBRY uses its own cryptocurrency, called LBC. As a user, you can earn LBC by simply using the LBRY app; as a publisher, you "claim" a place for your content on the network with a deposit of LBC; this requires, in my experience, a very minuscule amount. You also have the option to charge LBC for others to view your content. Most of what I've seen so far has been with 0 charge, though.

While the primary focus of the LBRY app seems to be on video content, the LBRY protocol isn't limited to _just_ video. You can also host images, audio, and even games:

![Hartwig Chess Set, an open source chess game available on LBRY and Github.](https://spee.ch/03329a2ba91ed1afe3158183a8ac458eb3740b65/hartwig-chess-set-Screenshot-from-2019-02-21-204056.png)

~~There's also [Spee.ch](https://spee.ch/about), which is basically a website front-end to the LBRY network. You can publish to the LBRY network from it, either through a channel, or just anonymously---great for hosting images for blog posts.~~

**2022/10/28 Update**: Spee.ch has long since been shut down; content that was uploaded to it is still accessible, but the website itself no longer is.

What really sets LBRY ahead of PeerTube, though, is that you can [sync your YouTube channel](https://lbry.io/youtube) with the LBRY network, as I touched upon earlier. Very, very convenient.

Overall, I like both, but as a content creator, I find myself leaning more towards LBRY right now; I don't have to host my own server, but I also don't need to worry about an upload limit. Although, you can't (yet) leave comments on videos, so community interaction may be better with PeerTube.
