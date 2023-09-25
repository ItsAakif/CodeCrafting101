
# Day 2: HTML Elements and Text Formatting

## Dive Deeper into HTML Elements

In Day 1, you were introduced to the basic structure of HTML and some essential elements. Today, we'll dive deeper into HTML elements, including headings, paragraphs, and lists. These elements are fundamental for structuring content on your web pages.

### HTML Headings

HTML offers six levels of headings, from `<h1>` (most important) to `<h6>` (least important). Headings are used to give structure and hierarchy to your content. Here's how to use them:

```html
<h1>This is a Level 1 Heading</h1>
<h2>This is a Level 2 Heading</h2>
<h3>This is a Level 3 Heading</h3>
<!-- And so on... -->
```

### HTML Paragraphs

Paragraphs are used to group and format text. You can create paragraphs using the `<p>` element:

```html
<p>This is a paragraph of text. It can contain multiple sentences.</p>
<p>Another paragraph follows.</p>
```

### HTML Lists

HTML supports two main types of lists: ordered and unordered.

- **Unordered (Bulleted) Lists** (`<ul>`):

  ```html
  <ul>
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
  </ul>
  ```

- **Ordered (Numbered) Lists** (`<ol>`):

  ```html
  <ol>
      <li>First item</li>
      <li>Second item</li>
      <li>Third item</li>
  </ol>
  ```

### Discover How to Format Text

HTML provides various tags to format text effectively. Here are some common formatting tags:

- `<em>`: Emphasizes text (usually displayed as italic).
- `<strong>`: Makes text strong or important (usually displayed as bold).
- `<u>`: Underlines text.
- `<s>`: Represents strikethrough text.

```html
<p>This text is <em>emphasized</em>, this is <strong>strong</strong>, and this is <u>underlined</u>.</p>
<p><s>This text has strikethrough.</s></p>
```

### Simple Webpage with HTML

Now, let's create a simple webpage using the concepts we've learned. Open your text editor and use the following code:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My Simple Webpage</title>
</head>
<body>
    <h1>Welcome to My Webpage</h1>
    
    <h2>About Me</h2>
    <p>I am a web developer learning HTML and CSS.</p>
    
    <h2>My Interests</h2>
    <ul>
        <li>Coding</li>
        <li>Design</li>
        <li>Music</li>
    </ul>
    
    <p>Feel free to <a href="#">contact me</a> if you have any questions!</p>
</body>
</html>
```

Save this file with an ".html" extension (e.g., "mywebpage.html") and open it in a web browser. You've just created a simple webpage with headings, paragraphs, a list, and a placeholder link.

### Hyperlinks

Hyperlinks, often referred to as links, are essential for connecting web pages and creating navigation within websites. HTML uses the `<a>` (anchor) element to create hyperlinks. Here's how to create a basic hyperlink:

```html
<a href="https://www.example.com">Visit Example.com</a>
```

- `<a>`: The anchor element.
- `href`: The "href" attribute specifies the URL (web address) to which the link points.
- Text between the opening and closing `<a>` tags is the visible link text.

You can create internal links within your website by specifying relative URLs instead of absolute URLs. For example:

```html
<a href="about.html">Learn About Me</a>
```

This link would point to an "about.html" file in the same directory as your current HTML document.

### Images

Images are used to enhance the visual appeal of web pages. HTML employs the `<img>` element to display images. Here's how to add an image to your webpage:

```html
<img src="image.jpg" alt="Description of the image">
```

- `<img>`: The image element.
- `src`: The "src" attribute specifies the image file's source (URL or file path).
- `alt`: The "alt" attribute provides alternative text for the image (important for accessibility and SEO).

### Incorporating Links and Images into Your Web Page

Now, let's incorporate links and images into your webpage. Modify your HTML code as follows:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My Webpage with Links and Images</title>
</head>
<body>
    <h1>Welcome to My Webpage</h1>
    
    <h2>About Me</h2>
    <p>I am a web developer learning HTML and CSS.</p>
    
    <h2>My Interests</h2>
    <ul>
        <li>Coding</li>
        <li>Design</li>
        <li>Music</li>
    </ul>
    
    <h2>Links and Images</h2>
    
    <!-- Link to an external website -->
    <p>Visit my favorite website: <a href="https://www.example.com">Example.com</a></p>
    
    <!-- Image from the same directory as your HTML file -->
    <img src="image.jpg" alt="A beautiful image">
    
    <p>Feel free to <a href="contact.html">contact me</a> if you have any questions!</p>
</body>
</html>
```

In this updated code, we added a hyperlink to an external website (Example.com) and an image ("image.jpg") to your webpage. Make sure to replace "image.jpg" with the actual file path or URL of the image you want to display.

Save the file and open it in a web browser. You should now see hyperlinks and an image incorporated into your webpage.

Congratulations! You've explored HTML elements and text formatting, and you've built a basic webpage to practice your skills to add hyperlinks and images to your web pages. In Day 3, we'll explore CSS (Cascading Style Sheets) for basic webpage styling to make your page even more visually appealing. Keep up the great work!


## Additional Resources

To further enhance your knowledge of HTML elements and text formatting, you can explore the following resources:

- **Mozilla Developer Network (MDN) HTML Documentation**:
  - [HTML Text Elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#text_content)
  - [HTML Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)
  - [HTML Links](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a)

- **W3Schools HTML Tutorial**:
  - [HTML Text Formatting](https://www.w3schools.com/html/html_formatting.asp)
  - [HTML Lists](https://www.w3schools.com/html/html_lists.asp)
  - [HTML Links](https://www.w3schools.com/html/html_links.asp)

- **HTML Cheat Sheets**:
  - [HTML Cheat Sheet](https://websitesetup.org/html5-cheat-sheet/)
  - [HTML Entity Codes](https://www.w3schools.com/html/html_entities.asp)

- **HTML Validators**:
  - [W3C Markup Validation Service](https://validator.w3.org/)

- **CodePen**:
  - [CodePen](https://codepen.io/)
    - Explore HTML and CSS examples created by the community.

- **HTML Editors**:
  - [Visual Studio Code](https://code.visualstudio.com/)
  - [Sublime Text](https://www.sublimetext.com/)

These resources offer detailed explanations, tutorials, and examples to help you gain a deeper understanding of HTML elements, text formatting, and how to create structured web content. They are valuable references for web development enthusiasts at all levels.

 [Day 1](../day1/day1.md) | [Day 3](../day2/day2.md)  

