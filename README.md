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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Solution URL](https://www.frontendmentor.io/solutions/stats-preview-card-using-sass-and-flexbox-bgJNFQ2I2)
- Live Site URL: [Live Site URL](https://cccaitlinmae-stats-preview-card.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- SASS
- Mobile-first workflow

### What I learned

I learned more of SASS (although there's still so much more with it to play around). Also, I applied neat naming conventions which is BEM [block, element, modifier] naming convention for my classes. Also, working on mobile-first workflow really makes the build of the component much easier.

1.) Use of BEM

```html
<div class="card">Card</div>
  <div class="card__content">
    <h1>Heading</h1>
    <p>Some paragraph.</p>
  </div>
  <div class="card__image">
    <img src="/image.jpg" alt="image">
  </div>
</div>
```

2.) Use of a block element: The div surrounding the image became quite a problem for me while working on this component since the container is larger than the image. So, to solve that, convert image to a block element

```css
vertical-align: top;
/*or you can simply use */
display: block;
```

2.) Use of filter property: I came across the use of filters which is helpful for images and backgrounds. Although, I still struggled to make the violet overlay pixel perfect just like from the picture.

```css
filter: contrast(200%);
```

### Continued development

I would continue to use BEM, SASS and mobile first workflow in my future projects. I would definitely apply this code if I would ever encounter it again.

### Useful resources

- [StackOverflow](https://stackoverflow.com/questions/11447707/div-container-larger-than-image-inside) - This forum helped me solve one of my major problems for this project.
- [BEM CSS Naming](https://sparkbox.com/foundry/bem_by_example) - I first heard about this while I was on my Front End internship last year. And I decided to apply it in my own work.
- [filter](https://developer.mozilla.org/en-US/docs/Web/CSS/filter) - Mozilla's helpful documentations on filter property

## Author

- Frontend Mentor - [@cccaitlinmae](https://www.frontendmentor.io/profile/cccaitlinmae)
- Github - [@cccaitlinmae](https://github.com/cccaitlinmae)
