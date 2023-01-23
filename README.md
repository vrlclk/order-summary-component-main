# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](https://kappa.lol/AFa74)

### Links

- Solution URL: [](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj/hub)
- Live Site URL: [](https://order-summary-by-vrlclk.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS reset by Josh Comeau
- Flexbox for the plan label
- CSS Grid for positioning the card
- Mobile-first workflow

### What I learned

- How to use ``box-shadow``
- How to add background images for mobile and desktop view using media queries and move it to the corresponding places with ``background-position``
```
body{
  background-image: url(images/pattern-background-mobile.svg);
  background-repeat: no-repeat;
  background-size: 100% auto;
}

@media (min-width: 800px){
  body{
    background-image: url(images/pattern-background-desktop.svg);
    background-position: 0 -3rem;
  }
}
```
- New properties like ``background-repeat``, ``background-size`` to fit the image to the window.
- Set the attribution's position to absolute and place it to the bottom with these two settings:
```
.attribution{
  position: absolute;
  bottom: 0;
}
```

### Useful resources

- [Josh Comeau's CSS reset](https://www.joshwcomeau.com/css/custom-css-reset/) - I recommend using this if you want to avoid the browsers default CSS rules.
- [CSS background properties](https://developer.mozilla.org/en-US/docs/Web/CSS/background#constituent_properties)
- [CSS box-shadow properties](https://developer.mozilla.org/en-US/docs/Web/CSS/border-radius)

## Author

- Frontend Mentor - [@vrlclk](https://www.frontendmentor.io/profile/vrlclk)
- GitHub - [@vrlclk](https://www.github.com/vrlclk)