# Markdown to Markup

We're moving on—admittedly, rather quickly—from Markdown to proper HTML. You can continue to use Markdown for basic document outlining. I use it to take notes! But to make real websites, we need to begin understanding proper HTML.

## Why bother with Markdown?

HTML isn't the easiest syntax to read/write when you're starting. Markdown gives us an easy entry-point into the core mechanism of software development: type something very specific in, get what you want out. Attention to detail is important.

Now into the real stuff.

## HTML Documents/Elements

Tim Berners-Lee invented HTML to send scientific information over the early internet in a structured way. So HTML pages are best considered as structured **documents**. Documents are made of **elements**.

## Tags: they're it

In Markdown, we used special characters like `#` to indicate the structure of lines or sections of our text. In HTML, we surround the text with tags. Doing so creates an HTML element.

For example, in Markdown we created a first-level heading with a single hashtag. In HTML, it looks like:

```html
<h1>This is a top-level heading!</h1>
```

Couple of things to notice here:

1. Tags are identifiers surrounded by `<>`, called "angle brackets."
2. Each set of tags has an opening and closing tags. The closing tag includes a slash, like `</h1>`. 
3. Most HTML elements need an opening and closing tag, but some don't These are called "self-closing tags."

## Tags you should know:

Here are a few important HTML tags to get started:

Tag | Purpose | Notes
--|--|--
`<h1>` | First-level heading | There are 6 levels of headings
`<p>` | Paragraph | All basic text should be in these
`<b>` | Bold |
`<i>` | Italics |
`<strong>` | Strong-styled text | Like `<b>`, but more semantically meaningful
`<em>` | Emphasized text | Like `<i>`, but more semantically meaningful
`<ul>` | Container for unordered lists | Bulleted lists
`<ol>` | Container for ordered lists | Numbered lists
`<li>` | List item | Used inside `<ul>` and `<ol>` elements
`<div>` | Division of the document | Used to contain groups of related elements

## `index.html`

You'll notice in this folder is a file called `index.html` This is the name for the starting point of all HTML projects. When you visit a website, the first thing you see is a file called `index`.

The file here has some built-in structure. Let's break down each element

Element | Purpose
--|--
`<html>` | The element that contains everything.
`<head>` | Information about the document. Not rendered to the page.
`<title>` | The document's title. These days, the browser tab's label.
`<body>` | Where the actual content of the page is going to go.
`<h1>` | A heading!
`<img>` | An image, which the `src` attribute points to the right file to display.


## Primary Objective: Tell us about WidgetCorp

I don't know what WidgetCorp does, but I bet you do. Make some `<h2>`, `<p>`, and lists (`<ul>` or `<ol>`) that describe what WidgetCorp does. Some ideas for sections.

* Mission
* About
* Contact
* Products

## Bonus Objectives: Add some images!

See that `<img>` in the file? See that `images` folder? You can either put images in there, or link to images on the internet and make some more images that relate to the sections you create.

## "What about links?"

Stay tuned...
