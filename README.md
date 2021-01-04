![code differently](https://user-images.githubusercontent.com/54545904/91590200-f82ec600-e928-11ea-9433-eea450388abf.png)

# Tic-Tac-Toe

Make the game Tic-Tac-Toe using HTML, CSS, and JavaScript!

## Instructions

1. Fork and clone this repository.
2. Fulfill the requirements below.

## Requirements

Your goal is to build out a working version of Tic-Tac-Toe.

YOu will build this game in two phases. Each phase is defined below.

### Phase 1: Player-scored Version

Build out a 3x3 grid with clickable squares. When a user clicks on a square, it should turn orange or blue (alternating with each click). Once a square has been
clicked, a user should not be able to click it again and change it's color.
Below your 3x3 grid, you should have a 'reset' button that will reset the game.

**Bonus requirements:**

* Have a message somewhere in your UI to show who the current player is (i.e.
    `orange's turn` or `blue's turn`)

### Phase 2: Dumbly-scored Version

The goal of this phase is to make it so that players don't have to manually
score the game. Instead, you're going to write some code that will check the
board with every turn:

* If a player has won, display a message with which player won the game (i.e. orange or blue)
* If all the squares are filled in and no player has won yet, display a message saying it's a tie
* In both cases, the users should be able to reset the game

In games where there are a limited number of winning combinations, a great
first-step to auto-calculating the winner is to hold those winning combinations
in some format (maybe an array) and check the current game against those winning
combinations. If one of the winning combinations matches the gameboard, then you
know a player has won!

However, doing so requires modeling the current state of the gameboard in your
code. So, in addition to updating your UI whenever a player makes a move, you'll
also have to update some representation of the gameboard in your game code.