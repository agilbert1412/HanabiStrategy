# Layers

<br />

## Technique

Prompts, Finesses and Bluffs are part of a category of moves called promises. When you execute one of those moves, you promise the table that the missing cards are somewhere and playable right now (In the case of the bluff, you lie about it, but you promised it nonetheless). Then, everybody is able to instantly confirm that (they see the card), except one person (the one who has it). This person has to trust you about it. You promised them that a needed card was in their hand and playable.

Now, as described before, they know what to play to find it. In the case of the prompt, the newest clued card that could be it. In the case of a finesse or bluff, the newest unclued card.

If it is a bluff, your promise is a lie, and they will realize it instantly. But in a case where a bluff is impossible, the card they play might still not be the desired card, but another unrelated playable card. Since the player in bluff seat did not attempt to play, it means they actually saw the card. They are implicitly confirming the promise, so it is not a bluff. In this case, you should move on the the next card that is the most likely to be it.

For a finesse, it would be whatever was the second newest unclued card at the time that the clue was given. It is obvious that the clue was not promising a card you hadn't picked up yet, so anything newly drawn after the clue is ignored when figuring out the next most likely card.

A promis does NOT promise the position of the card. It only promises that "If you trust me and try your best to play it, you will find it before making a mistake".

This is called a Layered Prompt or Layered Finesse. The desired card is under a few layers of playable cards, and you have to play them one at a time to find the one you want.

The Technique [14 - Prompt Finesse](https://github.com/agilbert1412/HanabiStrategy/blob/master/Strategy/Level%202%20-%20Beginner/14%20-%20Prompt%20Finesse.md) is a type of layered move where the actual finesse is layered behind potential prompted cards that are all playable.

Promises that end up being lies, like the bluff, are only allowed to be performed on the player that is playing right after you. It is the only person you can lie to. In the same logic, the only person allowed to lie to you is the person playing right before you.

Therefore, if a player not allowed to lie to you promises you that you have a card, trust them.

<br />

## Examples

<p align="center">
    <img src="images/<21_LayersExample.png" />
</p>

SedNegi tells Zamiel about one 3 (yellow3)

Zamiel is told he has a playable three. Of course, since no three is playable, he realises that the related 1 and 2 are also playable. Those two cards are promised, but Zamiel doesn't know their color yet. Dan sees that the 3 is yellow3, and sees the yellow1 in a playable position, he is promised a yellow2. Zamiel sees many cards as potentially playable, but there is no 1 playable right now to go with his three. He is promised a 1 that goes with the 3.

* Dan waits, because he sees the y1
* Zamiel plays purple1. He can't know if the 3 is purple3, but he doesn't see a purple2 anywhere, so he is promised either the purple2 (and clue is purple3), or another 1 and the clue is another 3
* Negi does whatever, he gave the clue and is only watching it unfold. He can do anything he deems useful.
* Dan does not play the yellow2, since the yellow1 is not played yet.
* Zamiel plays the yellow1. He still doesn't know the color of the 3. He knows that if it is yellow, Dan will play yellow2 now, and otherwise, that means he still has to play purple2 or another 1.
* Negi does whatever
* Dan plays yellow2, since he was promised it.
* Zamiel sees that Dan has played, but doesn't know if he will play again, since his next cards are playable too. He cannot know what Dan was trying to play, just that he was trying to play something. He waits one turn to confirm if Dan will keep looking for a card. If Dan plays nothing else, then Zamiel knows he was looking for yellow2, and therefore his clued card is yellow3.
* Negi does whatever
* Dan does not play rainbow1. He is not promised anything anymore, since the 3 is now playable.
* Zamiel sees nothing has been played, understands nobody else is promised anything, his 3 is now playable. He plays yellow3
* The clue is over.

<br />

## Navigation

* [Level 2 - Beginner Strategies](https://github.com/agilbert1412/HanabiStrategy/blob/master/Strategy/Level%202%20-%20Beginner/Level%202%20-%20Beginner.md)

* [Previous: Priority Plays](https://github.com/agilbert1412/HanabiStrategy/blob/master/Strategy/Level%202%20-%20Beginner/20%20-%20Priority%20Plays.md)
	* If someone seems to deviate from priority, it is signal, like a play clue, on the card(s) needed for the move to be correct priority. Any card you don't see, you have.

* [Next: 5 Chop Move](https://github.com/agilbert1412/HanabiStrategy/blob/master/Strategy/Level%202%20-%20Beginner/22%20-%205%20Chop%20Move.md)
	* If you receive "5" on a card exactly one slot away from chop, it is a save clue on both the 5 and the current chop.