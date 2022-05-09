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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

This is an Order Summary Component built using HTML & CSS.

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

https://gyazo.com/748c0e4bd746908caaac423792452226

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I first coded out the HTML markup, adjusted it all with flex box. 
I noticed that most of the divs would be similar when it comes to padding, margin, and border radius.
So I decided to make the parent div contain those properties and used flexbox with the column direction.
For the plan section, I made a grid and positioned accordingly to match the design.
Lastly I made each of the elements interactive and increase the size of the component for desktop using a media query.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

- How to implement variables in CSS
- Overlaying an image on padding
- How to use CSS Grid
- Using Media Queries


```css
/* Hero Image */
.hero_img {
    /* Fills the padding around the image */
    max-width: calc(100% + 4rem);
    margin: 0 -2rem;


    display: block;
    border-top-left-radius: 1rem;
    border-top-right-radius: 1rem;
}
```

### Continued development

In future projects, I intend to get more comfortable with styling more quickly and easily. I plan on moving to JavaScript soon, but I started Front End Mentor to make sure I could actually apply what I learned.

### Useful resources

- [Resource 1](https://developer.mozilla.org/en-US/) - This helped me find the syntax for certain commands

## Author

- Frontend Mentor - [@thejackshelton](https://www.frontendmentor.io/profile/thejackshelton)
