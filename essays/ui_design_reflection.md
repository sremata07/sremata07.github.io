---
layout: essay
type: essay
title: "You May Not Even Need to Ask"
# All dates must be YYYY-MM-DD format!
date: 2026-10-08
published: true
labels:
  - HTML
  - CSS
  - Bootstrap 5
---

<img width="300px" class="rounded float-start pe-4" src="../img/UI Design Reflection/bootstrap5_icon.jpg">

## Bootstrap Containers
These things are my favorite features from Bootstrap. Containers in Bootstrap help you quickly pad and align your items that are contained within the container. My favorite part of these containers is that they automatically adjust their margins automatically when the webpage view is adjusted, upkeeping those wonderful margins and the clean content alignment. I believe that the containers in of themselves are a great reason to start learning Bootstrap 5, even if some of the class names are confusing. 

## What do these even mean anyways?
Some of the class names are understandable in Bootstrap 5, such as `.py-*`  standing for 'padding y-axis - the amount of padding'. But then what about something like `.justify-content-*`? Well, it's supposed position items within a container, but the content justification is reliant on the container items being flex items. Thus, you will have to apply something like `.d-flex` which means to change the element display to be flex, and flex is basically shorthand for a flexible element. Then, before you know it, it starts to look like `<div class="container justify-content-start d-flex py-5"><div>` and my eyes start to glaze over a little bit. Looking through these classes and understanding what they they are getting at can be an arduous task at first, but once you start using them you start to understand the naming conventions and you'll certainly be better off for it.

