# Love Snake

A colourful Snake game built with the HTML Canvas API and plain JavaScript. No libraries, no build step.

## Features

* Enter a name and the game is personalised for that player
* Eat the hearts: the food travels down the snake's body as a bulge, and the snake grows when it reaches the tail
* Bonus mode after every 5 hearts: "Honest Love Ritah and will marry her one day" glows in the background and hearts count double for a few seconds
* Sparkles and sound effects, romantic background
* Walls wrap around, so only biting your own tail ends the game
* Arrow keys or WASD, swipe or on-screen buttons on a phone, space to pause
* Best score saved in the browser

## Run it

Open `index.html` in any browser.

## How it works

The board is a 20 x 20 grid and the snake is a list of grid squares. Each tick a new head is added and the tail is removed. When the snake eats, a "bulge" is added at the head and moves one square down the body per tick. When it reaches the tail, the tail is kept for one tick, so the snake gets longer.

## Ideas to extend

* Add a difficulty menu
* Add obstacles or special food
* Add background music

## Author

honest

