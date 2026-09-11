+++
title = 'First post, fourth revision'
featured_image = "/images/header.png"
omit_header_text = false
date = 2026-09-11T14:09:00-06:00
summary = 'You ever find yourself doing the same thing over and over again?'
draft = false
+++
# The fourth time is the charm
I finally took down my old dual-Xeon setup in favor of a single Ryzen machine.
Fewer cores, but better performance across the board anyway.
This also means I had to take my website down again.
I don't want to rebuild and rehost it locally, no sense in doing that.
Would rather not screw around with my firewall, so this time I've moved things to GitHub Pages.
The hope is that the website will be more consistently available (ignoring the fact that GitHub is unreliable as hell).
Since I only ever wanted a static website, I figure it should do fine.
Setting this crap up took me the entire day, and that's thanks to Hugo having vague documentation and Ananke having HORRID documentation.
Seriously, it's beyond outdated and written in code - not the code that I actually understand, mind you.
But I think I've gotten things figured out.

I'm now able to just update my website via git and I can write everything in markdown like I like.
Plus, I can do it all through the Helix editor so that's a plus.
Obviously I can edit things in VSCodium, too, but Helix is fine for quick posts such as this one.

At some point, I'll go through and reupload some of my old posts. I want to review them first, though.
I had previously written what I thought was a really nice introduction to how the Linux process works from start to finish, only to realize I framed it all wrong.
Specifically, I wrote it from the perspective of someone using `runit`, which is a faux pas considering I should've follwed `SysVInit`'s structure.
So be on the lookout for that rewrite if you want to read it. Wouldn't call it entertaining, but I'll see what I can do.

Anyway, that's all for now. See you whenever I see you.
