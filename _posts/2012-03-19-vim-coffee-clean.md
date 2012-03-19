---
layout: post
title: "vim-coffee-clean"
tags: [vim, projects]
author: Brendan Erwin
mail: brendanjerwin@gmail.com
published: true
twitter-handle: brendanjerwin
summary: "vim-coffee-clean: a Vim plugin that helps keep your .coffee files neat and tidy."
---
{% include JB/setup %}

`vim-coffee-clean` is a new Vim plugin that helps keep a team's .coffee files all looking the same.

It enforces some basic stylistic guidelines and, along with the [Janitor](https://github.com/kossnocorp/janitor.vim) plugin, does a pretty good job keeping things tidy for us.

It currently is implemented as a series of regex transforms on the buffer, but I have plans to make it a bit more sophisticated by utilizing the CoffeeScript compiler's TOKEN output.

You can find the plugin on GitHub here: [vim-coffee-clean](https://github.com/tnwinc/vim-coffee-clean)

Here is a little before and after. Everybody loves screenshots!

![Before](/screenshots/vim-coffee-clean/before.png "Before")
![After](/screenshots/vim-coffee-clean/after.png "After")
