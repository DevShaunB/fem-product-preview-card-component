# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Reference](#reference)
  - [Font](#font)
  - [Color](#color)
- [Run Locally](#run-locally)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Product preview card component desktop screenshot](https://devshaunb.github.io/fem-product-preview-card-component/screenshots/desktop.png)

![Product preview card component mobile screenshot](https://devshaunb.github.io/fem-product-preview-card-component/screenshots/mobile.png)


### Links

- Solution URL: [https://www.frontendmentor.io/solutions/product-preview-card-component-using-flexbox-and-css-grid-2FMyWC2ilX](https://www.frontendmentor.io/solutions/product-preview-card-component-using-flexbox-and-css-grid-2FMyWC2ilX)
- Live Site URL: [https://devshaunb.github.io/fem-product-preview-card-component](https://devshaunb.github.io/fem-product-preview-card-component)

## Reference

### Font

- Family: [Montserrat](https://fonts.google.com/specimen/Montserrat)
- Weights: 500, 700
<br/>

- Family: [Fraunces](https://fonts.google.com/specimen/Fraunces)
- Weights: 700

### Colors

#### Primary

- ![hsl(158, 36%, 37%)](https://via.placeholder.com/10/3c8067?text=+) `Dark cyan: hsl(158, 36%, 37%)`
- ![hsl(30, 38%, 92%)](https://via.placeholder.com/10/f2ebe3?text=+) `Cream: hsl(30, 38%, 92%)`

#### Neutral

- ![hsl(212, 21%, 14%)](https://via.placeholder.com/10/1c232b?text=+) `Very dark blue: hsl(212, 21%, 14%)`
- ![hsl(228, 12%, 48%)](https://via.placeholder.com/10/6c7289?text=+) `Dark grayish blue: hsl(228, 12%, 48%)`
- ![hsl(0, 0%, 100%)](https://via.placeholder.com/10/ffffff?text=+) `White: hsl(0, 0%, 100%)`

## Run Locally

Clone the project

```bash
  git clone https://github.com/DevShaunB/fem-product-preview-card-component.git
```

Go to the project directory

```bash
  cd fem-product-preview-card-component/
```

Run `index.html`

```bash
  <browsername> index.html
```

E.g.

```bash
  firefox index.html
```

```bash
  google-chrome index.html
```

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

- using "picture" HTML element

```html
<picture>
  <source
    media="(min-width:640px)"
    srcset="/images/image-product-desktop.jpg"
  />
  <img
    src="/images/image-product-mobile.jpg"
    alt="Gabrielle Essence Eau De Parfum"
    style="width: auto"
  />
</picture>
```

- using grid to create two equal columns

```css
.two-equal-columns {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
}
```

- using media queries for mobile responsive layout

```css
@media screen and (max-width: 640px) {
  /* CSS rules */
}
```

- creating screen-reader-only elements

```css
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  clip-path: inset(50%);
  white-space: nowrap;
  border-width: 0;
}
```

- creating and styling a button with icon and text

## Author

- Frontend Mentor - [@DevShaunB](https://www.frontendmentor.io/profile/DevShaunB)
- Twitter - [@DevShaunB](https://www.twitter.com/DevShaunB)

## Acknowledgments

- [Product preview card component](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa) by [Frontend Mentor](https://www.frontendmentor.io/)