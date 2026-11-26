# Color Game

An RGB colour guessing game built with vanilla **HTML, CSS and JavaScript** while following Colt Steele's web developer course on Udemy.

## How to play

1. The header shows an `rgb(r, g, b)` value.
2. Click the square you think matches it.
3. A wrong guess turns that square black and shows "Try Again"; a correct guess turns every square (and the header) to the winning colour.
4. Use **New Colors** to start a new round, and **Easy** (3 squares) or **Hard** (6 squares) to change the difficulty.

## Run it

No build step. Open `index.html` in a browser.

## Project structure

```
.
├── index.html   # markup
├── color.css    # styling
└── color.js     # game logic: colour generation, picking, click handling
```

## What I practised

DOM selection and manipulation, event listeners, random colour generation, and toggling UI state with CSS classes.

## Credits

Course project from Colt Steele's Udemy web developer bootcamp.
