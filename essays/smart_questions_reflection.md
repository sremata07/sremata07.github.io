---
layout: essay
type: essay
title: "You May Not Even Need to Ask"
# All dates must be YYYY-MM-DD format!
date: 2026-09-09
published: true
labels:
  - Questions
  - Analysis
  - StackOverflow
---

<img width="300px" class="rounded float-start pe-4" src="../img/Smart Questions Reflection/smart_questions_reflections_thumbnail.jpg">

## Before asking a smart question, there may already be an answer.

Before Steven Raymond teaches you how to ask a smart question, he first mentions what you should do before you ask. To quickly summarize his 7 suggestions, you should first refer to provided materials, then online sources, then you start analyzing your problem and ask a trusted friend. But why do this when asking a question is easier? If you're not crafting a smart question, you're most likely not going to get a smart answer. So in a way, looking for the answer may actually be the smarter solution. 

## Smart vs not-smart questions:

Firstly, Stack Overflow is an FaQ website for developers and programmers. People ask a question, then people answer, so it's the perfect place to look for answers as well as the perfect place for developers and programmers to ask questions. After combing through through Stack Overflow to look for examples, I have two questions that I think fit the description of a smart question and one that is not a smart question. 

## The not-smart

Below is what I think is a not-smart question by spin58. To summarize; spin58 would like to display two images in HTML using a w-3 card option. However, their image covers their w-3 card and the cards are stacked on top of each other vertically instead of being displayed side-by-side horizontally, like they wamt. They attached their entire block of code of what they appear to be working on.

Q:
``` 
<!--
Source - https://stackoverflow.com/q/80001979
Posted by spin58, modified by community. See post 'Timeline' for change history
Retrieved 2026-09-09, License - CC BY-SA 4.0
-->

<div align="center">
    <div class="row  ">
        <div class="col-sm "> 
            <div class="w3-card" style="width:400px;max-width:50%">
                <img src="image/engagement/001_thanksgiving_basket.jpg"   alt="thanksg" height="300" width="350">
                <br>&nbsp;
                <p align="center">
                    <div class="w3-container">
                        <span class="style14">The Annual Thanksgiving Basket Distribution
                            <br>&nbsp;is a collaborative effort&nbsp; involving 
                            <br>members of Williams Charity.
                            <br>The Market at 25th Street and volunteers
                            <br>from the MichiganFederal Credit Union Along
                            <br>with annual Christmas Basket distribution, the Foundation
                            <br>served more than 800 individuals in 2025.
                        </span> 
                    </div>
                </div>

                <!--2nd display-->

                <div class="col-sm "> Spin
                    <div class="w3-card" style="width:400px;max-width:50%">
                        <img src="image/engagement/001_thanksgiving_basket.jpg"   alt="thanksg" height="300" width="350">
                            <br>&nbsp;
                            <p align="center">
                                <div class="w3-container">
                                    <span class="style14">The Annual Thanksgiving Basket Distribution
                                        <br>&nbsp;is a collaborative effort&nbsp; involving 
                                        <br>members of Williams Charity.
                                        <br>The Market at 25th Street and volunteers 
                                        <br>from the Michigan Federal Credit Union Along
                                        <br>with annual Christmas Basket distribution, the Foundation
                                        <br>served more than 800 individuals in 2025.
                                    </span> 
                                </div>
                            </div>
```
> "I am trying to display two images with text side by side using the w-3 card option. Here are my concerns
> 
> 1. The display puts the image at the very top of the card without any space so the top part of the image consumes(blocks) the card
> 2. The two card displays are showing vertically and not side by side (horizontal as desired)
> Thoughts?"

