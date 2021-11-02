# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Links

- Solution URL: (https://github.com/Ax-cd/order-summary-challenge)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)



## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned
I first started this project in september, and I had decided to give up on it after spending more than ten days on it (struggle with Flexbox).
At the end of October, I decided to give myself a second chance, and to start over. I completed the challenge in less than a day.
As this is the first challenge I've done, I think I learned to be patient with myself, and to not give up (as cheesy as it may sound).

I struggled with flexbox and media queries, so I am quite proud of the final result.

```css
body {
    background-image: url(images/pattern-background-desktop.svg);
    background-repeat: no-repeat;
    background-color: hsl(225, 100%, 94%);
    display: flex;
    justify-content: center;
}

@media only screen and (max-width: 375px) {
    body {
        background-image: url(images/pattern-background-mobile.svg);
        background-color: hsl(225, 100%, 94%);
    }
}
```

### Continued development
In future projects I want to focus on:
- using Flexbox (and Grid)
- being comfortable with layouts
- being comfortable with media queries (and responsive designs)

### Useful resources

- Flexbox Froggy (https://flexboxfroggy.com) - This game helped me recall the differents CSS properties to place properly the HTML elements using Flexbox.



## Author

- Website - Ax-cd (https://axcoding.blogspot.com/)
- Frontend Mentor - @Ax-cd(https://www.frontendmentor.io/profile/Ax-cd)
- Instagram - @ax.coding (https://www.instagram.com/ax.coding/)