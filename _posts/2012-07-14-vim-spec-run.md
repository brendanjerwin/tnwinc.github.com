---
layout: post
title: "vim spec run"
tags: [vim, projects]
author: Brendan Erwin
mail: brendanjerwin@gmail.com
published: true
summary: "vim-spec-run: a Vim plugin to run your specs."
twitter-handle: brendanjerwin
---
{% include JB/setup %}

`vim-spec-run` is a Vim plugin we developed to make running our specs
(CoffeeScript + Mocha) quick and awesome.

It is designed to work with either `screen` and Terminal.app, or
`screen` and iTerm2.app. (When used with iTerm2, it uses AppleScript for
a little bit more awesome.)

Our usual configuration is:

  - `\t` : Run specs local to the current buffer
  - `\t.` : Run the current buffer's specs
  - `\T` : Run the entire spec suite
  - '\d' : Run local specs in the node debugger

Here is a YouTube of it in use: http://www.youtube.com/watch?v=ZOW4V4iRMJc

You can see it on GitHub here: https://github.com/tnwinc/vim-spec-runner
