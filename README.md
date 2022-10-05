# Ren-dle - A Wordle Clone
I really enjoy word games. Crosswords, anagrams, word searches. No word is too long or too short. So combining a passion for words with a passion for coding lead me to this cheeky little project ... creating a clone of Wordle. Don't forget to pay homage to the real Wordle by heading over to the <a href="https://www.nytimes.com/games/wordle/index.html">New York Times</a> webpage!

# What I used:
•	React
•	JavaScript
•	CSS
•	SCSS
•	GitHub

# The Design
The design of Ren-dle is in keeping with the original Wordle. It's pretty basic, with a black background, a white h1 heading with a gray border-bottom, followed by two boards: the game board (which comprises of 6 5-letter guesses) and the QWERTY keyboard (which includes larger DELETE and ENTER buttons. Upon completion of the game, a basic text box with a Game Over message appears.

# The Process
I took a step-by-step process to designing Ren-dle. Using ReactJS to create the single-page application, I created a Board component, which represented each cell/letter on the board, using a matrix that I created in a Word.js document. The cells were created using six divs representing different rows within the board. A letter component was also created to evaluate the letter position and attempt value.
The keyboard component was also made using divs and three arrays of key values which I eventually mapped through to get the individual keys. Here we had to add the ENTER and DELETE keys individually because they were larger buttons. A Key component was also created that allows you to select the letter through an onClick function and add it to the board.
Using a word bank of over 2000 five-letter words, I used Fetch to randomly select a word ech time the game is played. Upon completion of the game, a function was created to signal the game is over, displaying how many attempts it took to guess the word, or if indeed you failed to guess the word.


# The Functionality
Using React Hooks (UseState, UseEffect), State Management (UseContext, Context API and Javascript Logic I was able to add the functionality needed to recreate the Wordle game.

From selectLetter functions, to GameOver functions and correctWord functions, the game works as you would expect.

As explained earlier I used Fetch to collect the wordBank and convert it into a Set, which we then represented in a state so we had access to it everywhere in the project, especially when we press Enter. That was important because, we needed to confirm upon Enter press, whether or not that word was in the word bank.



# Ren-dle
![Rendle](https://user-images.githubusercontent.com/93707792/194070320-d89709d4-ca33-486e-86f2-663f4b685e53.jpg)

