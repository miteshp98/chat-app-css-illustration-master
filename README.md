# Frontend Mentor - Chat app CSS illustration solution

This is a solution to the [Chat app CSS illustration challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- **Bonus**: See the chat interface animate on the initial load

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

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

In completing this project, I gained hands-on experience with several key concepts and techniques including:

- **Before & After Pseudo-elements:** Utilized `::before` and `::after` pseudo-elements to add decorative elements and enhance the visual appeal of the chat app illustration.

- **Positioning:** Employed various positioning techniques such as absolute, relative, and fixed positioning to precisely place elements within the layout and create the desired visual effects.

- **CSS Grid:** Leveraged CSS Grid to create a flexible and responsive layout for the chat app interface. Grid allowed for easy alignment of elements and adaptation to different screen sizes.

- **Media Queries:** Implemented media queries to make the chat app illustration responsive across different devices and screen sizes. Adjusted layout, font sizes, and other styles to ensure optimal viewing experience on various devices.

- **Animation:** Incorporated CSS animations to add subtle movement and interactivity to certain elements of the illustration, enhancing the overall user experience and visual appeal.

```css
body::after {
  content: "";
  width: 550px;
  height: 80%;
  background: linear-gradient(
    180deg,
    hsla(293, 100%, 63%, 1) 0%,
    hsla(264, 100%, 61%, 1) 100%
  );
  position: absolute;
  z-index: -100;
  right: -150px;
  bottom: 0;
  border-radius: 0px 0px 300px 300px;
  transform: rotate(180deg);
  opacity: 0.05;
}
```

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Useful resources

- [Udemy Webdevlopment](https://www.udemy.com/share/101W9C3@2s1lShiGH32a3OJHMYullps9bvMmvxO_kykXK5ZGloqkGQDHawnryvbZtrMeQ8y81A==/)

## Author

- Website - [Mitesh Panchal](https://miteshp98.github.io/portfolio-website/)
- Frontend Mentor - [@miteshp98](https://www.frontendmentor.io/profile/miteshp98)
- Linkedin - [@Mitesh Panchal](https://www.linkedin.com/in/mitesh-panchal-356558126/)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

Thanks to the challenge provider for creating this opportunity to apply and improve my frontend development skills.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
