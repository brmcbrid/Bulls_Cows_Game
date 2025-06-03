# Bulls and Cows Game Project

## Game Description
In each round of the Bulls and Cows game, the computer generates a secret non-repeating 4 digit
number such as **4970** with the player trying to guess the number in as few attempts as possible. 
After each guess, the computer will provide feedback indicating how many digits in the
guess matched the same digit <u>and</u> position in the secret number ("Bulls") and how many digits 
in the guess matched the same digit, but not the same position in the secret number ("Cows"). 
The player uses the feedback to deduce the secret number, making new guesses and refining their 
strategy based on the bull and cow counts.

## Game Interface Prototype Example
<pre><b>In the Bulls and Cows game, the computer generates a secret non-repeating 4 digit
code with the player trying to guess the code in as few attempts as possible.

After the player guesses, the computer will provide feedback indicating how many digits in
the guess matched the same digit and position in the secret code ('Bulls') and how many digits
matched digits in the secret code, but are not in the matching position ('Cows'). 

Let's Play Bulls and Cows

Enter guess #1: 1234
-> RESULTS: 0 Bull(s) 0 Cow(s)
Enter guess #2: 5678
-> RESULTS: 1 Bull(s) 3 Cow(s)
Enter guess #3: 5876
-> RESULTS: 2 Bull(s) 2 Cow(s)
Enter guess #4: 5867
-> RESULTS: 1 Bull(s) 3 Cow(s)
Enter guess #5: 5786
-> RESULTS: 4 Bull(s) 0 Cow(s)

Congratulations! You broke the code in 5 guesses.

Play another round (y/n): N

Thanks for playing!
</b></pre>

## Version 1
Create a working version of the game that matches the example prototype shown above. This version should be completed using only procedural coding learned in CSC 175.

## Version 2
Use an object oriented paradigm approach to refactor the version 1 code. The completed project must be a fully object oriented solution that consists of multiple classes.


