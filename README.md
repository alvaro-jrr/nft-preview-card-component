# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - NFT preview card component solution](#frontend-mentor---nft-preview-card-component-solution)
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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

-   View the optimal layout depending on their device's screen size
-   See hover states for interactive elements

### Screenshot

![Screenshot of Page](./screenshot.png)

### Links

-   Solution URL: [https://github.com/alvaro-jrr/nft-preview-card-component](https://github.com/alvaro-jrr/nft-preview-card-component)
-   Live Site URL: [https://nft-preview-card-component-sigma.vercel.app/](https://nft-preview-card-component-sigma.vercel.app/)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid

### What I learned

I'm proud of this HTML and CSS code, because it shows the eye icon when the element is hovered.

```html
<a class="preview-img-container" href="#">
	<div class="view">
		<img src="./images/icon-view.svg" alt="Eye icon" />
	</div>

	<img
		class="preview-img"
		src="./images/image-equilibrium.jpg"
		alt="Equilibrium"
	/>
</a>
```

```css
.view {
	opacity: 0;
	position: absolute;
	width: 100%;
	height: 100%;
	display: grid;
	place-items: center;
}

.view:hover {
	opacity: 1;
	background: var(--transparent-cyan);
}
```

### Continued development

I would like to keep improving in responsive design, making the elements resize and change as needed due the current viewport size.

### Useful resources

-   [Josh's Custom CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/) - This helped me reset my CSS and gave me more knowledge due the way it works.

## Author

-   Website - [Alvaro Resplandor](https://github.com/alvaro-jrr)
-   Frontend Mentor - [@alvaro-jrr](https://www.frontendmentor.io/profile/alvaro-jrr)
