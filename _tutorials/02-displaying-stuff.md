---
layout: post
title:  "Displaying Stuff"
date:   2023-02-15 18:30:00 +0100
categories: tutorial
permalink: /tutorials/02-displaying-stuff.html
---
## Requirements
You will need:
* Follow the [Getting Started](getting-started.html) tutorial

## Background
Games are visually composed of a bunch of 3D objects in a kind of tree hierarchy. The root of that hierarchy is your main `Game` class, which represents the table. Game objects can be displayed by adding them directly to `Game.children`, or parented to other container objects called `Zone`s.
