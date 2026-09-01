# Random Color Generator

A simple, interactive web application that generates a random color with the click of a button. 

## Description
This project demonstrates DOM manipulation using vanilla JavaScript. When the user clicks the "Generate color" button, the script calculates a random RGB value, displays the exact rgb() code on the screen, and updates the background color of the display box to match.

## Features
- Generates random red, green, and blue values (0-255).
- Dynamically updates text to display the current RGB code.
- Instantly changes the background color of the UI box.

## Technologies Used
- **HTML:** For the basic structure and layout.
- **CSS:** For styling and center alignment.
- **JavaScript:** For the random color math and DOM event handling.

## How to Run Locally
1. Clone this repository to your local machine using `git clone`.
2. Navigate to the project folder.
3. Open the `index.html` file in any modern web browser.
4. Click the "Generate color" button to see it in action!

## Project Structure
- `index.html` - The main structure of the page.
- `style.css` - Basic styling and layout rules.
- `app.js` - The logic for generating the color and updating the DOM.



#Simmon says Game
A web-based sequence memory game inspired by the classic "Simon Says." The application tests a player's memory by generating a growing sequence of colors that must be repeated in the exact order.

Description
This project relies on JavaScript DOM manipulation to manage game states, user inputs, and visual feedback. The game generates a random sequence using four color buttons (yellow, red, purple, green). With each successful round, the sequence grows by one color, and the level increases. If the user clicks the wrong color, the screen flashes red, and the game resets.

Features
Dynamic Sequence Generation: Automatically adds a new random color to the sequence after each successfully completed level.

Visual Feedback: Buttons flash differently depending on whether they are triggered by the game sequence or a user click.

Level Tracking: Displays the current level dynamically as the player progresses.

High Score Tracking: Keeps a record of the highest level achieved during the session.

Game Over Animation: The background flashes red to indicate an incorrect sequence before resetting.

Prerequisites
To run this JavaScript code, you will need accompanying HTML and CSS files.

HTML: Must include an <h2> for level display, an element with the ID high-score, and four clickable elements with the class btn and individual IDs corresponding to the colors (yellow, red, purple, green).

CSS: Must include .flash (for game sequence animation) and .userflash (for user click animation) classes to handle the visual button changes.

How to Play
Open the game in a web browser.

Press any key on your keyboard to start the game.

Watch the buttons carefully. One button will flash.

Click the button that flashed.

If correct, the game will progress to the next level and flash the previous sequence plus one new button.

Repeat the sequence in order.

If you click the wrong button, the game ends, displays your score, and resets. Press any key to try again.
