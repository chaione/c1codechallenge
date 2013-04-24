---
layout: default
title: Boggle Solver Challenge
---

# Boggle Solver challenge

[Boggle](http://en.wikipedia.org/wiki/Boggle) is a word game played with
alphabetic letter tiles arranged randomly on a grid. Players must identify
words spelled by sequential adjacent letters in any direction
(horizontally, vertically or diagonally), but may not use the same
letter tile twice.

## Challenge

Write a program that solves a 5x5 randomly arranged Boggle grid.

Assume that your input file looks like this:

    ANRAI
    GANCE
    GLTIO
    DSERI
    SXOCL

Each line has exactly 5 characters followed by a new line `\n` character.  There are 5 lines.  The output would be something like the following:

    NAG
    RAN
    TAN
    TAG
    RICE
    SET
    REST
    ...

## Going Further

* What external resources would help?
* What factors impact performance? What would you do to improve them?
* What are the key data structures in use here? What makes them more
  appropriate than alternatives?
* Can your solution handle words that occur within other words? i.e.
  `'catcher' -> ['cat', 'catch', 'her']`

