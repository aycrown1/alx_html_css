### HTML, basic

**HTML** (HyperText Markup Language) is a markup language that tells web browsers how to structure the web pages you visit. It can be as complicated or as simple as the web developer wants it to be. HTML consists of a series of elements, which you use to enclose, wrap, or mark up different parts of content to make it appear or act in a certain way. The enclosing tags can make content into a hyperlink to connect to another page, italicize words, and so on.

To create an HTML page, you need a text editor to write the HTML code.

```html
<!DOCTYPE html>
<html>
<head>
  <title>Page Title</title>
</head>
<body>
  <h1>This is a Heading</h1>
  <p>This is writes the inside text in a paragraph.</p>
</body>
</html>
```

#### key concepts related to HTML

1. Markup Language: A markup language is a system for annotating a document's structure and formatting, providing instructions to a browser or other rendering engine on how to display the content.

2. DOM (Document Object Model): The DOM represents the structured content of an HTML document as a tree-like structure, where each element in the document is a node. It allows scripting languages (like JavaScript) to interact with the elements and modify the content dynamically.

3. Element/Tag: In HTML, an element represents a structure or a specific part of a document, such as headings, paragraphs, images, links, etc. Elements are defined using tags. For example, `<h1>` is the opening tag for a heading level 1 element, and `</h1>` is the closing tag.

4. Attribute: An attribute provides additional information about an HTML element. Attributes are used within the opening tag of an element and consist of a name and a value. For example, the `src` attribute in the `<img>` tag specifies the source URL of an image.


#### How does the browser load a webpage?

When a browser loads a webpage, it follows these general steps:

1. The browser sends a request to the web server for the specified webpage.
2. The server responds with the HTML document containing the webpage's content.
3. The browser parses the HTML document from top to bottom, building the DOM tree structure.
4. As the browser encounters external resources like CSS stylesheets or JavaScript files referenced in the HTML, it sends additional requests to retrieve those resources.
5. The browser renders the webpage based on the CSS styles, positions the elements on the screen, and displays the content to the user.

