
# Statistics Interview Questions

**Easy: (2 minutes)**

1. A person flips an unbiased coin over and over again.  Player A looks for the sequence HTH and player B looks for the sequence HTT. What is the probability that player A encounters their sequence first? Solution: https://dicedcoins.wordpress.com/2012/07/19/flip-hhh-before-htt/

2. Puzzle: You have 3 baskets and each basket contains exactly 4 balls; each ball is of the same size. Each ball is either red, black, yellow, or orange, and there is one of each color in each basket.  If you randomly draw 1 ball from each basket, what is the chance that you would have exactly 2 red balls? Solution: http://www.crazyforcode.com/3-baskets-4-balls-puzzle/

3. A bag contains x number of 1 rupee coins and y number of 50 paise coins. One coin is taken from the bag and put away. If a coin is now taken at random from the bag, what is the probability that it is a 1 rupee coin? Solution: http://www.crazyforcode.com/probability-rupee-coin-bag/

4. Bob is selected to interview for 3 posts.  The total number of candidates interviewing for the posts are 3, 4 and 2. What is the probability of getting at least one offer?  [Assume candidates are picked at random after interviews.] Solution: http://www.crazyforcode.com/probability-finding-job/

5. (Part A): Mr. Jones has two children. The older child is a girl. What is the probability that both children are girls?  (Part B): Mr. Smith has two children. At least one of them is a boy. What is the probability that both children are boys? Solution: http://en.wikipedia.org/wiki/Boy_or_Girl_paradox

**Harder: (5 minutes)**

1. You have two jars, 50 red marbles, and 50 blue marbles. You’ll first randomly pick a jar, and then randomly pick a marble out of that jar. You can arrange the marbles however you like, but each marble must be in a jar. You need to place all the marbles into the jars such that when you blindly pick one marble out of the chosen jar, you maximize the chances that it will be red. http://www.crazyforcode.com/red-blue-marbles/

2. You are given a choice of three doors by an Angel. You can choose only one of the doors among the three. Out of these three doors, two contain nothing and one has a jackpot.
After you choose one of the doors, the angel  reveals one of the other two doors behind which there is a nothing. The angel gives you an opportunity to change the door or you can stick with your chosen door.
You don’t know behind which door we have nothing. Should you switch or does it not matter? http://www.crazyforcode.com/3-doors-angel/

3. In a country where everyone wants a boy, each family continues having babies til they have a boy, at which point they stop having children.  What is the proportion of boys to girls in the country? (Assuming probability of having a boy or a girl is the same.) http://www.crazyforcode.com/boys-girls/

4. Three ants are sitting at the three corners of an equilateral triangle. Each ant randomly picks a direction and starts to move along the edge of the triangle. What is the probability that none of the ants collide? http://www.crazyforcode.com/ant-triangle-problem/

5. 100 passengers are boarding an airplane with 100 seats. Everyone has a ticket with his seat number. These 100 passengers board the airplane in order. However, the first passenger lost his ticket so he just takes a random seat. For any subsequent passenger, he either sits in his own seat or, if the seat is taken, he takes a random empty seat. What's the probability that the last passenger would sit in his own seat? There is a very simple explanation for the result. Solution: https://www3.nd.edu/~dgalvin1/Probpuz/probpuz3.html



**Even More Probability questions:**

1. Here are some facts about interviews:

    - 50% of all people who receive a first interview receive a second interview
    - 95% of your friends that got a second interview felt they had a good first interview
    - 75% of your friends that DID NOT get a second interview felt they had a good first interview

  If you feel that you had a good first interview, what is the probability you will receive a second interview?  http://stats.stackexchange.com/questions/86015/amazon-interview-question-probability-of-2nd-interview

2. The probability of a car passing a certain intersection in a 20 minute windows is 0.9. What is the probability of a car passing the intersection in a 5 minute window? (Assuming a constant probability throughout.) http://www.mytechinterviews.com/probability-of-a-car-passing-by

3. You have a stream of bytes from which you can read one byte at a time. You only have enough space to store one byte. After processing those bytes, you have to return a random byte. Note: The probability of picking any one of those bytes should be equal.  http://www.mytechinterviews.com/random-byte-from-a-stream-of-bytes

