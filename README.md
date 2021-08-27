## Coding sample

Implement one round of the card game War using the API found at deckofcardsapi.com. Your game. should work like this:

  - User presses a “Start Game” button to start the game
  - Your program requests a new deck of cards from the API (player A)
    - https://deckofcardsapi.com/api/deck/new/
  - Your program requests a second new deck of cards from the API (player B)
    - https://deckofcardsapi.com/api/deck/new/
  - Your program draws one card from each deck and displays the cards on screen
    - https://deckofcardsapi.com/api/deck/<<deck_id>>/draw/?count=1
  - Whichever player has the higher card gets a point (Aces are high)
  - The point total for each player is displayed
  - User presses a “Draw Cards” button to continue the game
  - Repeat steps 4 through 7 until no cards remain
  - Display which player won

In this simplified version, if there is a tie (both players draw identical cards), neither player gets a point. Language and framework. Write your code using PHP, Python, Ruby or JavaScript. (If you want to use another language, ask first.)

You may use a framework or library (Flask, Django, Rails, React, jQuery, etc.) but are not required to do so.


### Summary of Required Elements
  - Buttons Needed
    - Start Game, Draw Cards
  - Display
    - Show cards on screen when they are drawn
    - Show point totals for both players, updated after each round
    - Show the winner


### Time limit

- Don’t spend more than two hours on this. If you get it done in less time, that’s fine, too. If you don’t finish in two hours, send what you have.


### Scope

  - Do not spend time making it fancy (i.e. no animations or special effects).
  - Do not write any unit, integration, acceptance or other types of tests.


### Submitting your project

- Create a private GitHub repository for your project. When you are done, invite GitHub user paulschreiber as a collaborator and send Paul an email.


### Evaluation

- In addition to correctness, we want to see (a) clean, readable, well-documented code that’s idiomatic to your language and (b) good commit messages.


## Plan

- Start game via "Start Game" button
- When game is started, fetch a new deck for each player
-
