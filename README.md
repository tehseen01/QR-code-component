# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#Build-with)
  - [Useful resources](#useful-resources)
- [Check it out](#check-it-out)

## Overview

### Links

- Solution URL: [Add solution URL here](https://github.com/tehseen01/QR-code-component.git)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

```html

<section>
  <article class="container">
    <img src="/image-qr-code.png" alt="QR-code-image" />
    <h1>Improve your front-end skills by building projects</h1>
    <p>
      Scan the QR code to visit Frontend Mentor and take your coding skills to
      the next level
    </p>
  </article>
</section>
```

```css

body {
  background-color: hsl(212, 45%, 89%);
  font-family: "Outfit", sans-serif;
}
section {
  background-color: hsl(0, 0%, 100%);
  position: absolute;
  top: 50%;
  left: 50%;
  translate: -50% -50%;
  border-radius: 15px;
  padding: 0.8rem;
  width: 16rem;
}
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}
img {
  width: 16rem;
  border-radius: 12px;
}
h1 {
  color: hsl(218, 44%, 22%);
  font-weight: 700;
  margin-bottom: 0;
  font-size: 22px;
}
p {
  color: hsl(220, 15%, 55%);
  font-weight: 400;
  font-size: 15px;
}
```

### Useful resources

- [Font that was used](https://fonts.google.com/specimen/Outfit#styles)

- [How to submit solution on frontend](https://medium.com/frontend-mentor/a-complete-guide-to-submitting-solutions-on-frontend-mentor-ac6384162248) - This helped me for uploading my project on front end mentor. I really liked this pattern and will use it going forward.

## Check it out

- Github - [mohd tehseen](https://github.com/tehseen01)
- Frontend Mentor - [@tehseen01](https://www.frontendmentor.io/profile/tehseen01)
