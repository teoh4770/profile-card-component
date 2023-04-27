# Frontend Mentor - Profile card component

<img width="420" alt="Screenshot 2023-04-27 at 1 59 48 AM" src="https://user-images.githubusercontent.com/98545971/234772624-42533ed4-a3d4-49c2-a31f-ee518c4a9df9.png">

# Frontend Mentor - Profile card component solution

## Table of contents

- [Overview](#overview)
  - [Links](#links)
  - [Code](#code)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Attribute](#attribute)

## Overview

### Links
- [Click the link here](https://teoh4770.github.io/profile-card-component/)

### Code	
CSS

	.card__avatar-container:hover ~ .hover--on {
	  display: none;
	}

	.card__avatar-container:hover ~ .hover--off {
	  display: block;
	}


## My process

### Built with

- Semantic HTML5 markup
- BEM
- Grid
- Custom Hover State
- Custom Design
- Responsive Design

### What I learned

- Learn to use BEM to structure my code, way way better
- Using sibling combinator ~ to make CSS change
- Using content to change the image within the img tag

### Useful resources

- [BEM 101](https://sparkbox.com/foundry/bem_by_example) - BEM 101
- [Affect another element on hover CSS](https://simplernerd.com/css-affect-another-element-on-hover/) - Affect another element on hover CSS
- [Change image of img tag in CSS: content](https://developer.mozilla.org/en-US/docs/Web/CSS/content) - Using the content CSS property, and replace the img with a new url
- [Affect other element on hover in CSS](https://logfetch.com/css-affect-another-element-on-hover/)

## Attribute

Thanks Lucas @correlucas from frontend mentor for the inspiration and code to review
