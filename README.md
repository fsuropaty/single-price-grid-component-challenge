# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](/images/slice1.png)
![](/images/slice2.png)

### Links

- Solution URL: [Frontendmentor.io](https://www.frontendmentor.io/solutions/single-price-grid-component-challenge-using-html-css-BLQJmpmXau)
- Live Site URL: [fsuropaty.github.io](https://fsuropaty.github.io/single-price-grid-component-challenge/)
## My process

### Built with

- SASS/SCSS
- CSS custom properties
- CSS Grid
- Mobile-first workflow


### What I learned

I learned how to use custom CSS properties and media query

```css
 h1 {
      color: var(--Cyan);
    }
 h2 {
      color: var(--Bright-Yellow);
      font-size: 18px;
    }

 p {
      color: var(--Grayish-Blue);
      line-height: 1.8rem;
    }
    
@media only screen and (min-width : 800px) {
    .container {
        display: grid; 
        grid-auto-columns: 1fr; 
        grid-template-columns: repeat(auto 1fr); 
        grid-template-rows: auto; 
        gap: 0px 0px; 
    }
```

### Continued development

Responsive Website, Semantic HTML

### Useful resources

- [W3Schools](https://www.w3schools.com) - Pretty much your guidebook in website development
- [MDN](https://developer.mozilla.org) - W3Schools but from Mozilla.


## Author

- Website - [fsuropaty](https://www.fsuropaty.github.io)
- Frontend Mentor - [@fsuropaty](https://www.frontendmentor.io/profile/fsuropaty)
