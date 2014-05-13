---
layout: post
title: "Convert LESS to Sass"
date: 2014-05-08 10:29:54 -0400
comments: true
categories:
---

In my quest of building out a starting point for my web projects, I researched and tested out quite a bit of the CSS frameworks out there. I was looking for a grid system that would be pretty straightforward for me to pick up and be as universal as possible for responsive and different browsers environments (I'm looking at you IE 6-8)

I was first introduced to Sass and have been using it since without looking at Less or Stylus as I really didn't have the need. In my CSS framework testing, I ran into a system that was based on Less that didn't have a Sass alternative so I decided to start to convert it over to Sass to try it out. Unfortunately this wasn't the grid system I was looking for but glad to have this experience if I run into any other Less projects in the future.
<!--more-->
Overall the syntax for Less and Sass are pretty similar in some aspects so as long as its not too involved, it should be pretty straightforward to convert over. I'm sure there are some converters out there or in the works but think its a good practice to handle this manually. Its a good way to get familiar with the code and see how all of the parts work together with one another.

The obvious first step would be to rename your files with the .less file extension over to .scss or .sass. I personally use the .scss formatting on my Sass files so I've used that file extension.

###Imports
Imports will remain the same with using the `@import` to import in your various source files.

###Variables
This will be the biggest area where you'll more than likely have the most revisions. Less prefixes variables with @ while Sass uses $

``` [title]
// LESS
@variable1 : 12;
@variable2: 30;

//SASS
$variable1: 12;
$variable2: 30;

```
