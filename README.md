# Manage landing page solution

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
- See hover states for all interactive elements on the page
- See all testimonials in a horizontal slider
- Receive an error message when the newsletter sign up `form` is submitted if:
  - The `input` field is empty
  - The email address is not formatted correctly

### Screenshot

Lighthouse screenshot

[Screenshot](images/lighthouse.PNG)

### Links

- Solution URL: [Github](https://github.com/MelakuAlehegn/manage-landing-page)
- Live Site URL: [Live](https://melakualehegn.github.io/manage-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Flexbox
- Javascript

### What I learned

I have learned how to use javascript to add and remove classes from html elements for different screen sizes.

```js
function showMenu() {
  document.querySelector(".nav-links").classList.toggle('active');
  document.querySelector(".humberger").classList.toggle('hide');
  document.querySelector(".close").classList.toggle('show');
}
```
