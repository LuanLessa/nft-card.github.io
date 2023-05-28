# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](design/Captura%20da%20Web_28-5-2023_163435_127.0.0.1.jpeg)

### Links

- Solution URL: [GitHub](https://github.com/LuanLessa/nft-card.github.io)
- Live Site URL: [GitHub Pages](https://luanlessa.github.io/nft-card.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

In this new project there was a lot of new challenges like displaying items side by side and some really cool transition effects, I had a lot of trouble to align items correctly, I did a lot of research to complete this challenge.

there are some new codes that I learned that was helpfull like:

using icons
```html
<i class="material-icons">visibility</i>
<svg class="ethicon" width="11" height="18" xmlns="http://www.w3.org/2000/svg"><path d="M11 10.216 5.5 18 0 10.216l5.5 3.263 5.5-3.262ZM5.5 0l5.496 9.169L5.5 12.43 0 9.17 5.5 0Z" fill="#00FFF8"/></svg>
```
Uses of ::before, ::after, hover effects, transitions and transparency
```css
.imgwraper::before{}
.imgwraper:hover::before{
  background-color: hsla(178, 100%, 50%, 0.5);
  opacity: 0;
  transition: opacity 0.5s ease;
}
```

### Continued development

Still focusing on learn the basics of html and css and in the future more about responsiveness and new effects and tricks

### Useful resources

- [Material Design](https://m3.material.io/) - This is a design system standard for web and mobile development.
- [W3 Schools](https://www.w3schools.com/) - For basic html and css syntax.
- [Stack Overflow](https://stackoverflow.com/) - For basic html and css syntax.
- [MDN Web Docs](https://developer.mozilla.org/en-US/) - For more complete information and documentation about html and css.

## Author

- Website - [Luan Lessa](https://github.com/LuanLessa)
- Frontend Mentor - [@LuanLessa](https://www.frontendmentor.io/profile/LuanLessa)