---
layout: page
title: Guidelines
subtitle: Rules for contributing to our awesome project
date: 2017-03-23
---

In order to keep our project sane and usable for everyone we decided to set up
couple of rules.

Mostly these rules really just ensure that the packaging quality is at high
enough standard and that we have someone to contact if problems arise.

So long story short, what is required from your buildservice submissions:

 * Inherited packages from OBS must link to respective released versions (42.1 ffmpeg in our instance links to 42.1 ffmpeg in OBS)
 * All changes must be done in Devel project (Tumbleweed) via submit requests
 * Released products branches are handled with maintenance approach (like normal openSUSE release)
 * All non-linked project specific packages must have designated maintainer in them
 * No overwriting of system provided packages (We will not newer version than in openSUSE update repository)
 * Packages must adhere to [openSUSE packaging guidelines](https://en.opensuse.org/openSUSE:Packaging_guidelines)
