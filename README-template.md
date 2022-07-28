# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Analysis](#analysis)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Project on GitHub](https://github.com/joanFaseDev/hudle-landing-page)
- Live Site URL: [Project hosted through Vercel](https://hudle-landing-page-ten.vercel.app/)

## My process

### Analysis

- There's two designs for this project, mobile and desktop, so we need to make the page responsive.

- Use a _main_ element as a global container then nest a _div_ inside with a _width_ in percentage, that way no padding is needed.

- Then create two _section_ element, each with a _h2_ heading. The first will contain the Huddle part with the illustration. The second will contain the community part with the link and social medias logos.

- The Register button is used as a link so we need an _a_ element with lots of styling (also there's an active part to style).

- We'll probably use CSS Grid on the desktop design, two columns will do for a nice layout.

- The image's background change between the mobile design and the desktop one. Maybe use _picture_ and _source_ elements to change the image through media queries.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

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
  console.log("🎉");
};
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Font Awesome - Bordered & Pulled Icons](https://fontawesome.com/docs/web/style/pull) - This helped me set up a proper border for the social media's icons.
- [Font Awesome - Customizing Icons](https://fontawesome.com/docs/web/style/custom) - This helped me using CSS custom properties targeting specifically the social media's icons
- [Easings.net](https://easings.net/) - A cool website i often used to copy/paste easing functions. Works wonder with the CSS _transition_ property (specifically for the property _transition-timing-function_)

## Author

- Frontend Mentor - [@joanFaseDev](https://www.frontendmentor.io/profile/joanFaseDev)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
