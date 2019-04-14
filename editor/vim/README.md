# Vim Cheat Sheet

Personal Vim key mapping references.

## Table of Content

<!-- TOC -->

- [Vim Cheat Sheet](#vim-cheat-sheet)
    - [Table of Content](#table-of-content)
    - [File Operations](#file-operations)
    - [Cursor Movement](#cursor-movement)
    - [Screen movement](#screen-movement)
    - [Search](#search)
    - [Reference](#reference)

<!-- /TOC -->

## File Operations

Funtion | Key
---     | ---
:q(!) | quit (force)
:w | save
:wq / :x | save and quit

## Cursor Movement

Funtion | Key
---     | ---
h, j, k, l , 5l | ←, ↓, ↑, →, →x5
H, M, L | screen top/middle/bottom at the same column
w(W), e(E), b(B) | forward to word(w/ `-`)'s start/end, backward to word(w/ `-`)'s start
0, ^ | line start / non-blank start
$, g_ | line end / none-blank end
gg, G, 5G | first line / last line / line 5
% | matching char (`()`, `{}`, `[]` etc)
}, { | next / previous paragraph of funtion/block

## Screen movement

Funtion | Key
---     | ---
zz | center the cursor position
Ctrl + e / y |  move one line up/down
Ctrl + u / d |  move half screen up/down
Ctrl + b / f |  move one screen up/down

## Search

Funtion | Key
---     | ---
fx, Fx | jump to next / previous occurrence of `x`
tx, Tx | position before-next / after-previous occurrence of `x`
; | repeat previous f, F, t, T search

## Reference

[Vim Cheat Sheet](https://vim.rtorr.com/)