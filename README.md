# mandown

A man-page inspired Markdown pager written in C.

Considering to change the name in later release.

## What is it

Need to lookup things from README? Or from manual page? Or perhaps just want to install something cool... (**Looking for work buddies**)

## Update

**Line Wrap** now reacts to terminal resize events.

## Sample

![screenshot](./screenshot.png)

- This is nested list
  - 😊 is rendered
    - So is 🌚 🌕 🌖 🌗 🌘 🌑 🌒 🌓 🌔
      - It is 🔥
        - Me right now 💀

This is <ins>underline</ins>

This is <em>italic</em>

This is <strong>bold</strong>

This is a <kbd>key</kbd>

Can you see this <s>strikethrough</s> or this <del>strikethrough</del>?

`This is a code block`

## Install

Current version is incomplete. However, it should work on simpler Markdown documents.

The Ncurses UI is still being developed for different HTML tags.

```bash
$ git clone https://github.com/Titor8115/mandown.git
$ cd mandown
$ make
```

### Usage

```bash
$ cd mandown
$ ./mandown README.md
```

Mouse wheel scrolling is supported! (if your terminal emulator allows)

Scroll Up: <kbd>↑</kbd>, <kbd>k</kbd>, <kbd>BACKSPACE</kbd>

Scroll Down: <kbd>↓</kbd>, <kbd>j</kbd>, <kbd>ENTER</kbd>

Exit: <kbd>q</kbd>

if it compiles but doesn't run, try updating your ncurses library.

```bash
$ apt-get install libncursesw5-dev
```

## Todo

- Format

  - [x] markdown
  - [ ] troff

- Command-line

  - [x] test version
  - [ ] document pathfinder

- Ncurses
  - [x] keyboard control
  - [x] coloring
