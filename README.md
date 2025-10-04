# Blackjack (Python)

**Author:** Dan Quackenbush  
**Course:** CISS 111 – Program Project  

This is a simple text-based implementation of the Blackjack card game in Python.  
It demonstrates object-oriented programming concepts, including **classes**, **inheritance**, and **encapsulation**.

---

## Description
This program simulates a game of Blackjack between a **Player** and a **Dealer**:
The game even refrences real cards in a deck to mimic reality, so it isn't just a random number generator!

- A `Deck` of cards is created and shuffled.
- Both the Player and Dealer are dealt two cards.
- The Player decides whether to "hit" (take another card) or "stand" (end their turn).
- The Dealer automatically draws cards until reaching 17 or higher.
- The winner is determined based on the Blackjack rules.

### Classes
- **`Player`**  
  Represents a player’s hand. Handles hitting, scoring, and checking for Blackjack.

- **`Dealer`**  
  Shows only one card at first and then reveals the full hand after drawing until 17+ points.

- **`Blackjack`**  
  Manages the deck, initializes the game, and controls the flow of play.

---

##  How to Run
**NOTE** You must use a machine with PYTHON installed
- Place all dowloads in the same folder and navigate to that folder via windows command prompt
- use command: python blackjack.py


   
