---
layout: essay
type: essay
title: "I Like Bootstrap 5"
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

## A quick comparison
I recreated a shopping website trying to use as many Bootstrap 5 classes as I could. On the left is the real website and on the right is my imitation:<br>
<img class="float-start" width="750px" src="../img/UI Design Reflection/ado_shop_real.png">
<img class="float-start" width="750px" src="../img/UI Design Reflection/ado_shop_copy.png"><br>
You can see that Bootstrap 5 does have its limitations, thought it certainly came close to whatever custom HTML the real website uses. I was unable to copy the legal links styling completely, Bootstrap did not have icons for the accepted payment methods seen on the real site, and I was also unable to imitate country/region and language options. However, I would say that this is more indicative of my mastery over Bootstrap 5 rather than its limitations. The footer with the social media icons looks very similar and the styling for the newsletter ad is also very similar. Though you can not see it in the comparison, I actually did not use any Bootstrap 5 containers for these elements and instead used a custom class to mimic the padding of the real site, which means that if you were to change the size of the window viewing the webpage, it would mess up all of the styling. That's why I think it's incredibly important to utilize the classes given by Bootstrap 5, as mentioned before, those auto-adjusting margins are very important for a webpages readability.

## To conclude
I think Bootstrap 5 is a wonderful tool that people should use. It certainly has its use cases and is very wortwhile to learn as it will teach you more about HTML as a whole. While it may not have been too useful when it came to mimicing the website I showed above, trying to use Bootstrap 5 to imitate it certainly helped me understand HTML a lot better and understand why good HTML is important for a good website. 