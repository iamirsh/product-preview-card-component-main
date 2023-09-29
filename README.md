# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Table of contents

- [Frontend Mentor - Product preview card component solution](#frontend-mentor---product-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
 - [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![product-prev-desktop-screen](https://github.com/iamirsh/product-preview-card-component-main/assets/46514596/9193132b-5cd1-40e7-a2b2-d97c2ddd1c80)
![product-prev-mobile-screen](https://github.com/iamirsh/product-preview-card-component-main/assets/46514596/53a1b269-a6cd-4d24-bc02-95cab0b2f097)


### Links

- Solution URL: [Solution](https://github.com/iamirsh/product-preview-card-component-main)
- Live Site URL: [Live](https://65153760d9594068c1999cec--aquamarine-panda-0361ce.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Visual Studio Code

### What I learned

Through this project, I've learned how to use the `srcset` attribute in HTML for responsive image handling. It enables web developers to provide multiple image options with different resolutions and sizes to cater to various devices and screen dimensions. By specifying various image sources and their widths in `srcset`, I can optimize image loading for different scenarios, enhancing the user experience across devices, from desktops to mobile.

```html
<img
	srcset="images/image-product-desktop.jpg 600w, images/image-product-mobile.jpg 686w"
	sizes="(max-width: 600px) 686px, 300px"
	src="images/image-product-desktop.jpg"
	alt="A bottle of perfume surrounded by foliage"
>
```

## Author

- Website - [Irshad Ahmad](https://github.com/iamirsh)
- Frontend Mentor - [@iamirsh](https://www.frontendmentor.io/profile/iamirsh)



