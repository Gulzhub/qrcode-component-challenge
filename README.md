# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Connect](#connect)


## Overview


### Links

- Solution URL: [Solution URL](https://github.com/Gulzhub/qrcode-component-challenge)
- Live Site URL: [Live site](https://gulzhub.github.io/qrcode-component-challenge/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This is a solution to the beginner level challenge and is fairly easy. However, on attempting this challenge, I got to know how to center a div vertically. Centering a div has been a very ppopular topic in HTML and CSS.
There are a number of ways to center vertically but Flexbox makes it very easy(in my opinion). I just used a div inside main and using flex display on the main tag. Flexbox also makes it easy in centering it horizontally.



```html
<main>
    <div class="content">
      ...
    </div>
</main>
```
```css
main {
    display: flex;
    flex-direction: row;
    justify-content: center;
    text-align: center;
    align-items: center;
    min-height: 100vh;
}
```


## Connect


- Frontend Mentor - [@Gulzhub](https://www.frontendmentor.io/profile/Gulzhub)
- Twitter - [@gulz4you](https://twitter.com/gulz4you)

