# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot
- Desktop view
![](screenshoots/desktop_view.png)

### Links

- Solution URL: [GitHub](https://github.com/EshrakRahman/Stats-preview-card-component)
- Live Site URL: [GitGub Page](https://eshrakrahman.github.io/Stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow


### What I learned

I recently completed a newbie challenge on FrontendMasters, diving deep into the world of CSS Flexbox. Before this, positioning items in dynamic layouts felt complex. Flexbox, however, transformed my approach, offering a streamlined method to align and distribute elements within a container. Through properties like justify-content, align-items, and flex-direction, I mastered the art of creating responsive and visually appealing designs. This wasn't just about grasping a theoretical concept; it was hands-on learning, giving me the confidence to tackle modern web design challenges with a fresh perspective.

To see how you can add code snippets, see below:

```html
      <div class="stats">
  <div class="stat-one">
    <p class="stat-num">
      10K+
    </p>
    <p class="stat-name">
      companies
    </p>
  </div>
  <div class="stat-two">
    <p class="stat-num">
      314
    </p>
    <p class="stat-name">
      templates
    </p>
  </div>
  <div class="stat-three">
    <p class="stat-num">
      12M+
    </p>
    <p class="stat-name">
      Queries
    </p>
  </div>
</div>

```
```css
.card .col-left .description {
  width: 90%;
  text-align: center;
  margin: 30px auto;
  line-height: 1.8rem;
}
.card .col-left .stats {
  flex-direction: column;
  justify-content: center;
  align-items: center;
  row-gap: 30px;
  width: 100%;
  padding: 0;
}
```

### Continued development

Having tackled FrontendMasters' challenge, I delved into CSS Flexbox, streamlining complex layouts with newfound mastery. Using pivotal properties, I now confidently craft responsive designs, a testament to my hands-on growth in modern web design. My continuous development highlights my resilience and adaptabilit


## Author

- Website - [GitHub](https://github.com/EshrakRahman)
- Frontend Mentor - [@eshrakrahman](https://www.frontendmentor.io/profile/eshrak_rahman)
- Twitter - [@rahman_eshrak](https://www.twitter.com/rahman_eshrak)


