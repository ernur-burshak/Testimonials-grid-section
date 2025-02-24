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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

Mobile version:
![](../testimonials-grid-section-main/design/mobile-design.jpg)

Tablet version:
![](../testimonials-grid-section-main/design/tablet-design.png)

Desktop version:
![](../testimonials-grid-section-main/design/desktop-design.jpg)

### Links

- Solution URL: [solution URL here](https://github.com/ernur-burshak/Testimonials-grid-section)
- Live Site URL: [live site URL here](https://ernur-burshak.github.io/Testimonials-grid-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

In this project, I improved the skill of using CSS Grid and wrote cleaner code.

```css
@media (min-width: 48rem) and (max-width: 64rem) {
  main {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: auto auto auto auto;
    gap: 2rem;
    justify-items: center;
    width: min(100%, 40.4375rem);
  }

  .card {
    width: min(100%, 40.4375rem);
  }

  .card-purple {
    grid-column: 1 / 3;
    grid-row: 1;
  }

  .card-grey {
    grid-column: 1 / 2;
    grid-row: 2;
  }

  .card-white-1 {
    grid-column: 2 / 3;
    grid-row: 2;
  }

  .card-dark-blue {
    grid-column: 1 / 3;
    grid-row: 3;
  }

  .card-white-2 {
    grid-column: 1 / 3;
    grid-row: 4;
  }

  .card-purple {
    background-image: url("../images/bg-pattern-quotation.svg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: 23.125rem 0rem;
    background-size: 110px 100px;
  }
}
```

```css
@media (min-width: 64.0625rem) {
  main {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: auto auto;
    gap: 2rem;
    justify-items: center;
    align-items: center;
    width: fit-content;
    max-width: 69.625rem;
  }

  .card {
    width: fit-content;
    max-width: 69.625rem;
  }

  .card-purple {
    grid-column: 1 / 3;
    grid-row: 1;
  }

  .card-grey {
    grid-column: 3 / 4;
    grid-row: 1;
  }

  .card-white-1 {
    grid-column: 1 / 2;
    grid-row: 2;
  }

  .card-dark-blue {
    grid-column: 2 / 4;
    grid-row: 2;
  }

  .card-white-2 {
    grid-column: 4 / 5;
    grid-row: 1 / 3;
  }

  .card-purple {
    background-image: url("../images/bg-pattern-quotation.svg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: 23.125rem 0rem;
    background-size: 110px 100px;
  }
}
```

### Continued development

I'm looking forward to including JS animations on my projects.

### Useful resources

- [resource 1](https://www.frontendmentor.io/) - It always helps to improve Frontend skills.
- [resource 2](https://chatgpt.com/) - He helped me when writing the code.

## Author

- Website - [Ernur](https://ernur-burshak.github.io/Testimonials-grid-section/)
- Frontend Mentor - [@ernur-burshak](https://www.frontendmentor.io/profile/ernur-burshak)
- Linkedin - [Ernur Burshak](https://www.linkedin.com/in/ernur-burshak-7b6b0b31b?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

## Acknowledgments

I always thank the Frontend Mentor platform for giving me a good practice.
