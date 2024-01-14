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
      <p>Description of game</p>

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
1. Target the `body` and `div` element:
   Set the `font-family' to 'Arial, sans-serif'.
   Set `text-align` to `center`.
2. Target the `h1` element:
   Set the `color` to `#3498db`.
3. Target the `messages` id. This will be implemented in part 3 in the script.js file:
   Set the `font-size` to `18px`.
4. Target the `input` element:
   Set the `padding` to `5px`.
   Set the `margin` to `10px`.
5. Target the `button` element:
   Set the `padding` to `8px 16px`.
   Set the `font-size` to `16px`.
   Set the `background-color` to `3498db`.
   Set the `color` to `#fff`.
   Set the `border` to `none`.
6. Target the `playAgainButton` id:
   Set the `margin-top` to `20px`
   Set the `background-color` to `3498db`
  

### Part 3: JS
