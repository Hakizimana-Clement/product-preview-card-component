# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size.
- See hover and focus states for interactive elements.

### Links

- Live Site URL: [Github](https://hakizimana-clement.github.io/product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid and flexbox
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

-To use grid to center the page content.

```css
body {
  height: 100%;
  display: grid;
  place-content: center;
  min-height: 100vh;
}
```

-To use HTML picture element(srcset attribute)to switch image at certain minimum or maximum.

```html
<picture>
  <source srcset="images/image-product-desktop.jpg" media="(min-width:600px)" />

  <img
    src="images/image-product-mobile.jpg"
    alt="Gabrielle Essence Eau De Parfum"
  />
</picture>
```

### Continued development

I still have to keeping learning CSS for better practices.

### Useful resources

- [The HTML picture element explained](https://www.youtube.com/watch?v=Rik3gHT24AM) - This helped me to know how to use HTML picture element for switching images at the specified screen size.

## Author

- Website - [Hakizimana-Clement](https://github.com/Hakizimana-Clement)
- Frontend Mentor - [@HAKIZIMANA CLEMENT](https://www.frontendmentor.io/profile/Hakizimana-Clement)
- Twitter - [@HakizimanaClem5](https://www.twitter.com/@HakizimanaClem5)

## Acknowledgments

- [Kevin Powell](https://twitter.com/KevinJPowell?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor)
