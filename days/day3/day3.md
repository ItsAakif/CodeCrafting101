
# Day 3: CSS for Styling

## Introduction to CSS (Cascading Style Sheets)

CSS (Cascading Style Sheets) is a powerful styling language used to control the presentation and layout of HTML documents. It allows you to make your web pages visually appealing and create consistent designs across your site. In today's lesson, we'll introduce you to CSS and cover basic styling concepts.

## Delve into the World of CSS

CSS works by selecting HTML elements and applying styles to them. You can apply CSS styles directly in an HTML document using the `<style>` element or by linking an external CSS file to your HTML. Here's a simple example of inline CSS:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My Styled Webpage</title>
    <style>
        h1 {
            color: blue;
            font-size: 24px;
        }
        p {
            color: green;
        }
    </style>
</head>
<body>
    <h1>Welcome to My Webpage</h1>
    <p>This is some text with styles applied.</p>
</body>
</html>
```

In this example, we've used CSS to change the color and font size of the `<h1>` element and the color of the `<p>` element.

## CSS Properties and Values

CSS consists of properties and values. Properties define what aspect of an element you want to style, and values specify how you want to style it. Here are a few common CSS properties:

- `color`: Sets the text color.
- `font-size`: Adjusts the font size.
- `background-color`: Sets the background color.
- `border`: Defines the border properties (e.g., border color, width, style).
- `padding`: Adds space inside an element's border.
- `margin`: Adds space outside an element's border.

Here's an example that demonstrates these properties:

```css
h1 {
    color: red;
    font-size: 28px;
    background-color: yellow;
    border: 2px solid green;
    padding: 10px;
    margin: 20px;
}
```

## Styling Backgrounds, Borders, Fonts, and Text

- **Backgrounds**: You can set background colors, images, and other background properties to style the background of elements.
- **Borders**: Borders can be customized with colors, styles (e.g., solid, dashed), and widths.
- **Fonts**: You can change the font family, font size, and font weight (bold, normal).
- **Text**: CSS provides options to control text alignment, decoration (e.g., underline), and spacing (e.g., line height).

Here's a sample CSS code that demonstrates these concepts:

```css
body {
    background-color: #f0f0f0;
    font-family: Arial, sans-serif;
}

p {
    border: 1px solid #ccc;
    padding: 10px;
    text-align: center;
    text-decoration: underline;
    line-height: 1.5;
}
```

## Hands-on Activity

1. Create a new HTML file (e.g., "styled.html") and copy the HTML structure provided above.

2. Add a `<style>` block within the `<head>` of your HTML document to apply CSS styles to your elements.

3. Experiment with different CSS properties and values to style your headings, paragraphs, or other elements on the page.

4. Open your HTML file in a web browser to see the applied styles.

Congratulations! You've been introduced to CSS and learned how to style backgrounds, borders, fonts, and text. In Day 4, we'll explore responsive web design techniques to ensure your web pages look great on various devices and screen sizes. Keep up the great work!


## Additional Resources

To further enhance your understanding of CSS for styling web pages, you can explore the following resources:

- **Mozilla Developer Network (MDN) CSS Documentation**:
  - [CSS Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)
  - [CSS Properties Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
  - [CSS Box Model](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)

- **W3Schools CSS Tutorial**:
  - [CSS Tutorial](https://www.w3schools.com/css/)
  - [CSS Reference](https://www.w3schools.com/cssref/)

- **CSS Cheat Sheets**:
  - [CSS Cheat Sheet](https://websitesetup.org/css3-cheat-sheet/)
  - [CSS Specificity Cheat Sheet](https://www.smashingmagazine.com/2007/07/css-specificity-things-you-should-know/)

- **CSS Frameworks**:
  - [Bootstrap](https://getbootstrap.com/)
  - [Tailwind CSS](https://tailwindcss.com/)
  - [Bulma](https://bulma.io/)

- **CSS Editors**:
  - [Visual Studio Code](https://code.visualstudio.com/)
  - [Sublime Text](https://www.sublimetext.com/)

- **Online CSS Code Editors**:
  - [CodePen](https://codepen.io/)
    - Experiment with CSS code and see live results.

- **Responsive Design**:
  - [Responsive Web Design Basics](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
  - [Media Queries for Responsive Design](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)

These resources offer tutorials, references, and tools to help you master CSS for styling web pages. Whether you're a beginner or looking to dive deeper into CSS, these materials are valuable for improving your web development skills.

[Day 2](../day2/day2.md) | [Day 4](../day4/day4.md)  