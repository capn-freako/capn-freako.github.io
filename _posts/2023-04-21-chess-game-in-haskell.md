---
layout: post
title: 'Chess game written in Haskell.'
date: '2023-04-21 13:49:00 -0400'
categories: 'functional-programming haskell game-theory chess'
...

I needed a short distraction and was jonezing to write some Haskell again.
So, I wrote a [simple (and not very good) Chess program](https://github.com/capn-freako/freaky-chess).

I'd love to hear thoughts on how to make the board evaluation heuristics more performant.
I've gone through several rounds of profiling/improving the code, now, but can't seem to get useful performance beyond 3 move look-ahead. :(