4.  I have three colored cards. Two of the cards are painted green on each side, and
one is painted orange on one side and green on the other. Suppose you are shown a single
face of a card and that face is green. Find the probability that the other side is orange.  https://math.stackexchange.com/questions/513250/conditional-probability-question-with-cards-where-the-other-side-color-is-to-be

5. You roll two dice. Determine if the following events are independent: A = "the sum of two dice is odd" and B = "the second die is a 3."  https://rstudio-pubs-static.s3.amazonaws.com/295205_c52277a3e3804f36b34615e0073b688f.html

6. Let X be a uniformly distributed Random Variable on [1, 2].  What is the $E[X^2]$? https://stt.msu.edu/Academics/ClassPages/uploads/SS14/442-1/hw%20solution%20w1%20jan8-jan10.pdf

7. You have 52 playing cards (26 red, 26 black). You draw cards one by one. A red card pays you a dollar. A black one fines you a dollar. You can stop any time you want. Cards are not returned to the deck after being drawn. What is the optimal stopping rule in terms of maximizing expected payoff?  Also, what is the expected payoff following this optimal rule?  http://puzzles.nigelcoldwell.co.uk/fourteen.htm

8.  You have 2 decks of cards (each deck contains both red and black cards). One deck has twice the number of cards in the other deck, with the same color ratio (so one deck has 52 cards and the other has 104, both half red and half black). I offer you to play a game. First you get to choose which deck of cards you want to play with. Second, you draw 2 cards at random from your deck of choice. If both are the same color, then I will give you a Ferarri. Which deck of cards would you choose? Solution (similiar problem): https://math.stackexchange.com/questions/1549306/which-is-the-better-deck-of-cards

9. You have two dice. There are two players. You each pick a number in turn and the second person cannot pick the same number as the first. The person who picks the number closest or equal to the sum of the roll of the dice is the winner. What are each player's strategies?  Who has a greater chance of winning?

10. Person A has a 30-sided die (numbered 1 - 30) and person B has a 20-sided die (numbered 1 - 20). Both players role and the person with the highest role wins (on a draw B wins).  The loser pays the winner the value of the winner's die.
  - Calculate expected value of this game for player A.
  - How does this value change if player B can re-roll?
  
11. You have two fair dice.  I will roll it.  If you can correctly guess their sum, I will pay you the sum.  There is no penalty for misguessing.  What should you guess and how much do you expect to make?  What is the answer if we replace the word "sum" with "product"?

12. You are given a die with 100 sides numbered 1 - 100. You are given a chance to roll the die and you can (a) take the amount in dollars that corresponds to the number that was rolled or (b) pay $1 and roll again. You can continue to reroll as many times as you see fit, but you only keep the money of the one roll that you choose to end with. What is the optimal strategy and expected value?

13. Two teams have an equal probability of winning (and no chance of tying) a game.  A tournament ends when one team has two more wins than the other.  What is the probability that they will play at least 7 games?  What about the general case of $n$ more wins?

14. Play a game with an urn that has 75 blue balls, 25 red balls, and 1 yellow ball.  You draw balls without replacing them back into the urn.  You get a dollar for every red ball and if you select the yellow ball, you lose all your earnings and must stop playing.  What should be your strategy in the game?

15. There are 10 lightbulbs in a row, all either on or off.   No two adjacent lightbulbs can be on.  How many configurations can we have?

16. You have five coins. One is double-headed. Pick one coin at random without looking and throw it five times. Suppose the outcomes are five heads; what is the probability that the coin picked is the double-headed one?

17. Suppose you have two $n$-sided dice.  What is the expected value of the difference of two rolls?

18. I own a car with a resale value between 0 and 1000 dollars (uniformly distributed). You can make a single bid on this car. If you bid higher than the value of the car, you pay that much and get the car. If you bid lower than the value, you don't get the car.
    - What should you bid?
    - Your friend is a mechanic who can increase the resale value of the car by $x$ percent (without charge).  What should you bid as a function of $x$?
    - What if your friend could increase the resale value by $x$ dollars?  What should you bid as a function of $x$?
    
