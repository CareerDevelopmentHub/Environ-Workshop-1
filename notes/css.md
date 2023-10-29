# ✨ CSS (Cascading Style Sheets)

It is a style sheet language used for describing the presentation of a document written in a markup language such as HTML or XML. CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript. In a eassy way you can it as the makeup and styling part of the web page.

## Types of CSS

- Inline CSS, example: `<h1 style="color: red; font-size: 20px;">This is a heading</h1>`
- Internal CSS, example: using the `<style></style>` tags inside the head tags.
- External CSS, example: here we have to create a external `css file` and linking the css file to the html file

## Selectors in CSS

- Element selectors: Select elements by name, such as h1, p, or div.
- Class selectors: Select elements with a specific CSS class.
- ID selectors: Select elements with a specific ID.
- Descendant selectors: Select elements that are descendants of another element.
- Child selectors: Select elements that are direct children of another element.
- Adjacent sibling selectors: Select elements that are adjacent siblings of another element.
- Pseudo-class selectors: Select elements based on their state, such as when they are hovered over or clicked on.
- Pseudo-element selectors: Select specific parts of an element, such as the first letter or the last child.

## Sedo Selectors

Sedo Selectors are a set of CSS pseudo-elements that can be used to style specific parts of an element. They are similar to regular CSS selectors, but they are used to select specific parts of an element, such as the first letter, the first line, or the before and after pseudo-elements.

The following are some of the most common Sedo Selectors:

- ::first-letter: Selects the first letter of an element.
- ::first-line: Selects the first line of an element.
- ::before: Inserts content before the content of an element.
- ::after: Inserts content after the content of an element.

## Media queries

Media queries in CSS are a way to apply different CSS styles to different devices and media types. They are used to create responsive web designs, which adapt to the screen size, orientation, and other characteristics of the device on which they are being viewed.

```
@media (max-width: 768px) {
  body {
    /*...*/
    /*...*/
    /*...*/
  }
  /*...*/
  /*...*/
  /*...*/
  /*...*/
}
```

### Other common media queries include:

- min-width: Specifies a minimum screen width.
- max-height: Specifies a maximum screen height.
- orientation: Specifies the orientation of the device (portrait or landscape).
- aspect-ratio: Specifies the aspect ratio of the device's screen.
- resolution: Specifies the resolution of the device's screen.
- media type: Specifies the type of media on which the web page is being displayed (screen, print, speech, etc.).

Media queries can be used to style a variety of elements on a web page, including text, images, layout elements, and even other media queries. By using media queries, you can create web pages that look good and function well on all devices and media types.
