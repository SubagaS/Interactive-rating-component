# Frontend Mentor - Interactive rating component solution

This is a solution to the [Interactive rating component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Select and submit a number rating
- See the "Thank you" card state after submitting a rating

### Screenshot

![](./images/Frontend%20Mentor%20-%20Interactive%20rating%20component.jpg)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/responsive-page-for-interactive-rating-component-7Mj-z-2n08]
- Live Site URL: [https://subagas.github.io/interactive-rating-component/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- JavaScript
- Mobile-first workflow


### What I learned
#### HTML

```html
<input type="radio" name="radio" id="radio1" value="1" />
```
I learnt about various attributes provided for form, input tags, fieldsets and label.
#### CSS

```css
.rating-container {
  background: radial-gradient(
    98.96% 98.96% at 50% 0%,
    #232a34 0%,
    #181e27 100%
  );}
```
I learnt about `radial-gradient` property in CSS. I played with the positioning values to get the desired background.
#### JS


```js
e.preventDefault();
```
I made use of `preventDefault()` method. It stopped the page from reloading whenever the form was submitted.

### Continued development

I want to get get better at working with forms in general.

### Useful resources

- [https://www.w3schools.com/css/css3_gradients_radial.asp](https://www.example.com) - This helped me in implementing `radial-gradient` in CSS. 

## Author

- Frontend Mentor - [https://www.frontendmentor.io/profile/SubagaS]
- LinkedIn - [https://www.linkedin.com/in/subaga/]