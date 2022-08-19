# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## My process
  - Set up the colors, font-family and font-size i need from the "./style-guide.md".
  - Added divs to seperate certain elements and added class name to their corresponding role.
  - Set up the css.
  - Searched youtube on "How to center a div"/
  - I had a problem with the border radius and just set it up to 10px and 20px.
  - I also had a problem with the mobile view and fix it by making my before .card max-width: 320px to width: 320px.
### Built with

- Semantic HTML5 markup
- CSS
- position: absolute

### What I learned

Well I learned how to center a div in HTML/CSS ang might search it up on youtube again soon.

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.card {
      text-align: center;
      padding: 16px;
      background-color: hsl(0, 0%, 100%);
      border-radius: 20px;
      position: absolute;
      width: 320px;
      top: 50%;
      left: 50%;
      transform: translate(-50% ,-50%);
    }
```
