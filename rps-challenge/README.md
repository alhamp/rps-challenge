## Background: 
I learned my first rock, paper, scissors project when I attended an Apprenti program back in Spring 2019. From that I wanted to make a similar project for others to learn more JavaScript syntax including the use of Ecma6. I also wanted to gain more practice with UX design and some accessibility requirements so I utilized what I knew, adapted and created a new rock, paper, scissors project with the research I conducted. For students and people looking to practice the JS drills, they just need to add to the JavaScript file and a little in the html file to manipulate the DOM if they choose to.

## Instructions

Write a program where you can compete with the computer in **Rock, Paper, Scissors**. You should be able to run this code in your Google Chrome console and have it work!

### What is Rock, Paper, Scissors?

Taken from [Wikipedia](http://en.wikipedia.org/wiki/Rock-paper-scissors):

> Rock-paper-scissors is a hand game usually played by two people, where players simultaneously form one of three shapes with an outstretched hand. The "rock" beats "scissors", the "scissors" beats "paper" and the "paper" beats "rock"; if both players throw the same shape, the game is tied.

### Getting Started

You will be creating a digital version of the rock, paper, scissors game for the browser. Users should at least be able to see the results in the console.

What this project already has included:
index.html
styles.css
images
rock-paper-scissors.js
README.md

## First Level Requirement

1. Your code should be added to the `rock-paper-scissors.js`.

2. A game consists one round.

3. `Let's Play Rock, Paper, Scissors!` should appear in the console.

4. The player is prompted to choose a selection by typing `"rock"` (rock), `"paper"` (paper), or `"scissors"` (scissors).

5. The computer opponent randomly chooses between rock, paper, and scissors.

6. Output "you" and "computer" player choices. Examples:
  - `You chose rock`
  - `Computer chose scissors`

7. Output the result of the game before exiting. Examples:
  - `You won, congrats champion!`
  - `Computer wins, now the robots take over!`
  - `It is a Tie! Battle to the death!`

8. If the player enters an invalid option, print an error message.

9. If both players choose the same option, it is a tie.


## Second Level Requirements

10. If you completed everything from First Level Requirements.

12. The game ends when the player or the computer wins the best out of three rounds played

13. Ties do not count as a win.
- Output the results of each round. Examples:
  - `You chose scissors.`
  - `Computer chose scissors.`
  - `This round was a tie. Try Again!`
- Output the winner of all three rounds
  - `Computer wins the game!`
- Output the result of the game totals before exiting. Examples:
  - `You tie 1 won 2 loses 0!`
  - `Computer ties 1 wins 1 loses 1!`

## Boss Battle

14. Create a score board on browser page.

15. Have what is shown in the console from First Level now show on the browser page.

16. Make the game prompt show up only when clicking the "Play Now!" button.
----------------------------------------

### SAMPLE Console Output

**Tie:**

```no-highlight
Welcome to Rock, Paper, Scissors!
[Prompt] Choose rock, paper, or scissors: rock
You chose rock.
Computer chose rock.
Tie!
```

**Player wins:**

```no-highlight
Welcome to Rock, Paper, Scissors!
[Prompt] Choose rock, paper, or scissors: paper
You chose paper.
Computer chose rock.
Paper beats rock, you win!
```

**Computer wins:**

```no-highlight
Welcome to Rock, Paper, Scissors!
[Prompt] Choose rock, paper, or scissors: scissors
Player chose scissors.
Computer chose rock.
Rock beats scissors, Computer wins!
```

#### Tips

- It is difficult to compare shapes randomly, a way to go about this is using `math.random()` with `math.floor()`. 

- Try to check multiple conditions in a single expression by using operators like `&&` and `||`

- Make it so user will  automatically submit their option as lowercase so program can read user choice of "rock, paper or scissors".

