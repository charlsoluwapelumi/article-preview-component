# Frontend Mentor - Article preview component solution

This is a solution to the [Article preview component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/article-preview-component-dYBN_pYFT). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See the social media share links when they click the share icon

### Screenshot

![](./design/Screenshot%20(230).png)
![](./design/Screenshot%20(231).png)
![](./design/Screenshot%20(232).png)
![](./design/Screenshot%20(233).png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to use to use the transfrom property and others properties to get the desired design


```css
.share-options {
    background-color: var(--Very-Dark-Grayish-Blue);
    color: white;
    position: absolute;
    bottom: calc(100% + 28px);
    left: 50%;
    transform: matrix(1, 0, 0, 1, -100, 0);
    display: flex;
    gap: 15px;
    padding: 20px 30px;
    border-radius: 15px;
    transform-origin: bottom;
    transition: all 0.5s ease;
    visibility: hidden;
}

.share-options.active {
    visibility: visible;
}

.share-options::after {
    content: '';
    position: absolute;
    top: 100%;
    left: 46%;
    margin-left: -5px;
    border-width: 5px;
    border-style: solid;
    border-color: hsl(217, 19%, 35%) transparent transparent transparent;
}
```

### Continued development

i really want to improve my knowledge on advanced CSS


### Useful resources

- https://www.w3schools.com/css/css3_2dtransforms.asp - I really liked this pattern and will use it going forward.
- https://www.w3schools.com/css/css_tooltip.asp - This is an amazing article which helped me finally understand tooltips. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Charles Oluwapelumi](https://www.github.com/charlsoluwapelumi)
- Frontend Mentor - [@ycharlsoluwapelumi](https://www.frontendmentor.io/profile/charlsoluwapelumi)
- Twitter - [@sns charmie](https://www.twitter.com/charley06)


