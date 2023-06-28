# Frontend Mentor - [Product preview card component.](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

<details>

<summary>Click to open</summary>

![Desktop](https://i.imgur.com/ZEdaSYi.png)
![Mobile](https://i.imgur.com/qxdI79n.png)

</details>

### Links

- Live Site URL: [Live](https://solracss.github.io/FrontendMentor-product-preview-card/)

## My process

### Built with

<div >
	<img width="30" src="https://user-images.githubusercontent.com/25181517/192108891-d86b6220-e232-423a-bf5f-90903e6887c3.png" alt="Visual Studio Code" title="Visual Studio Code"/>
	<img width="30" src="https://user-images.githubusercontent.com/25181517/192158954-f88b5814-d510-4564-b285-dff7d6400dad.png" alt="HTML" title="HTML"/>
	<img width="30" src="https://user-images.githubusercontent.com/25181517/192158956-48192682-23d5-4bfc-9dfb-6511ade346bc.png" alt="Sass" title="Sass"/>
	<img width="30" src="https://user-images.githubusercontent.com/25181517/183898674-75a4a1b1-f960-4ea9-abcb-637170a00a75.png" alt="CSS" title="CSS"/>
</div>

### What I learned

1. Use of `aria-labelledby` for defining accessible name for button.

```html
<h2 class="product-title">Gabrielle Essence Eau De Parfum</h2>
```

```html
<button class="add-to-cart-btn flex" aria-labelledby="add-to-cart-btn product-title">
	<img src="./images/icon-cart.svg" alt="" />Add to Cart
</button>
```

2. Mastering mobile first approach
