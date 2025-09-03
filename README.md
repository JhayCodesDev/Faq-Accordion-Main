# Frontend Mentor - FAQ accordion solution

This is a solution to the [FAQ accordion challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-wyfFdeBwBz). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
The goal of this challenge was to build a clean and accessible FAQ accordion that allows users to expand and collapse answers in a visually appealing and user-friendly way.

It was a great opportunity to practice semantic HTML, CSS for interactive components, and responsive design for small UI elements. By completing it, I improved my ability to translate a given design into code while keeping the structure maintainable, readable, and accessible across different devices.

### Screenshot
![screenshot for desktop](./Screenshot%202025-09-03%20at%2004-30-48%20Frontend%20Mentor%20FAQ%20accordion.png)
![screenshot for mobile](./Screenshot%202025-09-03%20at%2004-34-47%20Frontend%20Mentor%20FAQ%20accordion.png)
![screenshot for active state](./Screenshot%202025-09-03%20at%2004-36-10%20Frontend%20Mentor%20FAQ%20accordion.png)

### Links
- Live Site URL: [View live site here](https://JhayCodesDev.github.io/Faq-Accordion-Main/)

## My process
1. Setup

Downloaded the starter files and extracted them into a new project folder named faq-accordion-main.
Reviewed the provided design mockups and instructions to understand the project requirements and layout.

2. Structure

Built the HTML structure using semantic tags:

A header with a nested <div> to allow a background image while giving the body its own background color.

A #container div that holds the main content:

Divs containing an h1 tag and an image

<details> and <summary> tags for the FAQ accordion (first time using these, which was a great learning experience)

A div with #attribution for credits and links at the bottom of the page

This structure allowed for clear separation of content and easy styling.

3. Styling

Added base styles for the body, headings, and containers.

Styled the header to display a background image properly while keeping the body background separate.

Applied styles to the accordion, including hover states, spacing between FAQ items, and smooth transitions for interactivity.

Styled the attribution section to match the overall design.

4. Responsiveness

Used a desktop-first approach, designing for larger screens first.

Applied media queries for smaller devices (320px–400px) to adjust widths, font sizes, and spacing.

Ensured the accordion, hover effects, and overall content remained fully readable and visually appealing on mobile devices.

### Built with

- Semantic HTML5 markup (header, div, details, summary)

- CSS custom properties and Flexbox for layout and alignment

- Container-based structure for content organization (#container and nested divs)

- Desktop-first workflow with media queries for smaller screens

- Responsive design techniques and interactive hover/accordion states

### What I learned
I learned how to create a functional accordion using the <details> and <summary> elements, which was different from the Bootstrap 5 accordion I was previously familiar with that requires a structured combination of <div class="accordion">, .accordion-item, .accordion-header, and collapse classes with JavaScript to toggle the content.

### Useful resources

-[ MDN Web Docs ]– <details>
Comprehensive documentation and examples of <details> and <summary>(https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details)

[CSS-Tricks] – Building a Pure CSS Accordion
Guide on creating collapsible accordions with CSS only(https://css-tricks.com/pure-css-accordion/)

## Author

- Website - [@JhayCodesDev](https://github.com/JhayCodesDev)
- Frontend Mentor - [@yJhayCodesDev](https://www.frontendmentor.io/profile/JhayCodesDev)
- Twitter - [@JhayCodes](https://www.twitter.com/JhayCodes)

## Acknowledgments
Thanks to Frontend Mentor for providing such practical and challenging projects.

Grateful to resources like MDN Web Docs and CSS-Tricks, which continue to be invaluable references.
