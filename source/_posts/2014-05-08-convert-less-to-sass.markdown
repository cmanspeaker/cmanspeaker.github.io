---
layout: post
title: "Convert LESS to Sass"
date: 2014-05-08 10:29:54 -0400
comments: true
categories: [Code]
---

In my quest of building out a starting point for my web projects, I researched and tested out quite a bit of the CSS frameworks out there. I was looking for a grid system that would be pretty straightforward for me to pick up and be as universal as possible for responsive and different browsers environments (I'm looking at you IE 6-8)
<!--more-->
Overall the syntax for Less and Sass are pretty similar in some aspects so as long as its not too involved, it should be pretty straightforward to convert over. I'm sure there are some converters out there or in the works but think its a good practice to handle this manually. Its a good way to get familiar with the code and see how all of the parts work together with one another.

The first step would be to rename your files with the .less file extension over to .scss or .sass based on your syntax preference.

###Imports
Imports will remain the same with using the `@import` syntax to pull in your various source files.

###Variables
This will be the biggest area where you'll more than likely have the most revisions. Less prefixes variables with @ while Sass uses $

``` sass Variables

// LESS
@var1: 12;
@var2: 30;

// SASS
$var1: 12;
$var2: 30;

```
###Mixins
This will be the biggest area where you'll more than likely have the most revisions. Less prefixes variables with @ while Sass uses $
