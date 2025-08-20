# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Table of contents

- [Frontend Mentor - Product preview card component solution](#frontend-mentor---product-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshots](#screenshots)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshots

![](screenshots/active.png)
![](screenshots/desktop.png)
![](screenshots/mobile.png)


### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/product-preview-card-component-ARdsjM7WzX)
- Live Site URL: [Live Preview](https://poseidon0211-hub.github.io/product-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Visual Studio Code

### What I learned

- The picture tag is used in HTML to show different images depending on the screen size of the device.
This helps my website look better on all devices and also makes it load faster on phones by using smaller images.

```html
<picture>
      <source srcset="./images/image-product-desktop.jpg" media="(min-width: 600px)">
      <img src="./images/image-product-mobile.jpg" alt="Perfume image" class="product-image">
    </picture>
```

### Continued development

- Still need more development in Media queries 


### Useful resources

- [Complete guide to Flexbox ](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)- Great reference for Flexbox
- [Responsive Images: Reference Guide ](https://imagekit.io/responsive-images/)- Extremely comprehensive guide to respomsive images
- [CSS Media Queries ](https://css-tricks.com/a-complete-guide-to-css-media-queries/)- Extremely guide to media queries


## Author

- Frontend Mentor - [@poseidon0211-hub](https://www.frontendmentor.io/profile/poseidon0211-hub)


## Acknowledgments

- I am deeply grateful to Mr. Albert for his dedicated support and encouragement throughout my learning journey in HTML and CSS. His clear explanations and practical advice were especially helpful in completing the Product Component project. His mentorship made a significant impact on my understanding and confidence in front-end development.
