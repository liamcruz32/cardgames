# Clover

## Overview
A point-trick game in the Jass family where players play in two-person partnerships with the person sitting across from them, and attempt to make the most points by making melds and collecting cards in trick.

## The Deck and Deal
Jass games are part of the Ace-Ten family of trick taking games, and share the card scoring scheme as those. They are unique in that the Trump suit changes ranks and points--with the Jack and Nine becoming the two highest cards.

| Trump Rank | Point value | Off Suit Rank |
|:----------:|:-----------:|:-------------:|
|     J      |     20      |               |
|     9      |     14      |               |
|     A      |     11      |       A       |
|    10      |     10      |      10       |
|     K      |      4      |       K       |
|     Q      |      3      |       Q       |
|            |      2      |       J       |
|            |      0      |       9       |
|     8      |      0      |       8       |
|     7      |      0      |       7       |

There are 152 total points in the deck. The last trick is worth -2 points, bringing the total points in a hand to 150.

  - In No-Trump games, there is no high point jacks or 9's, and 8's are instead worth 8pts each. This keeps the total score in the deck at 150
 
Deal eight cards to each player, with the final card dealt face up to the dealer to determine trump for the first round of bidding.

## Bidding
Starting to the dealer's left, each player decides whether his team passes or plays. If they choose to play, they accept the trump suit and aim to take more points in tricks than their opponents. This is known as 'declaring'.

If no players accept the trump suit in the first round of bidding, the dealer picks up the card to their hand, and the bidding goes around the table again, this time with the option to choose your own trump suit. A player choose to play a no-trump game, but a no-trump game may be outbid by a player who chooses a trump suit.

If no players play after the second round of bidding, the hand is thrown in and the same dealer deals again.

When a player accepts the bid and becomes the declarer, their partner must pass them one card. The declarer adds the card to their hand and then passes one card back.

## Melding
There are two ways to earn meld points in a round: shown in the hand before the first trick, and collected as combinations within tricks. **Both get added to your meld score at the end of the hand**. The melds values are as follows:

|          Meld          |   Score   |
|:----------------------:|:---------:|
| Set of 4 Jacks         |    200    |
| Set of 4 A/K/Q         |    100    |
| Run of 5               |    100    | 
| Run of 4               |     50    |
| Run of 3               |     20    |
| Set of 3 (tricks only) |     20    |
| K+Q of trump ("Bell")  |     20    |

**Runs must be in the same suit when declared in the hand, but may be mixed suits when won in tricks.**

Cards may not be used in multiple melds with the exception of the Bell. (A run of J♠-Q♠-K♠ with "♠" as trumps is 20+20 points)


## Play
The Declarer leads the first trick by placing a card face up in the center of the table, but first may declare any melds in their hand by laying them face up on the table.

Each player in turn must play a card matching the suit of the card led if possible. If they hold no cards of the suit led, they may play any card. They too may declare melds by laying them face up on the table.

After the first trick, players may take their tricks into their hands, or keep them on the table depending on preference. There is no difference in scoring or in play other than the accessibility of the information.

The trick is won by the player with the highest card in the suit led, or the highest card of the trump suit if any were played. That player collects the trick into their score pile and leads to the next trick.

Teams may also score melds by winning combinations of cards in tricks. For example, a trick containing the cards [J♣-8♣-10♥-9♦] scores 50 points for a run of 4. Or [Q♣-K♣-A♣-10♠] would be worth 40 points (20 for the run of 3, 20 for the Bell)

## Scoring
The score should be taken on 2 lines for each partnership, tracking meld points and trick points separately.


If the declaring team takes the most trick points, they make their bid and both teams get to keep their trick points in the score.

Whoever scores the most meld points in a hand gets to keep their meld score, the other player must cross it out and may not add it to their final score.

  - NOTE: If during the first trick, you do not declare your melds, you do not get to score them here, even if you would have made more points in melds than the opponent. You also cannot score them if you 'set' the declaring team.

If the declaring team does not take more points in tricks than the opposing team, they have been 'set' and all points they would earn in tricks and melds go to the opposing team.

Finally, the last digit of each score is scratched off, and the first part of the number becomes the total to add for the team's game score. For example, a team who scores 127 points in tricks will score 12 points for their team.

With bold scores symbolizing the declaring team:

Team 1
  * melds  |_~~7■~~_|_12■_ Total: 12
  * tricks | **12■**|__**7■**(set)
    
Team 2
  * melds  |_14■_|_4■_ Total: (14+2)+(4+7+12+7 from set)= 46
  * tricks | 2■    7■

* Game is played either 8 or 12 rounds depending on the desired length of game
