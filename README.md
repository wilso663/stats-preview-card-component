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

![Full Screen screenshot](./images/ScreenShot.png)


### Links

- Solution URL: [https://github.com/wilso663/stats-preview-card-component](https://github.com/wilso663/stats-preview-card-component)
- Live Site URL: [https://musing-babbage-33fd3b.netlify.app/](https://musing-babbage-33fd3b.netlify.app/)

## My process

### Built with

- CSS Grid
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

The most helpful thing that I learned was the ease of use of grid layouts, particularly how to redefine it with media queries with minimal code. Using grid-template-areas like this:
```css
.card-container {
  grid-template-areas:
    "image" 
    "header"
    "description"
    "stats";
```
```css   
@media(min-width: 376px){
  .card-container{
    grid-template-areas:
      "header image"
      "description image"
      "stats image";
```
This made redefining the two required layouts very simple.

### Continued development

My biggest issue in developing this was the header and description text bleeding out of their grid containers which became increasingly difficult to manage on each new screen size and horizontal/vertical orientation that I tried. 

How can I get a font system that works with most phone screen sizes and both orientations so that the font size is also responsive and doesn't break the layout? This is what I'd like to look into next.

### Useful resources

- [Grid Critters](https://mastery.games/gridcritters/) - This educational game helped me understand and reinforce fundamental knowledge of css grid. I felt like I finally understood how to use grid on a deep level after going this all of the exercises. 

## Author

- Website - [Stephen Wilson](https://github.com/wilso663)
- Frontend Mentor - [@wilso663](https://www.frontendmentor.io/profile/wilso663)


