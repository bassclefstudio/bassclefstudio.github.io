---
title:  "ScratchCompiler"
excerpt: "Building a pseudo-emulator in Scratch"
date: "2021-03-28T00:17:00-05:00"
header:
    teaser: "/assets/images/projects/ScratchCompiler-icon.png"
    overlay_color: "#3c3c64"
    actions:
      - label: "View GitHub"
        url: "https://github.com/bassclefstudio/ScratchCompiler"
      - label: "On Scratch"
        url: "https://scratch.mit.edu/projects/539686245"
tags:
  - development
---

I was recently inspired by [Ben Eater's hardware projects](https://eater.net/8bit) and [this amazing Scratch project by RokCoder](https://scratch.mit.edu/projects/531881458/) ([Turbowarp link](https://turbowarp.org/531881458?fps=50&clones=Infinity&limitless)) to try out making a pseudo-emulator in Scratch, which could run some kind of basic programs in a language that I designed. Version `v0.5` is now out, and it comes with a .NET 5 compiler program that turns human-readable code into a memory map that you can connect to the 'processor' and watch it run. I even managed to code a little game in it, which I thought was pretty neat. The documentation and compiler is available [on my GitHub](https://github.com/bassclefstudio/ScratchCompiler), and the Scratch project is available [here](https://scratch.mit.edu/projects/539686245) on Scratch, or [here](https://turbowarp.org/539686245/embed?hqpen&clones=Infinity&limitless&autoplay) in TurboWarp!