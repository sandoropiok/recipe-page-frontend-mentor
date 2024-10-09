# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

The challenge was to build a responsive recipe page based on a given design reference. The main objectives included creating a visually appealing and functional recipe page that adapts seamlessly to different screen sizes, ensuring a great user experience on both desktop and mobile devices.

### Links

- Solution URL: [GitHub Repository](https://github.com/yousifpa98/recipe-page-solution)
- Live Site URL: [Live Demo](https://yousifpa98.github.io/FE_recipe-page-main/)

## My process

### Built with

- Semantic HTML5 
- CSS custom properties
- Flexbox
- Mobile-first 

### What I learned

During this project, I honed my skills in responsive web design, particularly focusing on how to use CSS media queries effectively to ensure that the layout works well on both desktop and mobile devices. Here are some specific things I learned:

1. **Responsive Images**: Ensuring that images scale properly across different screen sizes.
2. **Mobile-first Approach**: Starting the design with mobile screens and then enhancing it for larger screens.
3. **Flexbox**: Using Flexbox to create flexible and adaptive layouts.

Some of the key snippets of my code include:

HTML:
```html
<section class="recipe">
  <div class="recipe-container">
    <img src="assets/images/image-omelette.jpeg" alt="omelette" />
    <h1>Simple Omelette Recipe</h1>
    <p>An easy and quick dish, perfect for any meal. This classic omelette combines beaten eggs cooked to perfection, optionally filled with your choice of cheese, vegetables, or meats.</p>
  </div>
</section>
```
CSS:
```css
@media (max-width: 480px) {
  body,
  .recipe,
  .recipe-container {
    margin: 0;
    padding: 0;
    width: 100%;
    height: 100%;
    display: block;
    border-radius: 0;
    box-shadow: none;
  }

  .recipe {
    padding-top: 0;
  }

  .recipe-container {
    padding: 0;
  }

  .recipe img {
    width: 100%;
    height: auto;
    border-radius: 0;
  }

  .recipe-container h1 {
    font-size: 34px;
    margin: 30px;
  }
  .prep-time,
  .recipe-container p {
    font-size: 16px;
    margin: 30px;
  }

  .prep-time h3 {
    font-size: 20px;
  }

  h2 {
    font-size: 24px;
    margin: 20px;
  }
  .ingredients li {
    font-size: 16px;
  }
  .ingredients,
  .instructions {
    margin: 20px;
  }

  .nutrition p,
  .nutrition h2 {
    margin: 30px;
  }

  .nutrition table {
    margin-left: 30px;
  }
}
```


### Useful resources

- [MDN Web Docs - Responsive Design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design) - This article provided a comprehensive overview of responsive design principles.
- [CSS-Tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This guide was instrumental in understanding Flexbox and applying it effectively in the project.

## Author


- Frontend Mentor - [@sandoropiok](https://www.frontendmentor.io/profile/sandoropiok)
- GitHub - [@sandoropiok](https://github.com/sandoropiok)