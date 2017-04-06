---
layout: page
title: Guidelines
subtitle: Rules for contributing to our awesome project
date: 2017-03-23
---

In order to keep our project sane and usable for everyone, we decided to set up
a couple of rules.

Mostly these rules really just ensure that the packaging quality is at high
enough standard and that we have someone to contact if problems arise.

So, long story short, this is what is required from your buildservice submission:

 * Inherited packages from OBS must link to respective released versions (42.1 ffmpeg in our instance links to 42.1 ffmpeg in OBS).
 * All changes must be done in the Devel project (Tumbleweed) via submit requests.
 * Released products branches are handled with maintenance approach (like a normal openSUSE release).
 * All non-linked project specific packages must have a designated maintainer in them.
 * No overwriting of system provided packages (we will not accept newer version than those that are already included in the openSUSE update repository).
 * Packages must adhere to the [openSUSE packaging guidelines](https://en.opensuse.org/openSUSE:Packaging_guidelines).
