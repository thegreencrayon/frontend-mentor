# Frontend Mentor - FAQ accordion solution

This is a solution to the [FAQ accordion challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-wyfFdeBwBz). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- Hide/Show the answer to a question when the question is clicked
- Navigate the questions and hide/show answers using keyboard navigation alone
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:
```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.proud-of-this-css {
  color: papayawhip;
}
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```
1. accordian toggle using <details> <summary> <p> <details>
2. best formatting order is (1) font (2) page background (3) card classes (4) icons (5) text colors and weights
3. how to insert google font by copy & pasting code to html <head> then actually using it in css font-family
4. min-height: 100vh = "make this element at least as tall as the screen"
5. background-color in css for body color
6. background-image in css for image stacked ontop of background color
7. background-size: 100% - "make image exactly as wide as the screen"
8. background-position ctrls position of image
9. flexbox lays out elements children, not the element itself
10. in flexbox, justify-content centers left & right
11. in flexbox, alight-items centers top & bottom
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

I would like to (1) add last progress note (2) edit progress notes (3) test mobile and desktop (4) upload to git


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
