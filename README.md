# Works Eventually

**Two simple tasks. A computer with other ideas.**

A pair of browser games about software that turns the smallest job into an afternoon. Created by [Paul Hewitt](https://impaulhewitt.com).

[**Play Works Eventually →**](https://workseventually.com/) · [Open FORMALITY](https://workseventually.com/#formality) · [Open Install One Program](https://workseventually.com/#installer)

![The Works Eventually CRT workstation, with recessed glass, a deep monitor casing, and a note from HR.](screenshots/entrance.png)

## The brief

Make an ordinary office computer feel like a place worth exploring—and make its inconvenient software fun to use.

The experience begins at a dimensional CRT workstation. Entering a game expands its screen into a full Windows 98-style desktop, complete with application windows, shortcuts, a Start menu, and a taskbar.

## Two programs, one desk

**FORMALITY** asks you to enter your name. Eighteen scenes later, you may have satisfied the buttons, forms, support desk, and printer.

**Install One Program** asks you to install exactly one program. Twenty-two puzzles cover component choices, DLL dependencies, adapter matching, defragmentation, configuration repair, and the inevitable request for Disk 2. The reward is a small working document editor.

![Install One Program running inside the shared desktop.](screenshots/installer.png)

## Design and engineering

- A curved, recessed CRT entrance transitions into the playable desktop; reduced motion skips the zoom.
- Each application preserves its own progress while switching windows pauses the inactive game.
- Keyboard and touch controls support the puzzles, with optional hints and a way past a stuck step.
- Clear field feedback, readable instructions, and responsive layouts make the next action understandable, even when the software is being unhelpful.
- Built with **Astro, TypeScript, and CSS**, deployed as a static site on **Vercel**.

Complete flows were verified in actual Chrome browsers, including desktop and emulated mobile viewports and touch input.

<img src="screenshots/mobile.png" alt="Works Eventually on a narrow mobile screen." width="300">

## About this repository

This is a portfolio showcase containing the project write-up and rendered screenshots. The implementation repository remains private.

[Play the games](https://workseventually.com/) · [More from Paul Hewitt](https://impaulhewitt.com)
