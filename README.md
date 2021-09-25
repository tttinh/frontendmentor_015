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

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- **Bonus**: See the chat interface animate on the initial load

### Links

- [Solution URL](https://www.frontendmentor.io/solutions/chat-app-css-v2lii9CW-)
- [Live Site URL](https://tttinh.github.io/frontendmentor_015/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Using clip-path attribute to create shapes. Very useful!

```css
.chevron-left::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: white;
  clip-path: polygon(100% 0%, 50% 50%, 100% 100%, 80% 100%, 30% 50%, 80% 0%);
}
```

### Useful resources

- [CSS clip-path maker](https://bennettfeely.com/clippy/) - This helped me for creating clip-path.

## Author

- Frontend Mentor - [@tttinh](https://www.frontendmentor.io/profile/tttinh)
