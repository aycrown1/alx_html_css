### HTML Basics

HTML (Hypertext Markup Language) is the standard markup language used for creating web pages and applications. It consists of a set of elements that structure the content and define its meaning within a web document. Here are some of the basic concepts of HTML:

1. Tags: HTML uses tags to define elements and structure the content. Tags are enclosed in angle brackets (< >), and most tags have opening and closing tags. For example, `<p>` is the opening tag for a paragraph, and `</p>` is the closing tag.

2. Elements: Elements are made up of tags and the content they enclose. They define different parts of a web page, such as headings, paragraphs, links, images, tables, forms, and more. Elements can be nested inside each other to create a hierarchical structure.

3. Attributes: Attributes provide additional information about an HTML element. They are placed inside the opening tag and consist of a name and a value. Attributes modify the behavior or appearance of an element. For example, the `href` attribute specifies the URL for a link.

4. Headings: Headings are used to define the hierarchical structure of a document. HTML has six levels of headings, from `<h1>` (the highest level) to `<h6>` (the lowest level). Headings are often used to create titles and subheadings.

5. Paragraphs: Paragraphs are created using the `<p>` tag. They are used to group and format blocks of text. Paragraphs are commonly used for regular text content.

6. Links: Links allow users to navigate between different web pages. They are created using the `<a>` tag and require an `href` attribute that specifies the target URL. When a user clicks on a link, the browser will navigate to the specified URL.

7. Images: Images can be inserted into a web page using the `<img>` tag. The `src` attribute is used to specify the image file's source (URL or local file path), and the `alt` attribute provides alternative text that describes the image.

8. Lists: Lists are used to group related items together. HTML supports two types of lists: ordered lists (`<ol>`) and unordered lists (`<ul>`). Each item within a list is marked with the `<li>` tag.

9. Tables: Tables are used to organize data into rows and columns. They are created using the `<table>` tag. Table rows are defined with the `<tr>` tag, table headers with the `<th>` tag, and table data cells with the `<td>` tag.

10. Forms: Forms are used to collect user input, such as text fields, checkboxes, radio buttons, and submit buttons. They are created using the `<form>` tag and contain various input elements defined by tags like `<input>`, `<textarea>`, `<select>`, and more.

```html
<!DOCTYPE html>
<html>
<head>
  <title>My Webpage</title>
</head>
<body>
  <h1>Welcome to My Webpage</h1>
  <p>This is a paragraph of text.</p>
  <img src="https://example.com/image.jpg" alt="Example Image">
</body>
</html>

```
