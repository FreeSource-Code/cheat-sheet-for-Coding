
markdown
Copy
Edit
# 🎨 CSS Cheat Sheet

Welcome to the ultimate **CSS Cheat Sheet**! This document provides a complete reference of essential CSS properties, syntax, and examples — perfect for beginners and pros.

---

## 📌 What is CSS?

CSS (Cascading Style Sheets) is used to style and layout web pages — including the design, colors, spacing, and animations.

```html
<link rel="stylesheet" href="style.css">
```
```
🧾 CSS Syntax

selector {
  property: value;
}
Example:
h1 {
  color: red;
  font-size: 24px;
}
```
```
🎯 CSS Selectors
*         /* Universal */
div       /* Element */
.class    /* Class */
#id       /* ID */
div p     /* Descendant */
div > p   /* Child */
a:hover   /* Pseudo-class */
p::first-letter /* Pseudo-element */
```
```
🎨 Colors

color: red;
color: #ff0000;
color: rgb(255, 0, 0);
background-color: #f0f0f0;
opacity: 0.5;
```
```
🔤 Fonts & Text
font-family: 'Arial', sans-serif;
font-size: 16px;
font-weight: bold;
font-style: italic;
text-align: center;
text-decoration: underline;
line-height: 1.5;
letter-spacing: 1px;
word-spacing: 2px;
text-transform: uppercase;
```
```
📦 Box Model
margin: 10px;
padding: 20px;
border: 2px solid black;
width: 300px;
height: 100px;
box-sizing: border-box;
```
```
🧱 Display & Positioning

display: block | inline | inline-block | flex | grid | none;
position: static | relative | absolute | fixed | sticky;
top, bottom, left, right: 10px;
z-index: 10;
overflow: hidden | scroll | auto;
visibility: visible | hidden;
```
```
🔧 Sizing & Units
width: 100px;
height: 50%;
max-width: 100%;
min-height: 200px;

Units: px, %, em, rem, vh, vw
```
```
🧲 Flexbox

display: flex;
flex-direction: row | column;
justify-content: center | space-between | space-around;
align-items: center | flex-start | flex-end;
flex-wrap: wrap;
gap: 20px;
```
```
🏗 CSS Grid

display: grid;
grid-template-columns: repeat(3, 1fr);
grid-template-rows: 100px 200px;
grid-gap: 10px;
grid-column: 1 / 3;
grid-row: 2 / 4;
```
```
🌀 Backgrounds

background-color: #fff;
background-image: url('image.jpg');
background-repeat: no-repeat;
background-size: cover | contain;
background-position: center center;
background-attachment: fixed;
```
```
🖼 Borders & Shadows

border: 2px dashed red;
border-radius: 10px;
box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
```
```
🔁 Transitions & Animations

transition: all 0.3s ease-in-out;

@keyframes slide {
  from { transform: translateX(-100%); }
  to { transform: translateX(0); }
}

animation: slide 2s infinite;
```
```
🎯 Pseudo-classes & Pseudo-elements
a:hover {
  color: blue;
}

input:focus {
  outline: 2px solid red;
}

p::first-line {
  font-weight: bold;
}
```
```
📱 Media Queries (Responsive Design)

@media (max-width: 768px) {
  body {
    background-color: lightblue;
  }
}
```
```
🌐 CSS Variables
:root {
  --main-color: #3498db;
}

button {
  background-color: var(--main-color);
}
```
```
🔄 Transform & Translate

transform: translateX(50px);
transform: rotate(45deg);
transform: scale(1.2);
```
```
👻 Visibility & Overflow

visibility: hidden;
overflow: hidden | scroll | auto;
```
```
🔘 Buttons Styling
button {
  padding: 10px 20px;
  border: none;
  border-radius: 8px;
  background-color: #007bff;
  color: white;
  cursor: pointer;
}
```
```
🧰 Useful Tools
CSS Tricks

MDN Web Docs

W3Schools CSS

Coolors Color Tool
```

```
🧑‍💻 Author
Ishan Walia
Web & App Developer | Cyber Security Learner
🌐 GitHub | LinkedIn
```

```
📂 License
This cheat sheet is open-source and free to use for learning purposes.
```
```
yaml


Agar tum is `README.md` file ko copy karke GitHub ya Marko ke repo main daaldo, toh yeh ek perfect **CSS knowledge base** ban jaayega.  

📌 **Bonus:** Agar tum image or button preview bhi chahte ho CSS ke sath, toh uske liye ek separate `.html` demo file bana sakte ho. Batao toh woh bhi bana du?

Ready to upload? ✅
```
