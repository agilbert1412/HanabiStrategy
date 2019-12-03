# Lines

<br />

## Technique

If anyone has ever heard of decision trees and algorithms such as minimax, this technique, which is more of a way of thinking, will be obvious to you.

Every time a player does anything, they have a finite set of possible actions (4-5 discard actions, 4-5 play actions, up to 32 clue actions), and they have to choose one. Some are better than others by a large difference, and some are pretty close. Most importantly, all those actions will create a slightly different game state for the next player, affecting their own set of possible actions. That is a decision tree with multiple players.

Once you choose one of your 40+ branches, all other branches are closed off permanently. The set of remaining actions is also a tree, it is the sub-tree of your move.

Unlike a versus game, in which you must choose the branch that gives the worst sub-tree to your opponent, in a cooperative game, all players try to generate the best possible sub trees for each other.

For example, in chess, you don't try to generate a sub tree with one very good branch for you, because you know your opponent will never choose this branch. You try to generate one with as few bad branchs as possible, and the "best" worst-branch possible.

In Hanabi, you can expect your team mate to look for good lines too, so choosing to give them a sub tree with one very good branch is much better than with many mediocre ones.

One path travelling the tree from beginning to end by choosing a branch on each step is called a line. Choosing a branch is called "initiating" a line. You must try to initiate the best possible line on each turn. You look to the next few turns (as far as you can reasonably calculate within a reasonable time), and try to make sure every player gets at least one good branch to choose, including them thinking in the future, etc.

PS: The expected branches should, as much as possible, be Randomness-independant. You don't calculate "this move is great if A picks up a specific card, and shit otherwise, so that's one good line, I'll go for it".

You try to get value regardless of randomness, "stable value", and if you can't, you get as stable as possible, which means the action that has the highest chance of not turning into garbage.

This entire Technique is only about predicting rational actions and taking them into account, not predicting the order of the deck. That's a topic for another day.

<br />

## Navigation

* [Level 3 - Intermediate Strategies](https://github.com/agilbert1412/HanabiStrategy/blob/master/Strategy/Level%203%20-%20Intermediate/Level%203%20-%20Intermediate.md)

* [Previous: Lie Component](https://github.com/agilbert1412/HanabiStrategy/blob/master/Strategy/Level%203%20-%20Intermediate/53%20-%20Lie%20Component.md)
	* You can do a soft lie, which is doing a finesse when the expected card is not in a playable position, if you know for sure you can fix before it turns into a mistake and it brings some value through the cards that get played before the fix.

* [Next: High Value Cards](https://github.com/agilbert1412/HanabiStrategy/blob/master/Strategy/Level%203%20-%20Intermediate/55%20-%20High%20Value%20Cards.md)
	* Critical cards and playable cards should be treated as very important, and not discarded, while almost-playable cards and 3s should not be carelessly thrown away unless necessary.