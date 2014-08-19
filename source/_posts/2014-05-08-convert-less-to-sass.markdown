---
layout: post
title: "Convert Less to Sass"
date: 2014-07-08 10:29:54 -0400
comments: true
categories: [Code]
---

When I was first introduced to CSS preprocessors, I started out with learning the Sass syntax. I've been researching different CSS frameworks and ran into a couple of instances where Less was used for its development. I went through the process of converting a Less version over to Sass to test it out in my local environment.
<!--more-->
Overall the syntax for Less and Sass are pretty similar in some aspects with slight differences between the two. There are some larger differences depending on the complexity of the code involved but this post will serve as a basic guide to get started.  I'm sure there are some converters out there or in the works but I'd suggest handling this manually. Its a good way to get familiar with the code and see how all of the parts work together with one another.

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
With Sass, you will include the @mixin declaration and call it later in another property using @include. Less treats its syntax like a class name and does not use the mixin or include declarations. Mixins that use arguments will be set in the parentheses with the differences being the variables syntax (@ - Less or $ - Sass)

``` sass Mixins

// LESS
.border-radius(@radius) {
  -webkit-border-radius: @radius;
  -moz-border-radius: @radius;
  -ms-border-radius: @radius;
    border-radius: @radius;
}

.box {
  .border-radius(5px);
  width: 50%;
}

// SASS
@mixin border-radius($radius) {
  -webkit-border-radius: $radius;
  -moz-border-radius: $radius;
  -ms-border-radius: $radius;
  border-radius: $radius;
}

.box {
  @include border-radius(5px);
  width: 50%;
}

```
