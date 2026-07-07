# Learning HTML

## Objective

This README summarizes the main concepts to learn when working with HTML, with a focus on writing clean, semantic, and accessible web pages.

## 1. HTML Guidelines

- Use semantic HTML whenever possible.
- Keep markup clean, readable, and well-indented.
- Use lowercase tag names and attribute names.
- Close all tags properly.
- Use meaningful `alt` text for images.
- Follow accessibility best practices.

## 2. Creating the Skeleton of an HTML5 Page

A basic HTML5 document has this structure:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Title</title>
  </head>
  <body>
    <h1>Hello World</h1>
  </body>
</html>
```

## 3. Semantic HTML Tags

Semantic tags describe the meaning of content and improve accessibility and SEO.

- `header`: introductory content or site header
- `main`: main content of the page
- `footer`: footer information
- `article`: self-contained content like a blog post
- `nav`: navigation links
- `section`: thematic grouping of content
- `aside`: related or supplementary content

## 4. `div` vs `span`

- Use `div` for block-level containers that group larger sections of content.
- Use `span` for inline elements that wrap small pieces of text or content.

## 5. Headings and Hierarchical Order

Headings help structure content for users and search engines.

- Use `h1` for the main title.
- Follow a logical order: `h1` → `h2` → `h3` and so on.
- Do not skip heading levels unnecessarily.

## 6. Lists in HTML

HTML supports:

- Unordered lists with `<ul>` and `<li>`
- Ordered lists with `<ol>` and `<li>`
- Description lists with `<dl>`, `<dt>`, and `<dd>`

## 7. Media File Types

Different image formats are used for different purposes:

- `SVG`: vector graphics, scalable, ideal for logos and icons
- `GIF`: simple animations, limited colors
- `PNG`: lossless image format with transparency support
- `JPG` or `JPEG`: photographic images, compressed format

## 8. Tables in HTML

Tables are used to structure tabular data.

```html
<table>
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Alice</td>
    <td>25</td>
  </tr>
</table>
```

## 9. Adding Video and Audio

### Video

```html
<video controls>
  <source src="movie.mp4" type="video/mp4">
</video>
```

### Audio

```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
</audio>
```

## 10. Embedding External Content

You can embed content from other sources using tags such as:

- `<iframe>` for external webpages or media
- `<embed>` for external content
- `<object>` for multimedia objects

## 11. Correct Structure of an HTML Page

A well-structured HTML page should include:

- A doctype declaration
- An `<html>` root element
- A `<head>` section for metadata and linked resources
- A `<body>` section for visible content
- Proper semantic sections such as `header`, `main`, `section`, `article`, `nav`, `aside`, and `footer`

## Summary

Learning HTML well means writing pages that are structured, semantic, accessible, and easy to maintain.
