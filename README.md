# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./images/Huddle%20landing%20page%20with%20single%20introductory%20section%20mobile%20view.png)

![](./images/Huddle%20landing%20page%20with%20single%20introductory%20section.png)


### Links

- Solution URL: [View solution URL here](https://github.com/preciousvictory/Huddle-landing-page-with-single-introductory-section-)
- Live Site URL: [View live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

- I learnt how to use CSS variables to assign values to them then call it letter while coding. I used it to get the colors so that i don't have to copy and paste colors, i'll just call the color variable var()
```css
:root{
    --Violet: hsl(257, 40%, 49%);
    --SoftMagenta: hsl(300, 69%, 71%);
}

body{
    background-color: var(--Violet);
}

.btn:hover, .btn:active{
    background-color: var(--SoftMagenta);
}
```

- I practiced more on using font icon library for the social icon and setting the size using font-size: ;

```html
<a href="#" class="icon">
  <i class="fa-brands fa-facebook-f"></i>
</a>
<a href="#" class="icon">
  <i class="fa-brands fa-twitter"></i>
</a>
<a href="#" class="icon">
  <i class="fa-brands fa-instagram"></i>
</a>
```


### Continued development

- I want to continue focusing and learn more on using CSS variables.

## Author

- Website - [Abiodun-Omoniyi Victory](https://preciousvictory.github.io/order-summary-component-main-frontendmentor/)
- Frontend Mentor - [@preciousvictory](https://www.frontendmentor.io/profile/preciousvictory)
- Twitter - [@preciousvicky_](https://www.twitter.com/preciousvicky_)
