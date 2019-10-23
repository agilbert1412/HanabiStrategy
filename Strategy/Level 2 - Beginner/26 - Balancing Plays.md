# Balancing Plays

<br />

## Technique

Most of the previous techniques were either ways to get cards played or saved with few or no clues at all, because clues are a limited resource.

If you understand all the previous Techniques relatively well, you will win some games, but not all games, even though your clue efficiency will usually be higher than the minimum required. This is because of Tempo.
Tempo is the measure of how efficiently the team is using time, which in Hanabi is represented in number of Turns. Since players can't skip turns, every turn either removes a card from the deck, or a clue from the limited stock. All those actions bring closer the end of the game and the clock can't be turned back. That's the entropy of Hanabi.
In other words, for a player to do a second action, all other players must take one action themselves. If those actions are useless, it cost n (n being the number of players) turns of tempo to do only one good move. Improving tempo is improving the number of useful (score-wise) actions taken per turn around the table, on average, and this is also why we try to choose THE most useful action every turn, as opposed to just an okay action.

Pretty much every deck shuffle is winnable, but some decks are much easier than others when it comes to Tempo. To reach the next level, you must optimize your tempo.

One of the biggest things, when it comes to tempo, is the fact that one player having more cards to play than the others is bad. For each card a player needs to play, every other player needs to do something too, because you can't skip turns. The game's entropy means that you move closer to the end faster than you are progressing. For example, if only one player has playable cards, then for each card played, n-1 clues or cards are used up (discards).

Of course, if a playable card is only visible in that player's hand, it would be a worse waste of time to not do anything about it than to clue it. But for all the cases where you see two copies, you should prioritize getting the one that is in a less-active player's hand, to balance the plays around the table, and improve tempo.

By less active, I mean that he has one of the following, in order from most important criteria to least
1. fewer clued playable cards
2. fewer unclued playable cards (excluding the one you are about to maybe clue)
3. fewer clued unplayable (saved) cards
4. fewer unclued unplayable (but maybe playable later) cards
5. unclued unplayable (but maybe playable later) cards are closest to their chop

Sometimes you will need to choose between a more clue-efficient play (ex: finesse) or a more tempo efficient play (getting the card in a less active player's hand). There is no general correct answer to that.

Each specific case must be evaluated to the best of your capacity. How efficient is the clue-efficient play? (2 cards for one clue? 3? more?). How unbalanced will the hands be if you choose to prioritize clues (is it 4-0, or 3-2?)? Is your team currently in need of clues, or in need of tempo? Are there many critical cards close to chops, do you need the extra clues to save them?

<br />

## Navigation

* [Level 2 - Beginner Strategies](https://github.com/agilbert1412/HanabiStrategy/blob/master/Strategy/Level%202%20-%20Beginner/Level%202%20-%20Beginner.md)

* [Previous: Gentleman's Discard](https://github.com/agilbert1412/HanabiStrategy/blob/master/Strategy/Level%202%20-%20Beginner/25%20-%20Gentleman%20Discard.md)
	* If you are about to play a card, but see it playable (findable) somewhere else (ex: finesse position), you can discard it instead to send a message. Only do it if it brings some value.

* [Next: Minimum Clue Value](https://github.com/agilbert1412/HanabiStrategy/blob/master/Strategy/Level%202%20-%20Beginner/27%20-%20Minimum%20Clue%20Value.md)
	* Every clue should get at least one new card to be played now or later, except specific situations where you are forced to give a clue and nothing good is available