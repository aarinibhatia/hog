# hog
A simulator and multiple strategies for the dice game Hog.

In Hog, two players alternate turns trying to be the first to end a turn with at least 100 total points. 
On each turn, the current player chooses some number of dice to roll, up to 10. 
That player's score for the turn is the sum of the dice outcomes.

There are also some additional special rules:
1. If any of the dice outcomes is a 1, the current player's score for the turn is 1.
2. A player who chooses to roll zero dice scores 2 more than the absolute difference between the digits in the opponent's total score.
3. After points for the turn are added to the current player's score, if both scores are larger than 1 and either one of the scores 
   is a positive integer multiple of the other, then the two scores are swapped.
