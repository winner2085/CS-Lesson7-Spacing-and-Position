# Lesson 2.6: Spacing & Position

## 🎯 Objectives
- Learn to manipulate the properties of the box model
- Use flexbox for alignment
- Understand spacing and positioning in HTML/CSS.

## Table of Contents
1. [Box Model](#box-model)
    - [Overview](#overview)
    - [Example](#box-model-example)
2. [Flexbox](#flexbox)
    - [Introduction](#flexbox-introduction)
    - [Example](#flexbox-example)
3. [Positioning](#positioning)
4. [Exit Ticket & Closing](#exit-ticket)

## Box Model
### Overview
The box model consists of four components:
- **Content**: Actual content (text, images, etc.).
- **Padding**: Space between content and border.
- **Border**: Line separating content from padding.
- **Margin**: Space outside the element.

### Box Model Example
```css
h1 {
  border: 4px solid blue;
  padding: 5px;
  margin: 5px;
}
```
This code adds a solid blue border of 4px, 5px of padding, and 5px of margin to all `h1` elements.

## Flexbox
### Introduction
Flexbox is a set of CSS properties for aligning items on a webpage.

### Flexbox Example
HTML:
```html
<div class="container">
  <p>Dogs</p>
  <p>Cats</p>
  <p>Hamsters</p>
</div>
```
CSS:
```css
.container {
  display: flex;
  justify-content: space-between;
}
```
This aligns the child elements with space between them.

## Positioning
Manipulate an element's position with the `position` property. Possible values:
- **Static**
- **Relative**
- **Absolute**
- **Fixed**

Example:
```css
img {
  position: fixed;
  top: 0;
  right: 0;
}
```
This fixes an image at the top-right corner of the viewport.

Happy coding!
