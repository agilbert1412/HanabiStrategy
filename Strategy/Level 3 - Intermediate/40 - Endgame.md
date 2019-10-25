# The Endgame

<br />

## Technique

Hanabi Endgames are very hard to figure out. There is no known algorithm (yet?) that allow you to calculate the endgame, other than literally brute forcing the possibilities (or use an algorithm equivalent or worse than brute force).

It would be easy to refer to the endgame as the portion of the game that happens after the deck is empty, but that's not optimal. Endgame decisions start much before that, specifically in trying to optimize who will pick up the last cards.

Usually, the endgame is defined as the portion of the game where there are so few remaining cards, that players can brue force the ending and make mathematically supported decision and gambles depending on the full range of options. Of course, unlike the early game, this separation may happen at a different turn, depending on the player, because some might be better at calculating it than others.

Endgame changes in stategy are not numerous, and they basically all gravitate around one simple principle: Get the right people to pick up the cards.

This means that, when in the endgame, even if you have something to play, you can't play it until you reach a stage where you should pick up a new card. This might mean giving low-value clues, or even zero-value clues, to delay picking up cards.

Discarding is allowed in the endgame, but only for a player who needs to pick up a card, but has nothing to play. Playing is always preferred to discarding if possible

If you give low-value clues in the endgame, you should make them obvious. One of the hard parts of the endgame is giving tempo clues without triggering unwanted finesse plays. This is especially problematic if some players haven't realised that we're in the endgame now.

When in the end game, context is extremely important to make the distinction between finesse and tempo clue.

For example, you are missing the green 3, 4 and 5. You have the 5 (known), you see the 4 in the third player's hand, but not the 3. You know it is in the deck, because of whatever reason. You decide to pre emptively clue the 4, so that the player next to you can try to pick up the 3, because once they do, you will not get a chance to clue the 4. It would be a tempo clue, to make sure all 3 cards are playable when you find the #3. In non-endgame situations, cluing that 4 would trigger a finesse on the other player. But in the endgame, this clue is crucial, which means you cannot assume it's a finesse.

Usually, in that case, if you have enough clues, the other player can assume that if he had the 3, you'd clue the 3, he's clue the 4, the other guy would stall, and everyoe ould play one turn later. But if you are low on clues, that's not an option. Then, if you can, you should clue the number 4, so that there is no risk of the card being played thinking it's a 3, but even that's not garanteed. If the other guy sees you gave the number when the color would have worked, he can figure out it's not a finesse. But if the color wouldn't have worked, or if you give the color because the number doesn't work, then it can get extremely hard to tell.

Basically, there is no set of conventions that is garanteed to get you out of this mess. If you are low on clues, and both color and number clues on the 4 are ambiguous, or even impossible, it's impossible to tell if it's tempo or finesse, because in both cases you'd be doing the same thing.

As the second player, if it's ambiguous, brute force it. What score do you finish with if you misplay right now, if you play the 3 correctly right now, and if you wait. Choose the mathematically optimal option. It won't always work, but it will give you the best results on average

<br />

## Navigation

* [Level 3 - Intermediate Strategies](https://github.com/agilbert1412/HanabiStrategy/blob/master/Strategy/Level%203%20-%20Intermediate/Level%203%20-%20Intermediate.md)

* [Previous: Trash Push](https://github.com/agilbert1412/HanabiStrategy/blob/master/Strategy/Level%203%20-%20Intermediate/39%20-%20Trash%20Push.md)
	* If a clue only touches known trash cards, and one of them was the chop, you should play your oldest unclued card (which just became your chop).

* [Next: Occupied Play Clue](https://github.com/agilbert1412/HanabiStrategy/blob/master/Strategy/Level%203%20-%20Intermediate/41%20-%20Occupied%20Play%20Clue.md)
	* Save clues are bad for efficiency and for tempo, and should only be given when they are needed or there is nothing better to do. If you do have something better to do, but choose to give a clue that looks like an unneeded save clue, it means it isn't one and is actually a play clue.