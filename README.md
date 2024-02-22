# Frontend Mentor - Blog preview card solution
This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover and focus states for all interactive elements on the page

### Screenshot

![](/Screenshot.png)

### Links

- Solution URL: https://github.com/NamanG22/BlogPreviewCard
- Live Site URL: https://namang22.github.io/BlogPreviewCard/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Simple thing I learned is that, when you want to place things side by side then display flex is best and when down then display grid property is the best.

```html
<body>
  <main></main>
  <footer>
    <div class="author">
      <img src="assets\images\image-avatar.webp" alt="...">
      <p>Greg Hooper</p>
    </div>
  </footer>
</body>
```
```css
.author{
    display: flex;
    justify-content: flex-start;
    align-items: center;
}

body {
    display: grid;
    place-content: center;
    height: 100vh;
}
```
### Continued development

When to use bootstrap or not, cause I starter using it in the begining but then things became too complicated. So, I just designed by myself. Judgement of when to use is still little unclear.

## Author

- Frontend Mentor - [@NamanG22](https://www.frontendmentor.io/profile/NamanG22)
- CodePen - [@Naman-Garg](https://codepen.io/Naman-Garg)

