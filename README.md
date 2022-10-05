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


# The Functionality
•	The portfolio page itself is pretty starightforward, given it is a single page application. The navbar provides the links to various points on the page, with the logo acting as a home link as well. The social media links also link to my social media pages away from the site.

•	The banner section now has a ticker headline which scrolls between "Web Developer", "Web Designer" and "UI/UX Designer" for an added element of fun, and my image scrollls horizontally. The "Lets connect" button will scroll you down to the contact form at the bottom of the page.

•	In the Experience section I have provided a brief synopsis of my working career to date, along with a fun interactive carousel. Click on the arrow under the text and it will link to my full CV.

•	The next section is the "My Work" (projects) section. Instead of CSS Grid, I used Bootstrap to position the images, which if clicked upon will take ypu through to the relevant project on my Github. I also created a tab section with three tabs that allows you to see "my Projects", "More Projects" and "Projects in development".

•	Finally we have the Contact page, which includes a fully functional contact form and an icon which uses the animate library to bounce into shot.

# Ren-dle
![Rendle](https://user-images.githubusercontent.com/93707792/194070320-d89709d4-ca33-486e-86f2-663f4b685e53.jpg)

