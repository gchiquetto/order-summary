# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

The Order summary card challenge should be concluded using HTML5 and CSS. In the challenge, I had to build a deskopt and mobile version to a order summary card.

### Screenshot

#### Desktop version
![desktop version screenshot](/images/desktop-screenshot.JPG) 

#### Mobile version
![mobile version screenshot](images/mobile-screenshot.JPG)

### Links

- Solution URL: https://gchiquetto.github.io/order-summary/

## My process

### Built with

- HTML5
- CSS 
- Flexbox

### What I learned


#### HTML
I nested divs in order to use css flexbox to create the area that contais the plan choice.
```html
<div class="box-plan">
  <img class="music" src="../images/icon-music.svg" alt="icon-music">
  <div class="box-value">
    <h3>Annual Plan</h3>
    <p class="value">$59.99/year</p>
  </div>
  <a class="change" href="#">Change</a>
</div>
```

#### CSS
I've learnt how to add images using CSS, which was good for setting the body background in the same was that was asked in the challenge. I also explored more the background- options.

```css
body{
  background-image: url("../../images/pattern-background-desktop.svg");
  background-repeat: repeat-x;
  background-color: hsl(225, 100%, 94%);
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  text-align: center;
  font-family: 'Red Hat Display', sans-serif;
}
```

## Author

- Website - [Linkedin](https://www.linkedin.com/in/gabriela-chiquetto-b6917533/)
- Frontend Mentor - [@gchiquetto](https://www.frontendmentor.io/profile/gchiquetto)

