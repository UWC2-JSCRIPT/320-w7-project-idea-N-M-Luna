
# Plans for the Memory Card Game app

## Elevator pitch

To play the **Memory** card game, a deck of cards is spread out and laid face down. The player (or players) take turns in flipping two cards face up. The goal is to find the matching pairs of cards. This game is also known as *Concentration, Matching Pairs, Match Match*, or *Match Up*.

Here is the [Wikipedia article](https://en.wikipedia.org/wiki/Concentration_(card_game)) on this game.

Last year, I implemented a 1-player version of this game using vanilla HTML, CSS, and JS. Here is my [GH repo](https://github.com/N-M-Luna/memory-card-game) and here is the [single-page app](https://n-m-luna.github.io/memory-card-game/).

For my final project, I'd like to re-make this app using React; or *reactify my app*, if you will.

## Features (with wireframes)

> This is from the readme file of the original project.

The game starts by shuffling and dealing a deck of 16 card (8 pairs of identical cards) face-down on the game board.

<img src="img/screenshot1.png" alt="screenshot" title="Screenshot of the beginning of the game" width="50%" /> 

> Beginning of game

In each turn, the player flips two cards. If they match, the player has solved the pair of cards and they remain facing up. If the cards do not match, they get flipped over again.

https://user-images.githubusercontent.com/1752105/188282009-b124bf38-0c62-4725-b406-e4e9c7df6fae.mov

> Game play

The game ends when all the cards have been solved.

<img src="img/screenshot5.png" alt="screenshot" width="50%">

> End of game

In the top left corner, there is a settings button that opens a **deck menu**. This allows the player to change the deck. *The deck library consists of six decks with the following themes: food, camping, animals, science, household, and tech.*

<img src="img/screenshot9.png" alt="screenshot" width="50%">

> Deck menu

In the top right coner, there is a help button that opens a **help screen** with the rules of the game.

<img src="img/screenshot10.png" alt="screenshot" width="50%">

> Game rules


### Nice-to-have features

If my app can do everything desribed in the previous section (before the project is due), I would like to implement the following features.

* User can change levels. 
* Browser remembers highest score. 
* User can sign in to keep a record of their highest score.

## Dependencies

Using no external npm modules. If authentication is being implemented, will use firebase.

## Game plan

TBD