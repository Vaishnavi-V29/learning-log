# 📘 Chapter 2 — Tag Categories

## 1. Semantic tags (content tags)

* `h1 - h6` → section headings
* `<p></p>` → paragraph
* `<a href="https://www.google.com">google</a>` → hyperlink
* `<a href="mailto:...">` → mail link
* `<a href="tel:...">` → call link

### Lists

* `<ul><li></li></ul>` → unordered list
* `<ol><li></li></ol>` → ordered list
* description list

Shortcut: `ol>li*3`
---

### Table

```html
<table>
    <tr>
        <td></td>
    </tr>
</table>
```
---

### Image

```html
<img src="source link" alt="alternate text">
```
---
## 2. Formatting tags

* `<b></b>`, `<strong></strong>` → bold (strong has emphasis)
* `<i></i>`, `<em></em>` → italic
* `<u></u>` → underline
* `<s></s>` → strikeout
* `<sub>` → subscript
* `<sup>` → superscript
* `<pre>` → preformatted text
* `<br>` → line break

Tip: `lorem100` inside `<p>` generates dummy text
---

## 3. Structural tags

### Basic page structure
* `<html>` → root
* `<head>` → info
* `<body>` → content

### Layout structure
* `<header>` → top section
* `<nav>` → navigation
* `<main>` → main content
* `<section>` → grouped content
* `<article>` → independent content
* `<aside>` → sidebar
* `<footer>` → bottom

### Generic containers
* `<div>` → block-level container
* `<span>` → inline container
---

### `<div>`
* block-level
* takes full width
* used for grouping large sections

### `<span>`
* inline
* takes only needed width
* used for small text grouping
---
