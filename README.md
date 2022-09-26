# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

Product Preview Card Component is another exciting HTML & CSS component with a beautiful mockup and responsive fill on all media screen sizes as inspired and instructed by Frontend Mentor.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/Screenshot%20Desktop%20-%20Frontend%20Mentor%20Product%20preview%20card%20component.png)
![](./images/Screen%20Shot%20Mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

- I began building the perfume-product-component by downloading the starter files and editing the index file through using semantic tags to display the code correctly and also improve accesibilty and SEO.

- Using an external CSS file I managed to style the product component as close to the figma design as possible and used flexbox to layout the product content side by side.

- For the product card responsive design I used Flexbox to display the card in a column layout and to ensure the browser displays the right product image for the corresponding media screen size, I used CSS and in my markup I declared two images and with the help of CSS I manupilated the images using their classes by displaing one and hiding the other at different screen sizes.

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox

### What I learned

- With some little research I managed to overcome the issue of setting border radius to a div containing an image and the image covers the div making the output appear as if the border radius didn't apply.

- You have to declare the boder radius property to both the parent container and to the image

```html
<div class="product__image">
  <img
    src="/images/image-product-desktop.jpg"
    alt="product image"
    class="product__img product__img--desktop"
  />
</div>
```

```css
.product__image {
  /* width: 50%;
  height: 100%; */
  border-radius: 1rem;
}

.product__img {
  /* width: 100%;
  height: 100%;
  object-fit: contain; */
  border-radius: 1rem 0 0 1rem;
}
```

### Continued development

- Responsive Images

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)
