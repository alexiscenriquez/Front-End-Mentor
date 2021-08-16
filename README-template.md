# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
This project is an order summary card that is responsive for desktops and mobile devices.
### The challenge

Users should be able to:

See a color change while hovering over the Change, Payment and Cancel Buttons

### Screenshot

![](images/solution.png)

### Links

- Solution URL: [](https://github.com/alexiscenriquez/Order-Summary-Card)
- Live Site URL: [](https://alexiscenriquez.github.io/Order-Summary-Card/)

## My process

- The first thing I did was "Mark Up" the HTML file using divs, inputs, anchor  (a), paragraphs (p) and a header (h1) and added IDs on them.

- I added a pricing div with a flex display that holds the music icon, the Annual Plan  and Change Button.

- I also wrapped the "Annual Plan" and Price in a flex box div with a column direction so they would be stacked rather than beside each other.

- Next, I grouped the music icon and Annual Plan in a div, so that they would stay together on the left when I added the space between style to their wrapper div, this resulted in the change button being placed on the opposite end of the div.
 
- Then , I created a CSS File and custom variables for the colors I would be using and added all the IDS I would be styling and added the styles.

- I then added some transitions so that the buttons would change color on hover. I made the transition duration 0.1s so the change would appear smooth and not sudden and sharp. 

- Lastly I added a media query with the card's styling for screens less than 376px.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Media queries


### What I learned

My challenge with this project was responsiveness. I implemented the desktop design first and I noticed it was hard to get card to look as it should on different widths.  I quickly learned that it is best to use a mobile first approach to ensure that all users on any device have a seamless experience

### Continued development

Moving forward, I'd like to learn more about scaling components and responsiveness. I find that I change the lengths based on trial and error, which can take a lot of time. I want to be more sure of the widths I am using to waste less time and optimize speed performace.

## Author

- Website - [Alexis Enriquez](https://github.com/alexiscenriquez/))
- Frontend Mentor - [@alexiscenriquez](https://www.frontendmentor.io/profile/alexiscenriquez)
- Twitter - [@alexisceleste14](https://www.twitter.com/alexisceleste14)
