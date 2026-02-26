---
layout: page
title: "Super Mario in MIPS Assembly"
description: "Animated Mario character with physics and input handling, written entirely in MIPS assembly."
img: assets/img/super-mario-mips.png
importance: 12
category: fun
---

[github.com/ShreyJ1729/UTD/tree/main/cs2340/bitmap-project](https://github.com/ShreyJ1729/UTD/tree/main/cs2340/bitmap-project)

An animated, playable Mario character written entirely in MIPS assembly for CS2340. Renders to the MARS bitmap display with 2×2 pixel units, supports WASD movement with wrapping, and features run/idle animation frames.

To keep the growing codebase manageable, nearly every operation was wrapped in a macro — from pixel drawing and coordinate math to frame rendering and input processing. This made debugging significantly more tractable at the cost of some verbosity.

Runs in [MARS](http://courses.missouristate.edu/KenVollmar/mars/) with the Bitmap Display and Keyboard Simulator tools.
