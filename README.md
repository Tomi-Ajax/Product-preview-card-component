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
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot
![image](https://user-images.githubusercontent.com/111189639/187002255-87ae974b-c8d3-4d1a-af61-f606b28bef45.png)

![](./screenshot.jpg)
### Links

- Solution URL: [github repo](https://github.com/Tomi-Ajax/Product-preview-card-component)
- Live Site URL: [Preview site](https://tomi-ajax.github.io/Product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learnt HTML picture tag element which allows one to display different pictures for different devices or screen sizes. I also learnt how to add google font to my html code. 


```html
<picture>
        <source media="(min-width: 48em)" srcset="images/image-product-desktop.jpg" class="desktop-image">
        <img src="images/image-product-mobile.jpg" class="image">
</picture>

<link rel="icon" type="image/png" sizes="32x32" href="images/favicon-32x32.png" />
  <link rel="stylesheet" href="stylesheet/styles.css" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link
    href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,700&family=Montserrat:wght@500;700&display=swap"
    rel="stylesheet">
```

## Author

- Frontend Mentor - [Tomi-Ajax](https://www.frontendmentor.io/profile/Tomi-Ajax)
- Twitter - [Tomi-Ajax](https://www.twitter.com/ajaxifeoluwa)

## Acknowledgments

I would like to say thanks to my amazing friend [@kushyzee](https://github.com/kushyzee) for his constant advice, I also got inspired from his own solution of this projects.

