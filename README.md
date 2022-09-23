# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/screen-shot.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I used the following code in order to make the buttons stop moving when hovering over them:

```css
.sedans .btn {
  color: var(--bright-orange);
  /* part of the coding to make the button stop moving when hovering */
  border: 0.2px solid var(--bright-orange);
}
```

```css
.sedans .btn:hover {
  color: var(--light-grey);
  border: 0.2px solid var(--light-grey);
  background: var(--bright-orange);
  transition: background-color 0.3s;
}
```

## Author

- Frontend Mentor - [@codercreative](https://www.frontendmentor.io/profile/codercreative)