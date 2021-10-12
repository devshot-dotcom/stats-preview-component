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

![Mobile View](./images/screenshots/mobile.png)
![Desktop View](./images/screenshots/desktop.png)

### Links

- Solution URL: [Github Repository](https://github.com/devshot-dotcom/stats-preview-component)
- Live Site URL: [devshot-dotcom.github.io/stats-preview-component](https://devshot-dotcom.github.io/stats-preview-component/)

## My process

To be very honest, this was a simple yet creative process. The OG project is somewhat gorgeous but there is something missing, sadly I couldn't figure it out. Something is off from this design, maybe the background?

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

It was all about CSS Grid. I was kind of hesitant to the usage to Grid-Model to generate layouts but now I'm pretty confident as it's one of the most superficient ways to generate layouts in CSS.

For illustration, this is how easy it is to center everything within a Grid-Model:

```css
.grid {
  display: grid;
  place-items: center;
}
```

This is how easy it is to generate two equal columns.

```css
.grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
}
```

Same goes for the rows.

```css
.grid {
  display: grid;
  grid-template-rows: 1fr 1fr;
}
```

### Continued development

I would like to use a javascript framework, most likely react. I'm very steady with Angular but React seems to be the trend today so...

## Author

Kashan Ahmad from devshot-dotcom.

- Website - [devshot-dotcom](https://devshot-dotcom.github.io)
- Frontend Mentor - [@devshot-dotcom](https://www.frontendmentor.io/profile/devshot-dotcom)
- Instagram - [@devshotdotcom](https://www.instagram.com/devshotdotcom/)
- YouTube - [Devshot](https://www.youtube.com/channel/UCYCAUsfy9JybOT-DvdTV_sA)
- Medium - [devshot-coffee@medium](https://devshot-coffee.medium.com/)
- HashNode - [@devshot](https://hashnode.com/@devshot)
