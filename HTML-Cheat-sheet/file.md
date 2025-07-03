
# 📟 HTML Cheat Sheet

A quick reference to essential HTML elements – perfect for beginners and daily developers.

---

## 📄 Basic HTML Structure

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <!-- Your content goes here -->
  </body>
</html>
```

---

## 🧱 Common Tags

| Tag            | Description                    | Example                                      |
|----------------|--------------------------------|----------------------------------------------|
| `<h1>`–`<h6>`  | Headings (1–6)                 | `<h1>Title</h1>`                             |
| `<p>`          | Paragraph                      | `<p>This is a paragraph.</p>`               |
| `<a>`          | Link                           | `<a href="https://example.com">Link</a>`    |
| `<img>`        | Image                          | `<img src="img.jpg" alt="desc">`            |
| `<ul>`         | Unordered List                 | `<ul><li>Item</li></ul>`                    |
| `<ol>`         | Ordered List                   | `<ol><li>Item</li></ol>`                    |
| `<div>`        | Block container                | `<div>Block</div>`                          |
| `<span>`       | Inline container               | `<span>Text</span>`                         |
| `<br>`         | Line Break                     | `Line1<br>Line2`                            |

---

## 🧹 Forms & Inputs

```html
<form action="/submit" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  <button type="submit">Submit</button>
</form>
```

| Tag              | Purpose                  |
|------------------|--------------------------|
| `<input>`        | Input field              |
| `<textarea>`     | Multi-line input         |
| `<button>`       | Button                   |
| `<select>`       | Dropdown menu            |
| `<label>`        | Input label              |

---

## 🎨 Text Formatting Tags

| Tag        | Purpose                 | Example                            |
|------------|--------------------------|------------------------------------|
| `<strong>` | Bold (semantic)          | `<strong>Important</strong>`       |
| `<em>`     | Italic (semantic)        | `<em>Note</em>`                    |
| `<b>`      | Bold (visual only)       | `<b>Bold</b>`                      |
| `<i>`      | Italic (visual only)     | `<i>Italic</i>`                    |
| `<code>`   | Inline code              | `<code>let x = 5;</code>`          |
| `<pre>`    | Preformatted text block  | `<pre>  Code block</pre>`          |

---

## 📊 Tables

```html
<table>
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Row 1 Col 1</td>
    <td>Row 1 Col 2</td>
  </tr>
</table>
```

---

## 📦 Meta Tags

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

---

## 🔗 HTML Entities

| Entity       | Symbol   |
|--------------|----------|
| `&lt;`       | `<`      |
| `&gt;`       | `>`      |
| `&amp;`      | `&`      |
| `&quot;`     | `"`      |
| `&nbsp;`     | (space)  |

---

## ✅ Tip

Use browser DevTools to inspect and test HTML live!

---
