
## Table of contents

- [Overview](#overview)
  - [Screenshots](#screenshots)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

This is a number-guessing game project. The user has to guess a correct number between 1 to 20. The starting score is set at 20 and user has to guess a correct number to win, for every wrong guess one point is deducted from the set score. 

If the user guess is less than the correct number, too low message is displayed and if user guess is above the correct number, too high message is displayed on the screen.

If user do not enter any number, No number warning will be given to user.

Once the user wins the current score is set to high score. When the user starts game again, they can compete to increase their high scores from the last time.

Happy Playing!!

### Screenshots
The screenshots of the game in action can be found in Screenshot folder.

## My process

### Built with

- Javascript DOM
- Semantic HTML5 markup
- CSS Styles

### What I learned

- DOM Manipulation with Javascript
- Event Handling
- Manipulating CSS styles
- Implementing Game Logic


```html
<h1>Some HTML code I'm proud of</h1>
<input type="number" class="guess" />
```
```js
document.querySelector('body').style.backgroundColor = '#457963';
const guess = Number(document.querySelector('.guess').value);
```

### Useful resources

- [The Complete JavaScript Course 2021: From Zero to Expert](https://www.udemy.com) - This course by Jonas Schmedtmann made me love Javascript and inspired to create this project.
- [W3Schools CSS Tutorial](https://www.w3schools.com) - This is an amazing website which I always refer to for revisiting HTML and CSS and basics of Javascript. I'd recommend it to anyone starting on with the web development.

## Author

Pranita Tapase
