---
title: What Would a Gnu/Linux Arcade Machine Look Like?
published: false
---

Several years ago I interacted with the _Free Software Foundation_ through a post on their official GNUSocial account. They were asking whether they should set up an arcade machine at headquarters. Coincidentally this is a subject I've been thinking about since the early 2010s. This essay explores a few design and engineering questions related to turning a GNU/Linux operating system into a dedicated video game console.

GNU/Linux computer software is remarkably suited to support a curated video game library. While installing any game of a general-purpose computer system like Windows or Linux normally involves no small amount of set-up, configuration, and troubleshooting; a GNU/Linux distribution created specifically for a library of gaming software need not be so. Linux-based desktops have access to Human Interface Device standards and dedicated package managers that can make sure downloaded games work immediately out-of-the-box with no additional configuration. Linux maintainers have full access to the source code of open-source games and can make any changes needed to assure each game is compatible with target software.

Proprietary Standards and Curated Libraries
-------------------------------------------

Video game consoles are notorious for being performance-limited, yet reliable plug-and-play devices. This is mainly a result of vendor lock-in forcing game developers to target a specific, un-changing hardware/software platform. Games for the _Nintendo 64_ must be compiled for MIPS machine code and tested against a specific CPU, GPU, and APU pipeline. _Xbox 360_ games are developed for the Microsoft XNA runtime environment. GNU/Android games are written in Dalvik, a Java-like runtime environment with an option to interface with "native" compiled libraries as well.

On the other hand, the GNU/Linux software ecosystem has accumulated countless programming languages, build systems, and graphics libraries. Open-source video game developers aren't restricted or encouraged to target any one of these, so games developed "for Linux" might need any number of popular, supported, obscure, out-of-date, or unmaintained environments in order to run properly.

Game Controllers, Keyboards, and Mice
-------------------------------------

Video game consoles and arcade machines 
