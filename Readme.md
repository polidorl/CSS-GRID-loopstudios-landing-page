# project : Loopstudios landing page solution

![Design preview for the Product preview card component coding challenge](./design/desktop-preview.jpg)

## Table of contents

- [Overview](#overview)
- [The challenge](#the-challenge)
- [Links](#links)
- [My process](#my-process)
- [Built with](#built-with)
- [What I learned](#what-i-learned)

## Overview
In this project, I developed a website from scratch applying the BEM (Block Element Modifier) ​​methodology. I also implemented transitions and animations in CSS, making extensive use of CSS Grid.
### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: [https://github.com/polidorl/CSS-GRID-loopstudios-landing-page](https://github.com/polidorl/CSS-GRID-loopstudios-landing-page.git)
- Live Site URL: [https://polidorl.github.io/CSS-GRID-loopstudios-landing-page.git/](https://polidorl.github.io/CSS-GRID-loopstudios-landing-page.git/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Implementation of Animations and transitions in CSS
- CSS Grid
- Mobile-first workflow
- Methodology BEM (Block Element Modifier)

### What I learned

This project allowed me to master advanced CSS Grid techniques, proving that it is possible to create complex layouts in an intuitive and scalable way. Thanks to pure CSS, I managed to develop a fully responsive interface that can be adapted to any device, from desktop to mobile. In addition, I incorporated CSS animations and transitions to enrich the user experience.
I learned about the use of the picture tag in html , seeing how images automatically adapt to the screen size, which is essential for responsive web design.


```html
<picture class="gallery__picture" data-message="Deep earth">

          <source srcset="./images/desktop/image-deep-earth.jpg" class="gallery__img" media="(min-width:768px)">

          <img src="./images/mobile/image-deep-earth.jpg" class="gallery__img" alt="imagen Deep earth">
</picture>
```
```css
.gallery {
        grid-template-columns: repeat(2, auto);
        grid-template-rows: repeat(2, auto);
        justify-content: space-between;
    }
    .gallery__cta {
        grid-column: 2/3;
        grid-row: 1/2;
    }
    .gallery__container {
        grid-column: 1/-1;
        grid-row: 2/3;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    }
```

## Author

- Website - [Add your name here](in/lisbeth-emperatriz-polidor-solano-139b70117)
- email - [@yourusername](polidor.lisbeth4@gmail.com)




