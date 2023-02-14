# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![Screenshot](/screenshot.png)

### Links

- Solution URL: [My Solution](https://www.frontendmentor.io/solutions/social-proof-section-using-flexbox-and-css-grid-xzmum2SM2d)
- Live Site URL: [Github Pages](https://delanohendrix.github.io/Social-Proof-Section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I using grouping of similar content to allow the use of Css Grid when going from the mobile design to the desktop version.

Examples of this grouping are found below:

```html
<div class="accolade-container">
  <div class="accolade">
    <div class="rating">
      <img src="images/icon-star.svg" alt="" />
      <img src="images/icon-star.svg" alt="" />
      <img src="images/icon-star.svg" alt="" />
      <img src="images/icon-star.svg" alt="" />
      <img src="images/icon-star.svg" alt="" />
    </div>
    <p>Rated 5 Stars in Reviews</p>
  </div>
</div>
```

```html
<div class="review-container">
  <div class="review">
    <div class="reviewer">
      <img src="images/image-colton.jpg" alt="" />
      <p>
        Colton Smith <br />
        <span>Verified Buyer</span>
      </p>
    </div>
    <p>
      &ldquo; We needed the same printed design as the one we had ordered a week prior. Not only did
      they find the original order, but we also received it in time. Excellent! &rdquo;
    </p>
  </div>
</div>
```

### Useful resources

- [CSS Reference](https://cssreference.io/) - This site helped me by refreshing me on the usage of various css attributes and properties.

## Author

- Frontend Mentor - [@delanohendrix](https://www.frontendmentor.io/profile/delanohendrix)
