---
title: Hexo in Win10 took me way too long
date: 2016-07-23 14:14:13
thumbnail: https://c1.staticflickr.com/1/33/44514845_572eb5d38a_b.jpg
categories:
 - help computer
tags:
 - my own fault
 - software
---
![I really tried hard](https://c1.staticflickr.com/1/33/44514845_572eb5d38a_b.jpg)
## It was my own fault, really...

I though it would be a fine time to start a blog, so I said "I know, I'll use one of those cool static blog generators."

I also thought it might be a good idea to use my creaky old Windows laptop, which was feeling pretty okay with Windows 10. Let's do it!

<!--more-->

* Install [Git](https://git-scm.com)!
* Install [Node](https://nodejs.org)!
* Uh.. [upgrade npm](https://www.npmjs.com/package/npm-windows-upgrade)...
* [Atom](https://atom.io), because of course.
* ~~[Terminal-plus](https://atom.io/packages/terminal-plus) for Atom~~... Or, uh, 30 minutes later [PlatformIO ide terminal](https://atom.io/packages/platformio-ide-terminal) plugin because it actually works.
  *  Don't forget to set the shell to `C:\Program Files\Git\bin\sh.exe` and the login options to `--login -i`
* I need [Visual Studio 2015 CE](https://www.visualstudio.com/)? Okay. Okay. I can do that (for hours, apparently).
* [Python](https://python.org)? Really? Sure. Yes. Yes, I also love Python.
* ~~Ctrl-s doesn't work? Are you kidding? No hope? Ctrl-shift-s, enter, 'y' isn't quite as convenient.~~
* Did you know that [Skype in Windows will take over your CTRL-S completely](https://darrenmyher.com/2014/01/18/ctrls-stopped-working-on-my-computerturns-out-skype-was-the-reason/)?
* let's get some ssh keys going for this machine.
* `eval $(ssh-agent)` in .bashrc because that's how I roll.
* github repo, let's keep it rolling
* scrape a little space out of my old web hosting that's normally doing other things.

What with all the downloading, installing, restarting, troubleshooting stupid problems (some Windows, some mine), this took 6 hours. Granted, most of that time was spent figuring out how to get Atom to open git bash (and install dependencies) so that I didn't have to open two windows on my creaky old laptop. That's why I wrote it down. JUST IN CASE.

It feels pretty rickety, frankly. But I'm blogging. Poorly. It isn't Hexo's fault, not at all. I quite like it, and I'm sticking with it. I'm just not good at blogging. Also, Windows 10 as a development environment for a Unix guy feels uncomfortable.
