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
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [https://github.com/aljager1983/nft-preview-card-component-main]
- Live Site URL: [https://aljager1983.github.io/nft-preview-card-component-main/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

This is my 4th solution in FrontEndMentor. On this challenge I have learned opacity manipulation in CSS and displaying another image in front of the other giving more depth to hover effects.

Below are the code snippet for the hover effects:
```css
.nftimg {
    opacity: 1;
    transition: .5s ease;
}

.preview:hover .nftimg {
    opacity: 0.3;
}
.preview:hover .midicon {
    opacity: 1;
}

.midicon {
    display: grid;
    align-content: center;
    position: absolute;
    width: 270px;
    height: 270px;
    transition: .5s ease;
    background-color: hsla(178, 100%, 50%, 50%);
    border-radius: 10px;
    opacity: 0;
    backface-visibility: hidden;
}

.icon {
    height: 50px;
    width: 50px;
}
```

### Continued development

Learning is an unending process. Going to get more challenges as im learning a lot here. 

### Useful resources

- [Advantag of Mobile First workflow](https://www.youtube.com/watch?v=0ohtVzCSHqs) - This helped me in my workflow of mobile first design. I am going to adopt this workflow as I feel theres huge difference against with DESKTOP first.


## Author

- Frontend Mentor - [@aldrinbfernandez](https://www.frontendmentor.io/profile/aldrinbfernandez)
- Twitter - [@promdiGamer](https://twitter.com/promdiGamer)


## Acknowledgments

I have been a member of frontend mentor for a while, and I have seen your link in the discord of Angela Yu. I just recently finished her course of Web Development Bootcamp in Udemy. Thanks to her, I got the arsenal (tho still have a lot to learn) to accomplish this challenge.
