---
layout: project
type: project
image: img/Checker Game/checkers_thumbnail.jpg
title: "Checker Game"
date: 2023
published: true
labels:
  - Game Development
  - C#
summary: "I helped one of my classmates code a checker game for their class."
---

<img class="img-fluid" src="../img/Checker Game/checkers_example.jpg">

In high school one of my classmates was in some sort of coding class, and their final assignment was to create a program. They decided to make a game that simulates chess. 

For this I was just an assistant as I was not in class, and while I do not have any of the original code, I certainly remember the issues we encountered. The first was creating the chess board, as the way we were doing it was to print out the entire chess board with symbols representing the pieces, and getting the board to be formatted nicely was a challenge. Another big challenge was making the program run well in the in-web development environment, as every move would reprint the chess board with the moved piece. Because of this the game was ultimately simplified to checkers. 

Overall, I think that these kinds of in-web development environments are a fantastic tool for learning intiially, but for bigger projects they definitely start to fall flat. Having to print the page every time there was a move made the program run incredibly slow, and today I think we would definitely do something differently. 

To kind of help you visualize what the board looked like, I recreated it below:
```
+---+---+---+---+---+---+---+---+
|   | X |   | X |   | X |   | X |
+---+---+---+---+---+---+---+---+
| X |   | X |   | X |   | X |   |
+---+---+---+---+---+---+---+---+
|   | X |   | X |   | X |   | X |
+---+---+---+---+---+---+---+---+
|   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+
|   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+
| O |   | O |   | O |   | O |   |
+---+---+---+---+---+---+---+---+
|   | O |   | O |   | O |   | O |
+---+---+---+---+---+---+---+---+
| O |   | O |   | O |   | O |   |
+---+---+---+---+---+---+---+---+
```