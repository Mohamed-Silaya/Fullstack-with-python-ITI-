# HTML Guide

## Types of HTML
HTML is a markup language used to create web pages. Different versions include:
- **HTML 4.01**: A widely used version before HTML5.
- **XHTML**: A stricter, more XML-compliant version of HTML.
- **HTML5**: The latest version, featuring new elements like `<video>`, `<audio>`, and local storage capabilities.

## Essential Guidelines
- **File Extension**: `.html`
- **Folder Naming**: Use descriptive folder names to organize website content efficiently.
- **Tags that require closing**: Most HTML tags have an opening and closing tag, e.g., `<p></p>`.
- **Self-closing tags**: Some tags do not require a closing tag, such as:
  - `<img src="image.jpg" alt="Image description" />`
  - `<br />` (line break)
  - `<hr />` (horizontal line)

## **The Head Section in HTML**
The `<head>` section contains metadata and resources that define the behavior and structure of a webpage. Key elements include:
- **SEO (Search Engine Optimization)**: Helps improve search rankings.
- **Title (`<title>`)**: Displays the page title in the browser tab.
- **Links (`<link>`)**:
  - `<link rel="stylesheet" href="style.css" />` (to link CSS files).
  - `<script src="script.js"></script>` (to include JavaScript files).
- **Meta Tags**:
  - `<meta charset="UTF-8" />` (sets character encoding).
  - `<meta name="viewport" content="width=device-width, initial-scale=1.0" />` (enhances responsiveness).
  - `<meta name="author" content="Author Name" />` (specifies page author).
  - `<meta name="robots" content="index, follow" />` (controls search engine indexing behavior).

## **The Body Section in HTML**

### **Types of Elements**
- **Inline Elements**: Occupy space according to content size, such as:
  - `<span>` (inline text styling)
  - `<b>` (bold text)
  - `<i>` (italic text)
  - `<a href="https://example.com">` (hyperlinks)
  - `<img src="image.jpg" alt="Image description" />` (images) 
- **Block Elements**: Occupy the full width of their parent container, such as:
  - `<p>` (paragraphs)
  - `<div>` (sections or layout blocks)
  - `<h1>` to `<h6>` (headings)
  - `<ul>` and `<ol>` (lists)
  - `<table>` (tables)
  <br> **Example:   [LAB1](https://github.com/Mohamed-Silaya/Fullstack-with-python-ITI-/blob/main/HTML/01_Day1/project/My_info.html)**
  <br> **Example:   [LAB2](https://github.com/Mohamed-Silaya/Fullstack-with-python-ITI-/blob/main/HTML/01_Day1/project/list.html)**

### **Tables in HTML**
Tables are used for organizing data into rows and columns. Key elements include:
- `<table>`: Defines the table.
- `<tr>`: Defines a row.
- `<th>`: Defines table headers.
- `<td>`: Defines table data cells.

#### **Example of a Simple Table:**
```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Ahmed</td>
    <td>25</td>
  </tr>
  <tr>
    <td>Mohamed</td>
    <td>30</td>
  </tr>
</table>
```
 <br> **Exercise:   [LAB](https://github.com/Mohamed-Silaya/Fullstack-with-python-ITI-/blob/main/HTML/01_Day1/project/all_data.html)**
### **Forms in HTML**
Forms allow users to input data via interactive fields. Common elements include:
- `<input>`: Text fields, checkboxes, radio buttons, etc.
- `<textarea>`: Multi-line text input.
- `<button>`: Submit, reset, or custom action buttons.
- `<select>`: Dropdown menus.

#### **Example of a Simple Form:**
```html
<form action="submit.php" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required>
  <br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>
  <br>
  <button type="submit">Submit</button>
</form>
```
 <br> **LAB:   [EX](https://github.com/Mohamed-Silaya/Fullstack-with-python-ITI-/blob/main/HTML/01_Day1/project/Registration_Form.html)**

### **Media Elements in HTML**
HTML5 supports embedded media elements, such as:
- **Video (`<video>`)**: Embeds a video file.
- **Audio (`<audio>`)**: Embeds an audio file.

#### **Example of a Video Player:**
```html
<video width="320" height="240" controls>
  <source src="video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

### **Additional HTML Features**
- **Semantic Elements**: HTML5 includes elements that enhance readability and SEO, such as:
  - `<header>` (header section)
  - `<nav>` (navigation menus)
  - `<section>` (content sections)
  - `<article>` (independent articles/posts)
  - `<footer>` (footer section)
- **Accessibility Features**: Attributes like `alt` (for images) and `aria-label` improve screen reader compatibility.
- **Responsive Design**: Using `<meta viewport>` and CSS media queries, HTML pages adapt to different screen sizes.

---