[Source Link](https://stackoverflow.com/q/80001979)

Here the user spin58 gives a huge chunk of code, and asks only one question, "Thoughts?". I think this is the prime example of a not-smart question because they didn't really showcase what they tried to do besides just attaching their entire block of code, and they only really outlined what they want to happen as if Stack Overflow is an AI Chatbot.  
To test my own understanding on how to create a smart question, I would like to take a close look at this question. Try to analyze with me, as I most likely may have missed a spot that could be improved. 
Now, from this question, you can see there are about 3 areas of improvement. After they outlined what they wanted, they should have mentioned what fixes they've tried. Such as: "I tried to Google how w-3 cards work but I couldn't get anything to work." then another place of improvement would be to attach a block of code of what they attempted. Finally, they should instead attach the block of code that is returning the error they are recceiving. With this whole block of code, it can be hard to pinpoint where their issue is, especially since they don't provide much information. 

## The smart

Below is what I believe to be a smart question, asked by Vincent McNabb. To summarize; Vincent McNabb is working on a web application wants content to fill the height of the entire screen. Their page has a header, and they would like the rest of the content to fill the rest up the page down to the bottom. They then include code of what they have and attempted, then added edits to their question to include solutions offered by people that they tried.

Q:
> "I am working on a web application where I want the content to fill the height of the entire screen.
> 
> The page has a header, which contains a logo, and account information. This could be an arbitrary height. I want the content div to fill the rest of the page to the bottom.
> 
> I have a header div and a content div. At the moment I am using a table for the layout like so:
> 
> CSS and HTML

```
/*
Source - https://stackoverflow.com/q/90178
Posted by Vincent McNabb, modified by community. See post 'Timeline' for change history
Retrieved 2026-09-09, License - CC BY-SA 4.0
*/

#page {
  height: 100%;
  width: 100%
}

#tdcontent {
  height: 100%;
}

#content {
  overflow: auto;  /* or overflow: hidden; */
}
```
```
<!--
Source - https://stackoverflow.com/q/90178
Posted by Vincent McNabb, modified by community. See post 'Timeline' for change history
Retrieved 2026-09-09, License - CC BY-SA 4.0
-->

<table id="page">
  <tr>
    <td id="tdheader">
      <div id="header">...</div>
    </td>
  </tr>
  <tr>
    <td id="tdcontent">
      <div id="content">...</div>
    </td>
  </tr>
</table>
```
> "The entire height of the page is filled, and no scrolling is required.
> 
> For anything inside the content div, setting top: 0; will put it right underneath the header. Sometimes the content will be a real table, with its height set to 100%. Putting header inside content will not allow this to work.
> 
> Is there a way to achieve the same effect without using the table?
> 
> Update:
> 
> Elements inside the content div will have heights set to percentages as well. So something at 100% inside the div will fill it to the bottom. As will two elements at 50%.
> 
> Update 2:
>
> For instance, if the header takes up 20% of the screen's height, a table specified at 50% inside #content would take up 40% of the screen space. So far, wrapping the entire thing in a table is the only thing that works."

[Source Link](https://stackoverflow.com/q/90178)

This question from the user Vincent McNabb is a good example of what I believe is a smart question. They outlined precisely what they are going for, asked a proper question, and gave examples of what they've tried. Another thing I think enhances the question is that they edited their original question to include their attempts trying solutions offered by people trying to answer their question. 

## Which one worked?

<img width="300px" class="rounded float-start pe-4" src="../img/Smart Questions Reflection/smart_questions_reflections_header.png">

Now, while spin58's question may be "not-smart" and Vincent McNabb's question is "smart", but that doesn't matter if they get the answers they're looking for right?

Now, looking at the answers for spin58's questions:

A:
> "You have invalid HTML. You never close your `<p>` tags, and you start a col-sm div inside the first one before closing it, too. Also, `<p>` cannot go inside an `<img>` I'm pretty sure (you never close the img tags, they should self-close) Your last `</div>`s need several other closing tags for different tag types in it before it can be valid. I've reformatted your code to use proper indentation to make it more clear where your issues lie. I recommend using a proper IDE or development environment when writing code; whatever tool you are currently writing the code in is clearly not doing you any favors."

A:
> "'using the w-3 card option' What is that supposed to be? w-3 would be a 3% width Bootstrap class, but that' is not a default class. And in your HTML, you have w3-card, which is not a Bootstrap class either."

Then, the answer for Vincent McNabb's answers:

A:
> "There are two other answers briefly mentioning flexbox; however, that was more than two years ago, and they don't provide any examples. The specification for flexbox has definitely settled now.
> 
> Note: Though CSS Flexible Boxes Layout specification is at the Candidate Recommendation stage, not all browsers have implemented it. WebKit implementation must be prefixed with -webkit-; Internet Explorer implements an old version of the spec, prefixed with -ms-; Opera 12.10 implements the latest version of the spec, unprefixed. See the compatibility table on each property for an up-to-date compatibility status.
> 
> (taken from https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Flexible_boxes)
> 
> All major browsers and IE11+ support Flexbox. For IE 10 or older, you can use the FlexieJS shim.
> 
> To check current support you can also see here: http://caniuse.com/#feat=flexbox
> 
> Working example
> With flexbox you can easily switch between any of your rows or columns either having fixed dimensions, content-sized dimensions or remaining-space dimensions. In my example I have set the header to snap to its content (as per the OPs question), I've added a footer to show how to add a fixed-height region and then set the content area to fill up the remaining space.

```
/*
Source - https://stackoverflow.com/a/24979148
Posted by Pebbl, modified by community. See post 'Timeline' for change history
Retrieved 2026-09-09, License - CC BY-SA 4.0
*/

html,
body {
  height: 100%;
  margin: 0;
}

.box {
  display: flex;
  flex-flow: column;
  height: 100%;
}

.box .row {
  border: 1px dotted grey;
}

.box .row.header {
  flex: 0 1 auto;
  /* The above is shorthand for:
  flex-grow: 0,
  flex-shrink: 1,
  flex-basis: auto
  */
}

.box .row.content {
  flex: 1 1 auto;
}

.box .row.footer {
  flex: 0 1 40px;
}
<!--
```
```
Source - https://stackoverflow.com/a/24979148
Posted by Pebbl, modified by community. See post 'Timeline' for change history
Retrieved 2026-09-09, License - CC BY-SA 4.0

<!-- Obviously, you could use HTML5 tags like `header`, `footer` and `section` -->

<div class="box">
  <div class="row header">
    <p><b>header</b>
      <br />
      <br />(sized to content)</p>
  </div>
  <div class="row content">
    <p>
      <b>content</b>
      (fills remaining space)
    </p>
  </div>
  <div class="row footer">
    <p><b>footer</b> (fixed height)</p>
  </div>
</div>
```
> In the CSS above, the flex property shorthands the flex-grow, flex-shrink, and flex-basis properties to establish the flexibility of the flex items. Mozilla has a good introduction to the flexible boxes model."

I'd say the differences are like night and day. spin58 got very impassioned answers from people that look like they answered only to question what they were even doing. Meanwhile Vincent McNabb got so many answers, that someone else compiled the most resounding solution and gave examples on how to utilize that solution. They also linked resources to what they refer to, they link their sources where they get their information, and also even linked a different site that may help. 
Thus, you can see that asking smart questions is very important for programmers and developers. With a smart question, you get people compiling answers into one big answer with examples, as well as links to what they are referring to. People will be more willing to help and go out of their way to help you improve. Otherwise, you will people being passive-aggressive to you, commenting only to question your skills or perceived lack thereof.  