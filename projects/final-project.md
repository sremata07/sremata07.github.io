---
layout: project
type: project
image: img/computer_mail.png
title: "UH ITS Email Helper"
date: 2026
published: true
labels:
  - Prisma 
  - PostGreSQL 
  - Next.js 
  - React  
  - Vercel
summary: "A web app designed to help UH ITS Students create, share, and save email templates."
---

## Project overview
This aim of this project was to help UH ITS student workers save time by creating a web app designed to share, create, and save email templates. This way, they will be able to save time and also share their templates with other ITS student workers in order to create a large, collaborative database that will tackle their every need when it comes to sending emails. There are also other small functionalities that were created to make the overall app more complete such as tags for emails, user profiles, template comments, and a templates use count. 

## My contributions
This project was managed in a team of 4, I handled the following:
- Creating and styling the initial landing page
    - Was later restyled by a different group member, Chase
- Restricting access to non-logged in users
    - If users were not logged in, they would either be redirected back to landing page, sign-in page, or to a restricted access page
- Worked on the tag functions
    - Tag suggestion when creating and/or searching tags
    - Clickable tags in search page that search for similar tags
    - Misc. QoL relating to tags
- Worked on the templates view page
    - Added time stamps when viewing templates page

Below are some examples of what I coded:
```
  const tagSearchEvent = (e: React.MouseEvent, tag: string) => {
    e.stopPropagation();
    if (onTagClick) onTagClick(tag);
  };
```
This was an event helper I created to be able to implement the ability to click the tags and have it automatically search it when viewing the templates in the search page, it was used here:
```
           {template.tags.map((tag) => (
              <button
                key={tag}
                className="badge fw-normal tag-badge"
                style={{ flexShrink: 0 }}
                onClick={(e) => tagSearchEvent(e, tag)}
              >
                {tag}
              </button>
```
Turning the tags into a button, then intiiating the above event helper which then leads to here:
```
  const tagSearchEvent = (tag: string) => {
    setSearch(tag);
    setPage(1);
  };
```
Where the current search becomes the clicked tag, thus allowing you click on the tags and search relating tags.
I found this to be quite difficult, as I spent a lot of time looking into custom React hooks and figuring out where I needed to slot things in into other's created frameworks to make sure my code works without breaking other people's code. I remember being very happy when everything worked, and I'm sure if I spent more time on this I could make it better but that's for the future.

## What I learned
From this project I learned a lot of time management, and I learned a lot about how difficult it can be to work on a coding project with other people. Making your implementations work without breaking other people's code is a little stressful, and I remember being very confused when looking through merge conflicts trying to figure out what needed to stay and what didn't. Overall, if I had one take away, it's that now I understand the need for comments on code. Because not only do I forget sometimes what I was trying to accomplish, but it's even harder to figure out what something does when I never wrote it. In the future, I will make sure to leave detailed comments as if someone is going to go through my code.

## Check out the app:
<p> 
<a href="https://uh-its-email-helper.vercel.app/">Deployed app on Vercel<a> <br>
<a href="https://github.com/ICS314-Group-4/Group-4-Final-Project">Source code<a> <br>
<a href="https://ics314-group-4.github.io/">Group project page<a>
<p>
