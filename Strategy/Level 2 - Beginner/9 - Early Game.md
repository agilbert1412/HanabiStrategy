# Early Game

<br />

## Technique

As mentioned in [8 - Discard Principle](https://github.com/agilbert1412/HanabiStrategy/blob/master/Strategy/Level%201%20-%20First%20Principles/8%20-%20Discard%20Principle.md), in Hanabi we are allowed very few discards to be able to get the maximum score. This means that, when possible, we should delay discarding to do something better.

There are two types of discard. Trash discard, and semi-critical discards (Here, we ignore the third type, Critical discards, because we assume any critical discard is the result of a mistake, not an expected event in the normal course of the game). A trash discard is when a player discards a card that has already been played, and had therefore no value whatsoever. A semi-critical discard is when you discard a card that could have been played later on, but at least it's not the last copy of that card.

As a game tends to progress, the likelyhood of making trash discards goes up (as more cards are played), and the likelyhood of making semi-critical discards goes down proportionally. In a perfect game, only trash discards would be made, because the players manage to play the first copy of each card that they encounter.

This is the main reason why discarding should always be delayed when possible. It is better to give low-value clues than to discard, but it is not better to give zero-value clues than to discard.

The early game is the game phase that happens before the very first blind discard. We start with 8 clues and a lot of new cards, and we have to play as many of those as possible (without making mistakes) before the first discard, so that our discards start with the highest possible likelyhood of being trash discards.

There are several differences between how you should play in the early game vs the midgame, but we only focus on one for this strategy.

During the early game, you can give save clues for 5s that are not on the chop. This is called a 5 Stall, and should always be given by number, not color, so that it is easy to identify. We assume that in the vast majority of games, no 5 will become playable during the early game, so the 5 stall clues cannot be confused with 5 play clues.

This kind of clue works on the idea that you will need to save this 5 eventually, because any 5 that is drawn in the early game is more likely to reach the chop before becoming playable, and this way we save it pre-emptively, while delaying our first discards.

Of course, if you can give actual play clues or save clues on the chop, or play a card, you should prioritize doing that over 5 stalls.

The early game ends when the first blind discard happens (discarding a card that could be semi-critical). Misplays and known discards don't end the early game.

You should only end the early game when you either run out of clues, or there is nothing of value left to clue.

<br />

## Navigation

* [Level 2 - Beginner Strategies](https://github.com/agilbert1412/HanabiStrategy/blob/master/Strategy/Level%202%20-%20Beginner/Level%202%20-%20Beginner.md)

* [Go back to Level 1 - First Principles](https://github.com/agilbert1412/HanabiStrategy/blob/master/Strategy/Level%201%20-%20First%20Principles/Level%201%20-%20First%20Principles.md)