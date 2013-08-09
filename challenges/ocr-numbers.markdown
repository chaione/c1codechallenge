---
layout: default
title: OCR Numbers Challenge
---
# OCR Numbers

Write a program that, given a 3 x 4 grid of pipes, underscores, and spaces, can determine which number is represented, or whether it is garbled.

## Step 1

A simple binary font has been constructed using only pipes and underscores.

The number is four rows high, three columns wide:

    _   #
   | |  # zero.
   |_|  #
        # the fourth row is always blank

        #
     |  # one.
     |  #
        # (blank fourth row)

Write a program that, given a 3 x 4 grid of pipes, underscores, and spaces,
can determine whether the the grid represents a zero, a one, or garble.

Anything else is considered garble, and can be represented with a '?'

## Step 2

A simple numeric font has been constructed using only pipes and underscores.

The number consists of four rows high, three columns wide:

    _  _     _  _  _  _  _  _  #
  | _| _||_||_ |_   ||_||_|| | # decimal numbers.
  ||_  _|  | _||_|  ||_| _||_| #
                               # fourth line is always blank

There may be several numbers in the input text, one per line.

## Tests

Hint: Remove the `skip` message from the next test once the first test passes.

When all the tests are passing, post the result to a private [gist](http://gist.github.com).

Email the link to the created gist to [kelly@chaione.com](mailto://kelly@chaione.com).

{% include_code ocr-numbers_test.rb %}

## Source
[Inspired by the Bank OCR kata](http://codingdojo.org/cgi-bin/wiki.pl?KataBankOCR)

