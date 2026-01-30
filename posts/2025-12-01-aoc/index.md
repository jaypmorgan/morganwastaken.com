---
author: Jay Paul Morgan
date: 2025-12-01
subtitle: AOC Using Scheme
title: Advent of Code -- Day 1
---

```{=org}
#+PROPERTY: header-args:scheme :session aoc1 :export both
```
# Introduction to Advent Of Code

This year, I thought I\'d try to solve the [Advent of Code
(AOC)](https://adventofcode.com) puzzles using Scheme. I tried this
before (2022), but only made it [day
7](https://github.com/jaypmorgan/aoc/tree/master/2022/scheme). It\'s
also been a long time since I\'ve used Scheme--perhaps lisps in
general--so the solutions may not be the most elegant, but is an
oppurtunity to use a language that I don\'t typically get to use or
reach for in my work.

I\'ll post each of these days as separate blog articles, with a
description of my understanding of the puzzles, and an explanation of my
solution to the current day.

At least for the first couple of days, I will try not to reach for a
library (or even write one myself), but try to program everything
myself. There is definitely a possibility that this could become tedius,
so I am not commiting myself to this for all of the puzzles, but it is
just to push myself to get comfortable with Scheme rather than just
reaching for on-liner solutions that doesn\'t teach me anything.

With that out of the way, let\'s start with Day 1!

# Day 1

``` scheme
(define (f x)
  (+ x x))
```

This is a test.

``` {.scheme exports="both"}
(f 1)
```

``` example
2
```
