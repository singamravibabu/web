# Introduction to HTML

- What is HTML?
  - HTML stands for HyperText Markup Language.
  - It is the standard language for creating web pages.
  - HTML documents are made up of elements represented by tags.
- Basic HTML Structure

```html
<!DOCTYPE html>
<html>
<head>
  <title>My First Web Page</title>
</head>
<body>
  <h1>Hello, World!</h1>
  <p>This is my first web page.</p>
</body>
</html>
```

- Explanation:
  - `<!DOCTYPE html>`: Defines the document type and HTML version.
  - `<html>`: Root element of the HTML document.
  - `<head>`: Contains meta-information like the title.
  - `<title>`: Sets the title of the web page (visible on the browser tab).
  - `<body>`: Contains the visible content of the web page.
  - `<h1>`, `<p>`: Heading and paragraph tags.

## 1. Basic HTML Tags

- Headings

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

- Paragraphs
```html
<p>This is a paragraph.</p>
```

- Line Breaks and Horizontal Lines
```html
<p>This is a line.<br>This is another line.</p>
<hr>
```

## 2. HTML Attributes

- Using Attributes

```html
<p style="color:blue;">This is a blue paragraph.</p>
<a href="https://www.example.com">Visit Example</a>
<img src="image.jpg" alt="Description of Image" width="200">
```

- Explanation:
  - `style`: Inline styling.
  - `href`: Link to another page.
  - `src`: Source of an image.
  - `alt`: Alternate text for accessibility.
  - `width`: Adjusts the size of the image.

## 3. Lists

- Ordered List

```html
<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ol>
```

- Unordered List

```html
<ul>
  <li>Bullet point 1</li>
  <li>Bullet point 2</li>
</ul>
```

- Nested List
```html
<ul>
  <li>Item 1
    <ul>
      <li>Sub-item 1.1</li>
    </ul>
  </li>
</ul>
```

## 4. Tables

- Basic Table Structure

```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>John</td>
    <td>25</td>
  </tr>
  <tr>
    <td>Jane</td>
    <td>22</td>
  </tr>
</table>
```

- Explanation:
  - `<table>`: Defines a table.
  - `<tr>`: Table row.
  - `<th>`: Table header.
  - `<td>`: Table data.

## 5. Forms

- Creating a Simple Form

```html
<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  <br><br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email">
  <br><br>
  <input type="submit" value="Submit">
</form>
```

- Explanation:
  - `<form>`: Creates a form.
  - `action`: URL where the form data is sent.
  - `method`: HTTP method (GET or POST).
  - `<label>`: Describes an input.
  - `<input>`: Collects user input.

## 6. Links and Navigation

- Internal Links

```html
<a href="#section1">Go to Section 1</a>
<h2 id="section1">Section 1</h2>
```

- External Links
```html
<a href="https://www.google.com" target="_blank">Open Google</a>
```

  - Explanation:
    - `target="_blank"`: Opens link in a new tab.

## 7. Images and Multimedia

- Embedding Images
```html
<img src="logo.png" alt="Website Logo" width="150">
```

- Embedding Videos
```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

## 8. Semantic HTML

- Using Semantic Tags

```html
<header>
  <h1>Website Header</h1>
</header>
<nav>
  <a href="#home">Home</a>
  <a href="#about">About</a>
</nav>
<main>
  <article>
    <h2>Article Title</h2>
    <p>This is an article.</p>
  </article>
</main>
<footer>
  <p>&copy; 2024 My Website</p>
</footer>
```

## 9. HTML Best Practices
- Use Meaningful Tags
- Indent Code for Readability
- Always Close Tags
- Use Comments for Documentation

```html
<!-- This is a comment -->
```

## 10. Hands-on Practice

- Create a Personal Web Page
  - Include a profile picture, a short bio, hobbies, and links to favorite websites.
- Create a Simple Form for Contact
  - Name, email, message, and submit button.

## 11. Project Assignment
- Build a multi-page website with:
  - Home page with navigation.
  - About page with a list of hobbies and interests.
  - Contact page with a form.
  - Use images, links, tables, and forms.
