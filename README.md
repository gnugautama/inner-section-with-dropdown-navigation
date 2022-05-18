# Frontend Mentor - Intro section with dropdown navigation solution

This is a solution to the [Intro section with dropdown navigation challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/intro-section-with-dropdown-navigation-ryaPetHE5). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the relevant dropdown menus on desktop and mobile when interacting with the navigation links
- View the optimal layout for the content depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./images/Screenshot%20Intro%20section%20with%20dropdown%20navigation.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
- Bootstrap
- Mobile-first workflow

### What I learned

In this challenge I learned how to set different images for desktop and mobile. Here's how:

```html
<div class="hero-img col-lg-6 col-12 order-lg-1 order-0 ps-lg-5">
  <img src="./images/image-hero-desktop.png" alt="" class="desktop-img" />
  <img src="./images/image-hero-mobile.png" alt="" class="mobile-img img-fluid" />
</div>
```

```css
@media only screen and (max-width: 600px) {
  .hero-img .mobile-img {
    display: block;
  }
  .hero-img .desktop-img {
    display: none;
  }
```

### Continued development

I still cannot put the client logos aligned perfectly on their real size.

### Useful resources

- [Quora](https://www.quora.com/What-CSS-can-I-use-to-display-an-image-on-a-mobile-site-while-hiding-it-on-the-desktop-version) - This helped me for set the different images for mobile.
- [Bootstrap](https://getbootstrap.com/docs/5.0/utilities/flex/) - Bootstrap documentations to help set the layout.

## Author

- Website - [My Linktree](https://linktr.ee/agungutama)
- Frontend Mentor - [@gnugautama](https://www.frontendmentor.io/profile/gnugautama)
- Twitter - [@gnugautama](https://www.twitter.com/@gnugautama)

## Acknowledgments

Thanks to my coworkers, Reva, (again).
