 
## 📅 Date: 29 June 2025
## 📘 Topic: Introduction to HTML – Sigma Web Development Course (CodeWithHarry)

### 🎯 What I Learned Today:

### HTML Tags

If you want to build a beautiful website, tags are essential elements that help you achieve that.

An HTML tag acts as a container for content or other HTML tags. Tags are words enclosed within < and > angle brackets.

They serve as keywords that instruct the web browser on how to format and display the content.

Commonly used tags in HTML
Here are some commonly used tags in HTML. These are the only tags used 70% of the time.

## Document Structure Tags
<DOCTYPE html>: Specifies the document type.
<html>: Encloses the entire HTML document.
<head>: Contains meta-information and links to scripts and stylesheets.
<body>: Contains the content of the web page.

## Metadata Tags
<title>: Sets the title of the web page.
<meta>: Provides metadata such as character set, author, and viewport settings.
<link>: Links external resources like stylesheets.

## Text Formatting Tags
<p>: Paragraph.
<h1>, <h2>, <h3>, <h4>, <h5>, <h6>: Headings.
<strong>: Strong emphasis (typically bold).
<em>: Emphasis (typically italic).
<br>: Line break.
<hr>: Horizontal rule.

## List Tags
<ul>: Unordered list.
<ol>: Ordered list.
<li>: List item.

## Hyperlink and Media Tags
<a>: Anchor (used for links).
<img>: Image.
<audio>: Audio content.
<video>: Video content.

## Form Tags
<form>: Form.
<input>: Input field.
<textarea>: Text area.
<button>: Button.
<select>: Dropdown list.
<option>: Options within a <select> or <datalist>.

## Table Tags
<table>: Table.
<tr>: Table row.
<td>: Table data cell.
<th>: Table header cell.
<thead>: Table header group.
<tbody>: Table body group.
<tfoot>: Table footer group.

## Semantic Tags
<header>: Header section.
<footer>: Footer section.
<article>: Article.
<section>: Section.
<nav>: Navigation.
<aside>: Sidebar content.
<article>
<aside>
<details>
<figcaption>
<figure>
<footer>
<header>
<main>
<mark>
<nav>
<section>
<summary>
<time>




### HTML Elements
Beginners often get confused between HTML elements, nested elements, and tags. Let's clarify the difference by understanding each one step-by-step.

What is an HTML Element?
An HTML element is a complete set that consists of a start tag (or opening tag), content, and an end tag (or closing tag).

HTML Element = Start Tag + Content + End Tag

For example:

<h1>This is our first heading</h1>

In this example, <h1> is the start tag, "This is our first heading" is the content, and </h1> is the end tag. Together, they form an HTML element.

What is a Nested HTML Element?
A nested HTML element is an HTML structure where one element is placed inside another element.

The enclosing element is often referred to as the "parent," while the enclosed element is called the "child."

Nested HTML Element = One HTML Element Inside Another HTML Element

For example:

<h1><b>This is our first heading</b></h1>

In this example, the <b> element (child) is nested inside the <h1> element (parent).

What is an Empty HTML Element?
An empty HTML element is one that does not have a closing tag or content. These elements are also known as "void elements" or "self-closing elements."

Empty HTML Element = Tags with No Content

For example:

<br />

This is a break tag, which has no content and no closing tag. It's used to insert a line break within text or other inline elements. The <hr /> tag, used for horizontal rules, is another example of an empty or void element.


### HTML Attributes
HTML attributes are used to define the characteristics of an HTML element. They are placed within the element's opening tag and consist of two parts: the name and the value.

Name: Specifies the property for that element.
Value: Sets the value of that property for the element.
Types of HTML Attributes
There are three main types of HTML attributes:

Core Attributes: These are basic attributes that can be applied to most HTML elements. Examples include id, class, and style.

Internationalization Attributes: These attributes help adapt the document to different languages and regions. Examples include lang and dir.

Generic Attributes: These attributes provide additional information about the element but don't necessarily affect its appearance or behavior. Examples include data-* attributes for storing custom data private to the page or application.

Core attributes are some of the most widely used attributes in HTML. There are four main types:

id
class
title
style
ID Attribute
The ID attribute is used to assign a unique identifier to an HTML element. Each element with an ID has its own unique identity, similar to how each individual has a unique identity. Multiple elements cannot have the same ID.

Example:

<p id="html">This is an HTML tutorial</p>
<p id="python">This is a Python tutorial</p>

In this example, the ID attribute helps to distinguish between two paragraphs by having different values: "html" and "python".

Class Attribute
The class attribute is used to associate an HTML element with a particular class, typically for styling or JavaScript manipulation. Unlike the ID attribute, the class attribute is not unique, and multiple elements can share the same class.

Title Attribute
The title attribute provides additional information about an element and is often displayed as a tooltip when the mouse hovers over it.

Example:

<h4 title="hello, motto">Title attribute</h4>

Output:

Style Attribute
The style attribute allows for inline styling of HTML elements. It is used in conjunction with CSS properties to directly style individual elements within the HTML code.

Case Sensitivity
The HTML standard is flexible about the case of attribute names, allowing them to be written in either uppercase or lowercase, such as "title" or "TITLE." However, for best practices and compatibility with stricter document types like XHTML, the W3C recommends using lowercase attributes.