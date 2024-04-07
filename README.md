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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Screenshot of desktop view of testimonial grid](./design/screenshot.png)

### Links

- Solution URL: [Solution]()
- Live Site URL: [Live Site](https://fejiro001.github.io/testimonials-grid-section-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Gave dark font color to all odd numbered article elements except the first one.

```css
article:nth-child(odd):not(:first-child) {
  color: var(--very-dark-blackish-blue);
}
```

### Continued development

Try out more CSS pseudo classes combination

## Author

- Frontend Mentor - [@Fejiro001](https://www.frontendmentor.io/profile/Fejiro001)
- Twitter - [@aberefejiro](https://www.twitter.com/aberefejiro)
- LinkedIn - [oghenefejiro-abere](https://www.linkedin.com/in/oghenefejiro-abere-487b08161/)
