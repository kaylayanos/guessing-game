# Guessing Game

### Description
This is a simple game. The computer will come up with a random number from a given range of numbers. Then, the user will be able to input numbers until the user guesses the random number correctly.

### Difficulty
Beginner

### Prerequisites
- JS variables
- JS conditionals
- JS functions
- JS loops

### Setup
Create the following files:
- index.html
- style.css
- script.js

### Part 1: HTML
1. Start by editing the `<head>` tags. We will link the css here. Make sure that you are linking the style.css file correctly!
   ```
   <head>
     <meta charset="utf-8">
     <meta name="viewport" content="width=device-width">
     <title>Guessing Game</title>
     <link href="style.css" rel="stylesheet" type="text/css" />
   </head>
   ```
2. Now, we will edit the `<body>` tags. This is were we will the game and link the script.js file. Edit the inside of the in `<p>` tag with the description of the game.
   ```
   <body>
      <h1>Guessing Game!</h1>
     <h2>Description</h2>
     <p>The computer will randomly choose a number from a specified range and it is your task to guess the number!</p>

     <div>
         <h1>Guessing Game</h1>
         <p id="message">Guess a number between 1 and 5</p>
         <input type="number" id="guessInput">
         <button onclick="checkGuess()">Submit Guess</button>
         <script src="script.js"></script>
     </div>
     <script src="script.js"></script>
   </body>
   ```

### Part 2: CSS

### Part 3: JS
