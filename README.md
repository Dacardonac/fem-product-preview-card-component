# Frontend Mentor - Product preview card component solution

This is a solution to the **[Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa)** by **[Dacardonac](https://github.com/Dacardonac)**. Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

## Overview

### The challenge

**Users should be able to in this project:**

- View the optimal layout depending on their device's screen size (Responsive)
- See hover and focus states for interactive elements

### Screenshot

![Solution Screenshot](./public/design/Screenshot.webp)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 Markup
- CSS3 Custom Properties
- Flexbox
- Mobile-first Workflow
- [Vite](https://vitejs.dev/) - Frontend Tooling
- [Sass/Scss](https://sass-lang.com/) - Modules

### What I learned

I learned a lot about responsive design and its breakpoints, and I practiced the BEM methodology and modularized styles in components using Sass.

You can see part of the class names with BEM and breakpoints in SCSS below:

```html

  <!--Classes with BEM-->

    <article class="card__content">
        <p class="card__category">Perfume</p>
        <h1 class="card__title">Gabrielle Essence Eau De Parfum</h1>
        <p class="card__description">
          A floral, solar and voluptuous interpretation composed by Olivier
          Polge, Perfumer-Creator for the House of CHANEL.
        </p>

        <p class="card__prices">
          <span class="card__price--new">$149.99</span>
          <span class="card__price--old">$169.99</span>
        </p>
        <button class="card__button">
          <img src="./assets/images/icon-cart.svg" alt="Shopping cart icon" class="card__icon" />
          <span class="card__button-text">Add to Cart</span>
        </button>
    </article>
```
```css

/*Breakpoint 1440px*/

@media (min-width: 90rem) {
  .card {
    max-width: 37.5rem;
    display: flex;

    &__image {
      max-width: 18.75rem;
      height: 100%;
      border-radius: 0.625rem 0 0 0.625rem;
      object-fit: cover;
    }

    &__content {
      padding: 2rem 2rem 0 2rem;
    }

    &__title {
      margin: 1.25rem 0 1.5rem 0;
    }

    &__button {
      margin-top: 1.875rem;
      padding: 0.938rem 3.875rem;
    }
  }
}
```

### Continued development

With this path, I want to continue learning more about **Responsive Design** and how to work across different devices, **BEM methodology** and perfect the technique in aspects like name the classes, also I want to improve in modularize the component's styles with **Sass** and learn about **Conventional Commits**.

### Useful resources

- **[MDN](https://developer.mozilla.org/en-US/)** - This helped me with **Documentation** on many topics, mostly with **HTML** and **CSS** properties.
- **[ChatGPT](https://chatgpt.com/)** - This is an incredible **Artificial Intelligence (AI)** tool, **ChatGPT** helps me with **specific topics**, **errors in the project** and **investigations**.

## Author

- Frontend Mentor - **[@Dacardonac](https://www.frontendmentor.io/profile/Dacardonac)**
- LinkedIn - **[@Daniel Alejandro Cano Cardona](https://www.linkedin.com/in/daniel-alejandro-cano-cardona/)**


## Acknowledgments

I want to thank **[Jairovg](https://github.com/jairovg)** for the teachings and his help to complete this challenge in a good way and with good practices.