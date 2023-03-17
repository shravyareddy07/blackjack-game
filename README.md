# blackjack-game

This is a simple implementation of the classic game Blackjack (also known as 21) in JavaScript. The game is played by drawing cards and trying to get a hand that totals as close to 21 as possible without going over. The player starts with two cards and can choose to draw additional cards until they are satisfied with their hand or they go over 21 and lose the game.

***usage:***
This will deal the initial two cards to the player and display them on the screen. The player can then choose to draw additional cards by clicking the "New Card" button. The game will continue until the player either decides to stop drawing cards or goes over 21.

***
Getting Started
---
The game uses a simple card drawing function (getRandomCard()) to generate random card values between 1 and 11. Face cards (Jack, Queen, King) are worth 10, and an Ace is worth 11 unless it would cause the player to go over 21, in which case it is worth 1.
The game keeps track of the player's current hand total (sum) and checks it against the winning condition of 21.
The game also keeps track of whether the player has "Blackjack" (an initial hand of two cards that totals exactly 21) or if they are still "alive" (i.e., have not gone over 21). These variables are used to determine when the game should end.
The game displays the player's cards, their current hand total, and a message indicating whether they can draw another card or whether they have won or lost the game. The message is updated after each card draw or after the player decides to stop drawing cards.
The game is designed to be simple and is not optimized for performance or advanced gameplay mechanics.
