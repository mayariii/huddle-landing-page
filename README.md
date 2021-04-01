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
- [Author](#author)


## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![Desktop](screenshot-desktop.png)
![Mobile](screenshot-mobile.png)


### Links

- Solution URL: [https://www.frontendmentor.io/solutions/single-pricing-card-component-html-and-css-with-flexbox-and-grid-0YFT-MSj6](https://www.frontendmentor.io/solutions/single-pricing-card-component-html-and-css-with-flexbox-and-grid-0YFT-MSj6)
- Live Site URL: [https://nicoleanalisecox.github.io/price-grid-component/](https://nicoleanalisecox.github.io/price-grid-component/)

## My process

### Built with

- HTML
- CSS / Flexbox 
- Sass

### What I learned

**Day 1: **
Using Sass for the first time, after watching Brad Traversy's Sass Crash Course.  [Sass Crash Course] (https://www.youtube.com/watch?v=nu5mdN2JIwM)
Set up Live Sass Compiler & Live Server extensions. Set up stylesheets & applied the a font style to the body to test that the stylesheets were linked successfully.

**Day 2: **
Set up the HTML structure. Added background colour & background image. 
Used flexbox to get the main content in two columns, with the image on the left in one div, and the text content on the right in another div. In the parent container, used display: flex; with align-items: center; and justify-content: center;.
Also made use of nesting selectors in Sass.

**Day 3: **
Tweaked padding on the elements. Added font awesome icons for the social links. 
Used flexbox (justify-content: flex-end) to align icons to the left. 
Handy cheat sheet: [Flexbox Cheat Sheet](https://flexbox.malven.co/)
Looked at how I could create circle border on the font awesome icons. Found out about stacking through this post: [How to create circular backgrounds for your font awesome icons](https://markheath.net/post/font-awesome-circle-background). The lines are too thick currently and don't match the design very well.

**Day 4: **
Started with looking at the icons again. Had a goodle and found this stack overflow post to help me achieve what I wanted with basic CSS, using the border and border-radius properties. 
[Can you put a circle border round an icon in HTML5](https://stackoverflow.com/questions/25309500/can-you-put-a-white-circled-border-around-a-icon-in-html5/25309638#25309638)
Styled the Register button with a box shadow and border radius, using a large radius to get the oval shape. Also added 'cursor: pointer;' inspired by feedback from my previous Front End Mentor project. 
Added hover states to the register button and social links with the :hover selector.

**Day 4: **
Added in a mobile partial for responsiveness. Used flex-direction: column to stack the main content vertically. Pretty much centered everything, and adjusted sizing of images and fonts. Tidied up code.

### Issues I had:
**Problem:**
Images weren't showing up.
**Solution:**
I did the same on my first project accidentally, so remembered that the references in a url need to be relative to the current stylesheet that line of code is in. 

## Author

- Website - [Nicole Analise Cox](https://www.nicoleanalisecox.co.uk)
- Frontend Mentor - [@nicoleanalisecox](https://www.frontendmentor.io/profile/nicoleanalisecox)
- Instagram - [@nicolencode](https://www.instagram.com/nicolencode_)
- Twitter - [@_nicoleanalise](https://www.twitter.com/_nicoleanalise_)