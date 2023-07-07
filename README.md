# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

 This challenge is from Frontendmentor.io. The challenge is to build a QR code component using my knowledge of HTML and CSS, 
 The goal is to get my design to look as close to the design provided whilst making my component responsive on desktop and mobile. 

### Screenshot

![QR-Code-Component](./content/finished-project/Frontend%20Mentor%20QR%20code%20component.png)

### Links

- Solution URL: (https://burty197.github.io/Frontend-Mentor-Challenge-QR-Code-Component/)
- Live Site URL: ()

## My process

- Github Repo created with a local repository which included a template project from Frontend Mentor QR-Code Component challenge.
- HTMl 5 Markup added with metadata information plus links setup to stylesheet and favicon.
- Div classes Container and Card created to add style rules later on, whilst QR-Image was added and card content was given the attributes tag h1, p 
- A Footer was created to add a hyperlinks for my GitHub project and the QR-Code component challenge on Frontend mentor.io
- Stylesheet created,   
- The main goal was to get the QR card component to be in the center of the page. so the solution I did for this was to assign the container flex properties to center the card.
- After the card was centered the next thing to do was create css attributes for the image of the qr code to fit within the card by assigning a max-width:100% to scale with the card.
- Text was assigned font-sizes and a font-weight to resemble the look of the design given.
- Padding was added to the text and QR img to keep content spaced out whilst also adding a margin on the container to keep the card component more responsive on mobile devices.

### Built with

- HTML5 
- CSS
- Flex 

### What I learned

The languages used for this challenge were HTML5 and CSS, For creating the QR Code component I used a CSS method called flex/flexbox property, which allows me to use a flexible box layout that is easier for designing and positioning elements for more of a responsive layout. 

### HTML
```html
  <main>
    <div class="container">
      <div class="card">
        <img id="qr_img" src="/content/images/image-qr-code.png" alt="QR_Code link for frontendmentor.io" width="360px"
          height="360px">
        <h1>Improve your front-end skills by building projects</h1>
        <p>Scan the QR code to visit Frontend <br> Mentor and take your coding skills to<br> the next level</p>
      </div>
    </div>
  </main>
```
- The Container Class is the main div for the card component, its purpose is to position and center the card on the page. 
- Card class contains all of the qr content such as the image and text, styles will be applied such as the color and card design.
- img id ="qr_img" contains the qr-code and also has the width and height properties added as they will be applied to the image first before the style is applied in the stylesheet.css.
- Text provided was placed in h1 and p tag.

### CSS Flexbox model
```css - flexbox
.container{
     min-height: 100vh;
    display: flex;
    flex-shrink: 1;
    flex-grow: 0;
    flex-wrap: nowrap;
    align-items: center;
    justify-content: center;
    text-align: center;
    margin: 1rem;
    scale: 80%;
}
```
- The code snippet above shows my div container having a display:flex with using flex i have learnt how properties interact with each other when postioning my QR code component.
- The min-height for the container is 100vh, vh = view height so for the value 100vh this tells the browser how much of the container should on the screen. 
- flex-shrink and flex-grow property shrinks and grows the flex item to fit acorrding to the flex container properties.
- flex-wrap set at nowrap so flex items do not wrap on to other items.
- align-items and justify-content set to centre so content will be centered in the middle of the browser. 
- text-align center the text in the container on the card.
- margin:1rem applied to container giving 1rem of space on each side of the container. 
- scale:80%, changed the size of the element by scaling it down to 80%

### Continued development

For my continued development i will be refining my knowledge with concepts such as flexbox and also looking into learning css grid for making more responsive projects in the future. 

### Useful resources

- [Example resource 1](https://www.w3schools.com/css/css3_flexbox.asp) - W3schools example  and explaination on how to use flexbox with css
- [Example resource 2](https://www.w3schools.com/howto/howto_css_cards.asp) - W3schools examples of making a card using css 

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@burty197](https://www.frontendmentor.io/profile/burty197)