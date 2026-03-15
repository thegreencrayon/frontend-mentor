# Frontend Mentor - FAQ accordion solution

This is a solution to the [FAQ accordion challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-wyfFdeBwBz). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## My process
I used cursor AI to guide me to next steps. I wrote out all the improvements I wanted to make and it helped me decide order in terms of which file to edit first (html/css) or which task to do.

### Built with

- Semantic HTML5 markup
- Flexbox

### What I learned

1. accordian toggle using <details> <summary> <p> <details>
2. best formatting order is (1) font (2) page background (3) card classes (4) icons (5) text colors and weights
3. how to insert google font by copy & pasting code to html <head> then actually using it in css font-family
4. min-height: 100vh = "make this element at least as tall as the screen"
5. background-color in css for body color
6. background-image in css for image stacked ontop of background color
7. background-size: 100% - "make image exactly as wide as the screen"
8. background-position ctrls position of image
9. flexbox lays out element's children, not the element itself
10. in flexbox, justify-content centers left & right
11. in flexbox, align-items centers top & bottom
12. main flexbox job is for positioning, NOT for sizing
13. rounded edges achieved through border-radius: ![](./assets/images/progress-images/faq-box.png)
14. gap = works on a container, and it adds space between its children ![](./assets/images/progress-images/faq-header.png)
15. justify-content: space-between = "push the first child to the start, last child to the end, and spread any leftover space between them"
16. summary::after is a pseudo-element so by default it is basically a 0x0 invisible box ![](./assets/images/progress-images/plus-minus-icons.png)
17. "color" for text color: ![](./assets/images/progress-images/text-color.png)
18. line-height: 1.5 = double spacing!
19. padding = all four, padding-block = top & bottom ![](./assets/images/progress-images/faq-spacing.png)
20. Responsive design mode: Safari -> Develop -> Adopt Responsive Design Mode ![](./assets/images/progress-images/original-mobile-view.png)
21. flex-shrink: 0 for ::after = makes it so that invisible element cannot deviate from set dimensions, no shrink
22. margin = creates empty space between faq and background
23. @media to do mobile version ![](./assets/images/progress-images/final-mobile-view.png)


### Continued development

In future projects I would like to work on mobile first development before customizing it to desktop. I would like to experiment on different types of web design formats to see what is possible.

### Useful resources

- cursor - This helped me for syntax and guiding my next steps. 
- Apple Responsive Design Mode - This developer tool helped me live test the mobile version since I only program with my laptop. 

## Author

Patricia Mae Santos

## Acknowledgments

I would like to thank front end mentor for providing the assets for this project. I would also like to thank the creator of this challenge for making such a helpful guide to base the AI agent on.
