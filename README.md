# Frontend Mentor - QR code component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV/hub).

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Solution Screenshot](#solution-screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [Layout](#layout)
    - [What I learned](#what-i-learned)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

## Overview

In the source code you will find what I consider the bare minimum markup and styles that I came up with to solve the challenge, with the addition of some landmark roles to comply with Accessibility best practices.

### Solution Screenshot

![Solution screenshot](./images/solution_1.png)

### Links

Sandboxes with the solution are available at the following links:

- View it on Repl.it: [Live solution]()
- View it on Codepen: [Live solution]()

## My process

### Built with

- Visual Studio Code
- Semantic HTML5
- CSS
- Mobile-first workflow
- axe-core 4.6.3

### Layout

The basic layout in which the QR code is rendered follows this markup:

```html
<div id="results-panel">
  <section class="summary">
    <h1>Results</h1>
    <p class="score-box">
    <p class="score-grade">
    <p class="score-rank">
  <section class="details">
    <h2>Summary></h2>
    <p class="..."> * 4 times
    <button>
</div>
```

### What I learned

I learned how to use line-height property to vertically center text (no line breaks) within a container by setting its value equal to that of the height property in the same container.
I learned the correspondence between rgb() --> rgba() and hsl() --> hsla().

## Author

- Frontend Mentor - [@efabrizio75](https://www.frontendmentor.io/profile/efabrizio75)
- Vercel space - [Work in progress](https://vercel-tmpl-react.vercel.app/)
- Netlify space - [Work in Progress](https://factotum-jammming.netlify.app/)

## Acknowledgments

Obviously, there wouldn't be this file without the wonderful idea that is Frontendmentor.io. Thank you guys!
