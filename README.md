# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](product-preview-card-component-main\images\screenshot-desktop.png)
![](product-preview-card-component-main\images\screenshot-mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

Below is the code I used to change the image according to the user's screen size.
```html
<img srcset="images/image-product-desktop.jpg 600w, images/image-product-mobile.jpg 686w"
          sizes="(max-width: 600px) 686px, 300px" src="images/image-product-desktop.jpg"
          alt="Perfume Gabrielle Chanel Paris">
```

This CSS snippet was used to import external fonts into my web site.
```css
@import url('https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,700&family=Montserrat:wght@500;700&display=swap');
```

Worrying again about the responsiveness of the site, in the CSS file, I used @media to work with different configurations for screens of different proportions.
```css
@media only screen and (max-width: 600px) {}
```

## Author

- Frontend Mentor - [@LucasDeSousaR](https://www.frontendmentor.io/profile/LucasDeSousaR)
- Twitter - [@LucasDeSousaR](https://twitter.com/LucasDeSousaR)