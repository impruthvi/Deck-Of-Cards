# OOP Exercise
## Introduction

Your goal in this exercise is to implement two classes, Card  and Deck .

## Specifications

### Card 

1.Each instance of Card  should have a suit ("Hearts", "Diamonds", "Clubs", or "Spades").

2.Each instance of Card  should have a value ("A", "2", "3", "4", "5", "6", "7", "8", "9", "10", "J", "Q", "K").

3.Card 's  __repr__   method should return the card's value and suit (e.g. "A of Clubs", "J of Diamonds", etc.)


### Deck 


1.Each instance of Deck  should have a cards attribute with all 52 possible instances of Card .

2.Deck  should have an instance method called count  which returns a count of how many cards remain in the deck.

3.Deck 's __repr__  method should return information on how many cards are in the deck (e.g. "Deck of 52 cards", "Deck of 12 cards", etc.)

4.Deck  should have an instance method called _deal  which accepts a number and removes at most that many cards from the deck (it may need to remove fewer if you request more cards than are currently in the deck!). If there are no cards left, this method should return a ValueError  with the message "All cards have been dealt".

5.Deck  should have an instance method called shuffle  which will shuffle a full deck of cards. If there are cards missing from the deck, this method should return a ValueError  with the message "Only full decks can be shuffled".  shuffle should return the shuffled deck.

6.Deck  should have an instance method called deal_card  which uses the _deal  method to deal a single card from the deck and return that single card.

7.Deck  should have an instance method called deal_hand  which accepts a number and uses the _deal  method to deal a list of cards from the deck and return that list of cards.
