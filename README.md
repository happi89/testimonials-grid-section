# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Screenshot from 2022-06-26 01-05-06](https://user-images.githubusercontent.com/101960666/175800194-df86bf3f-1745-4cfa-a9ad-1c123f90811a.png)

### Links

- Live Site URL: [Live Site](https://happi89.github.io/testimonials-grid-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

```css
grid-template-areas: 
  'one'
  'two'
  'three'
  'four'
  'five';
  
@media (min-width: 50em) {
  .testimonial-grid {
    grid-template-areas: 
    'one one two five'
    'three four four five'
  }
}
```
