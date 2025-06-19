## Common HTML Tags
- `<html>` - Root element of an HTML document.
- `<head>` - Contains metadata, title, and links to stylesheets/scripts.
- `<title>` - Sets the title of the document (shown in the browser tab).
- `<body>` - Contains the content of the document (text, images, links).
- `<h1> to <h6>` - Heading elements (h1 is the largest, h6 is the smallest).
- `<p>` - Paragraph element for text content.
- `<a>` - Anchor element for hyperlinks (links to other pages or resources).
- `<img>` - Image element for displaying images (requires `src` attribute).
- `<ul> <ol>` - Unordered and Ordered list (bulleted list).
- `<table>` - Tables
- `<div> <span>` - Generic Containers
- `<form> <input>` - Form and Inputs (To create webforms)

### Tag Atributes
- `<tagname attributeName="Value"> Content </tagname>`
- `<tagname attributeName="Value" /> ` (Optional for HTML 5)
- `<a href="about.html"> About </a>`
- `<img src="logo.png" alt="logo" /> `

## Document Structure
```
<!DOCTYPE html>  <!--Tells browser its an HTML5 Document -->
<html>  <!-- Root Element -->
    <head> <!-- Contains Meta info, title, links to other resources, etc -->
        <title> My First Webpage</title>
    </head>
    <body> <!-- Content of the page -->
        <h1> Hello World </h1>
    </body>
</html>
```

## Meta Contents
- Charset (to view text properly)
`<meta charset="UTF-8">`
- Viewport (Control layout on different devices devices - Responsive)
`<meta name="viewport" content="width=device-width, initial-scale=1.0">`
- Keyword and Description (Description is displayed in search result, keyword should relate to the page content)
`<meta name="description" content="Learn html, css">`
   `<meta name="keyword" content="html, css, js">`
- Author (Provide information about the author)
- Robots (Control how search engines index the pages)

## Semnatic Elements
- `Header` : header of the layout
- `Nav` : Navigation links
- `Main` : Main content of the page
- `Article` : Independent content (like blog post)
- `Section` : Section of the page (like a chapter)
- `Aside` : Related content (like sidebar)
- `Footer` : Footer of the layout
- `Figure` : Image with caption
- `Figcaption` : Caption for the figure
- `Time` : Represents a specific time (like a date)