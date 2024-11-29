---
title: "My Setup"
date: 2024-10-21T16:40:21-05:00
slug: 2024-10-21-my-setup
type: posts
draft: false
categories:
  - default
tags:
  - software
---

I'm always fiddling with the tools I use, so it's possible this eventually becomes out of date. But for now, here's what I use:

### The OS

My first computer was a Mac. Then I got a Windows computer. At some point, I installed Linux (Mint) on that machine and used that full-time. Now I use MacOS full time. While it's far from perfect, seamless integration with my iPhone, Airdrop, native Arc (see [The Browser]({{<ref "my-setup#the-browser" >}})), gives it an edge over the alternatives, especially when coupled with the [AeroSpace](https://github.com/nikitabobko/AeroSpace).

My theatre work often requires [QLab](https://figure53.com), an incredible piece of software that sadly only runs on Mac. When I daily drove Windows and Linux, I owned a supplemental Mac Mini. I no longer need more than one device.

### The Editor

My primary editor is Neovim ([config](https://github.com/zachicecreamcohn/nvim-config)). I used VSCode for the longest time until I switched to the JetBrains suite. I really only used vim when SSH-ing into a Linux instance and it always felt a bit clunky. But this past summer at [Amplify](https://amplify.com), I had the pleasure of pairing with [Denis Lantsman](https://github.com/dlants). There are a couple moments every now and then when you come to the exciting and daunting realization that you're just barely scratching the surface of what is possible; seeing Denis absolutely zoom through the codebase in neovim was one of those moments. I've since converted and can't beleive I didn't do it earlier.

*Note: [Alacritty](https://alacritty.org/) is my terminal emulator.*

### Notes

Obsidian is amazing.

### Email

My Google account is the hub for all my communications and life organization, so I don't mind paying for the best possible experience. I pay for a single seat of Google Workspace's Business plan. I back up all my files to Drive and use email aliases and inbox filters that automatically tag incoming mail based on the alias used: theatre@zachwcohn.com, software@zachwcohn.com, travel@zachwcohn.com, etc. If I suddenly got into glass blowing, I'd create the alias glass@zachwcohn.com and add a filter to tag all mail sent to that address accordingly.

I like to keep my inbox organized. If an email is still in my inbox, it means I need to read or respond to it, or I’ve just sent a message and I’m waiting for things to wrap up (like an open buffer in Neovim). Once I’ve finished with an email or no longer expect a reply, I tag and archive it.

Finally, there's something to be said about the "it just works" quality of (most) Apple devices. As of now, it's just not worth my time to struggle to tune a Linux machine to reach my standards and requirements. Maybe someday...

### Keyboard
I use a wireless corne split keyboard. I've got my eues on the Glove80, but I have found the small form factor of the corne to perfectly fit my needs. I like that it's incredibly portable which means I can maintain consistency in my typing experience no matter where I go. I started using a split keyboard becuase I was experiencing some wrist pain and I've found that it's helped a lot. And it's just fun to use. My one complaint is that it makes switching to conventional laptop keyboard a bit of a pain when using someone else's machine.

### The Browser {#the-browser}

I'm a big fan of [Arc](https://arc.net). I use Spaces to keep my activities separate, which not only helps bundle related sites and login sessions together but also improves my mental model of the browser when working. For example, when switching from schoolwork to development for the university newspaper, toggling between differently styled Spaces with their own organized bookmarks helps me switch mental contexts.


### Passwords

For my password manager, I use the free public [vaultwarden](https://github.com/dani-garcia/vaultwarden) instance hosted at [vaultwarden.net](vaultwarden.net) alongside BitWarden's browser extension and mobile and desktop apps.
