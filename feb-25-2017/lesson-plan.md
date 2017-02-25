#Math circles lesson Feb 25 
## Algorithms (for optimization?)

How do you want to introduce the topic? - the brief introduction and jumping straight in last time was not very successful. 


History? 
Examples? 
Motivation from a technical standpoint? 

What are the basic ideas to cover in the introduction? 


Plan is to cover divide and conquer (binary search) using the coin weighing puzzle - get them to generalize the result to powers of 2 to think about growth of steps  
(give additional problems to think about - 12 coins, 9 coins etc.

### A Fake among nine coins [2]
 There are eight identical-looking coins; one of these coins is counterfeit and is known to be lighter than the genuine coins. What is the minimum number of weighings needed to identify the fake coin with a two-pan balance scale without weights?

 Each step of this can also be thought as finding one binary digit or bit when the fake coin can be represented using 3 bits. 

This approach is better thought of as decrease and conquer [1] because the number of problems to be solved decreases at each step. 
In divide and conquer methods, the size of the problems decrease, but the number of problems increase. 

Levitin [1] has a nice puzzle of covering a 2^n by 2^n grid with one missing square by trominos that nicely breaks into a divide and conquer algorithm. 

8 x 8 -> 4 diff 4 x 4 puzzles -> 4 diff 2 x 2 puzzles. 

Merge sort can be a question to think about 

Splitting trees can help grasp the growth better for both decrease and conquer and divide and conquer algorithms. 

Imagine Alice, Bob, and two piles of ten rocks. Alice and Bob are bored one
Saturday afternoon so they play the following game. In each turn a player
may either take one rock from a single pile, or one rock from both piles. Once
the rocks are taken, they are removed from play; the player that takes the last
rock wins the game. Alice moves first.


How to transition from divide and conquer to dynamic programming ideas? - They all know fibonacci numbers - is calculating fibonacci of n with some constraints on the number of steps a good example? 

and then move on to the egg drop puzzle and 

[1]: [Algorithmic Puzzles](https://www.amazon.ca/exec/obidos/ISBN=0199740445/ctksoftwareincA/), A. Levitin and M. Levitin, Oxford University Press, 2011. 

[2]: Original wording from [Cut the Knot](http://www.cut-the-knot.org/blue/EightCoins.shtml)