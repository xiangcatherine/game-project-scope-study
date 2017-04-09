# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](https://www.mountaingoatsoftware.com/agile/user-stories)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to the following in this file via a pull request:

-   A wireframe of what your game project will look like.
![Catherine's wireframe] (http://imgur.com/a/KSKui)

-   The data structure you plan to use.
Given the JS representation of the game board (as drawn in the next question),
I plan on using arrays for the data structure.

-   How you will take the markup of the game board and represent it in JS
![HTML and JS representation] (http://imgur.com/a/JT4tF)
As pictured in the link, I will represent the game board using an object, which
contains 3 arrays.
const board = {
  top:[l, c, r],
  mid:[l, c, r],
  bottom:[l, c, r]
}
This way each grid in the game board has a specific reference, e.g.:
board.top[0], board.top[1], board.mid[0] etc.

-   How you plan to approach this project.
I plan to start with HTML (based on my wireframe), since this is needed for
JS and CSS. Once I have the HTML structure I want, I will start the JS portion,
which I'm sure will require me to revisit the HTML frequently (class and ids etc.).
Once HTML and JS are functioning, I'll work on CSS styling to make it look more
sleek and presentable.

-   4-8 user stories for your game project.
1) As a non-registered user, I can sign up for an account.
2) As a registered user, I can keep track of my game-play history.
3) As a user, I can play tic tac toe.
4) As a user, after a game I can replay the game.
5) As a user, I can choose if I want to play as circle or cross.

-   How you plan to keep your code modular.
![game modular structure]http://imgur.com/a/y9EOV
I plan on organizing my code based on the diagram attached, so that each bit
of code carries a specific function.

-   What creative spin will you add to your project?
As seen in my wireframe, I plan on having the tic tac toe grid the space where
users sign in/ sign up.

-   How will you use version control to backup / track your project?
I plan on sharing my work through a git repostory on Github — making clear
commits frequently will help keep track of my progress as well as backing
everything up.

-   Do you plan to attempt any of the bonuses?
No, I plan to focus on fulfilling the requirements and building a functioning
game. When I have that done (and hopefully done well), I will consider attempting
the bonuses.

You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur](http://imgur.com/).