19. Four fair coins are flipped.
    - You get one dollar each time heads appears. What is the expected payoff?
    - What is the expected payoff if you know at least two heads appeared?

20. You have a die and are told that when you roll it you will receive the amount rolled. What is the expected value? If you have the option to roll again, what is the expected value? If you have the option to roll a third time, what is the expected value?

21. You have a lottery ticket with 10 slots. Behind each slot there's an equally distributed number between 0 and 1. Your payout is the maximum number between any of these slots. How much are you prepared to pay for the lottery ticket?

22. Given a 12 sided die, you roll the die repeatedly until the cumulative sum is odd. What is the number of the cumulative sum you can have with the highest probability?

23. If you toss a fair coin 10 times, what is the expected product of number of heads and number of tails? 

25. If I have a 4x4x4 cube and I paint the outside of the cube, then I cut it into 64 1x1x1 cubes...
    - How many have at least one side painted?
    - If I pick one of the 64 cubes up and roll it, what is the probability that the top side is painted?

**Harder (mostly brain teasers): (5 minutes)**

1. You are give 12 identical-looking balls. One of them is fake (could be heavier or lighter than the rest of the 11; all the others weigh exactly the same). You are provided with a simple mechanical balance and you are restricted to only 3 uses. Find the fake ball.  http://www.mytechinterviews.com/12-identical-balls-problem

2. Write a method to generate a random number between 1 and 7, given a method that generates a random number between 1 and 5. The distribution between each of the numbers must be uniform. http://www.mytechinterviews.com/equal-probability-between-1-and-7

3. Given a fleet of 50 trucks, each with a full fuel tank and a range of 100 miles, how far can you deliver a payload? You can transfer the payload from truck to truck, and you can transfer fuel from truck to truck. Assume all the payload will fit in one truck. http://www.mytechinterviews.com/challenge-50-trucks-with-payload

4. A duck that is being chased by a fox saves itself by sitting at the center of circular pond of radius r. The duck can fly from land but cannot fly from the water. Furthermore, the fox cannot swim. The fox is four times faster than the duck. Assuming that the duck and fox are perfectly smart, is it possible for the duck to ever reach the edge of the pond and fly away to its escape from the ground? http://www.mytechinterviews.com/the-fox-and-the-duck

5. A train leaves City X for City Y at 15 mph. At the very same time, a train leaves City Y for City X at 20 mph on the same track. At the same moment, a bird leaves the City X train station and flies towards the City Y train station at 25 mph. When the bird reaches the train from City Y, it immediately reverses direction. It then continues to fly at the same speed towards the train from City X, when it reverses its direction again, and so forth. The bird continues to do this until the trains collide. How far would the bird have traveled in the meantime? http://www.mytechinterviews.com/trains-and-birds

6. We consider numbers from 1 to 1 million. How many times does the digit "2" appear?

7. If you have a 6 by 6 matrix where each element is either 1 or -1, how many unique matrices are there such that each row and each column multiplies to 1?  http://www.glassdoor.com/Interview/if-you-have-a-6-by-6-matrix-where-each-element-is-either-1-or-1-how-many-unique-matrices-are-there-such-that-each-row-and-QTN_314169.htm

8. For a bus, there are three stops and at each stop 3/4 people gets off and 7 people get on. What is the minimum number of passengers at the beginning? http://www.glassdoor.com/Interview/A-bus-there-are-three-stops-each-stop-3-4-people-gets-off-and-7-people-get-on-What-is-the-minimum-number-of-passengers-a-QTN_207831.htm

9. Today is 15/09/2011. What's the nearest day in the future that all of the eight digits are unique?  http://www.glassdoor.com/Interview/Today-is-15-09-2011-what-s-the-nearest-day-in-the-future-that-all-the-eight-digits-are-unique-QTN_190876.htm

10. Let’s say that you have 25 horses, and you want to pick the fastest 3 horses out of those 25. In each race, only 5 horses can run at the same time because there are only 5 tracks. What is the minimum number of races required to find the 3 fastest horses without using a stopwatch? http://www.programmerinterview.com/index.php/puzzles/25-horses-3-fastest-5-races-puzzle/


