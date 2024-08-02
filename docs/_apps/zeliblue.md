---
title: Zeliblue
excerpt: Customized dervivative of Fedora Silverblue.
---
![Zeliblue Desktop](https://raw.githubusercontent.com/zelikos/zeliblue/main/repo_content/desktop1.webp)

Zeliblue is a customized [Fedora Atomic Desktop](https://fedoraproject.org/atomic-desktops/) image, based on the [Universal Blue](http://universal-blue.org/) project, featuring the GNOME desktop as the flagship experience.

Notable changes from vanilla GNOME and Fedora Silverblue include:

- Workspace navigation shortcuts are adjusted, with the aim of being more intuitive for horizontal workspaces
- Ptyxis replaces GNOME Terminal as the default terminal, and can be launched with Super+t
- `fish` is set as the default shell in Ptyxis
- [Homebrew](https://brew.sh/) is enabled out of the box
- The `fish` shell is configured to integrate with certain [CLI utilities](#zeliblue-cli) for a more modern terminal experience
- Flathub is set up in the background on first boot, both system-wide (flathub-system) and for per-user installs (flathub-user)
- GNOME Software defaults to installing apps from flathub-user
- Core system apps are installed to flathub-system after first boot
- System apps are selected based on the official [GNOME Core apps](https://apps.gnome.org/), with some substitutions and additions
- And more miscellaneous tweaks

There is also Zeliblue Plasma (zeliblue-kinoite), which uses the Plasma desktop environment instead of GNOME. It replaces multiple apps that are layered into the upstream image with Flatpak equivalents, as well as using `fish` as the default shell in Konsole.

Zeliblue is made with [BlueBuild](https://blue-build.org/).

For more information and to report issues or offer feature suggestions, see the [GitHub repository](https://github.com/zelikos/zeliblue).
