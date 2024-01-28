# Introduction
This is a markdown doc for everything in week one; from Git and Github, to Basics of HTML and CSS, and lastly JS basics.

---
## Basics of HTML
HTML is not a programmming, however it is a markup language used to display web pages on browsers. A crystal understanding of it's syntax is vital for web development.Html files have a .html extension.
One can view HTML as the skeleton of web development, while CSS on its end acts as the skin and Javascript as the brains.

### Course outline
- HTML declarations and boilerplate tags
- Element nesting & Identation
- Semantic Layout elements
- Metadata, Linking documents, scripts and style elements.
- Attributes, ID's and classes
- Video & Image embedding
- Ordered & Bulleted lists
- Tables and Forms

#### Head elements
`<title> </title>` tag is used to describe content that is placed on the browser's tab.

Apart from the title, other head elements are meta tags, used to describe the web page.
`<meta charset= "">` is used to describe the character set used. Character sets may include; ASCII, Unicode, UTF-8, UTF-16, ANSI(Windows 1252) among others.

`<meta name="viewpoint" content="width=device-width", "initial-scale= 1.0">` - used to make responsive web pages

`<meta name="description">` is used to describe the webpage, and most time description keywords end up being used for SEO.

`<link relation="stylesheet" href="index.css">` is used to link the index.html file to a styling sheet, index.css
Also, one could link to an online stylesheet like fontawesome, in this way, one needs to attach the URL instead as the reference.

`<script></script>` tag is used to link the html to an external script, in this case, Javascript.

#### Layout elements
`<div> </div>` element is the most commonly used, for pretty much anything. It takes in some attrbutes; class, id. 

Before, the div element was used to separate content while the class attribute to differentiate one div from another. ID attribute is used only for one particular attribute and not multiple.

To differentiate content on html5, one could use `<header></header>` element, `<footer></footer>` element, `<section></section>` element which also takes the `<main></main>` elements as a child element, `<aside></aside>` element used to describe any other thing apart from the main. Lastly we have `<article></article>` element.

#### Video & Image embedding
Question: How do we embedd audio to a webpage?

The `<img>` tag is used to add images to webpages. It has no closing tag and requires 2 attributes; *src=""* and *alt=""* .

One could use the `<figure>` element to specify any self-contained content; illustrations, code, photos, diagrams, etc. The tag takes a child element of `<figCaption>` that provides a caption for the figure element. Attributes could be added for styling.

To attach a video, the `<video>` element is used, it has no closing tag. It takes src attribute, control, autoplay, muted, loop, preload, width="", among others. Video element can take source element as a nested element and the type attribute could be used to describe the video format.

`<iframe>` element inside a div could be another way to embedd a video. Takes in attributes like: width, height, and src.

#### Navigation Bar & List
`<nav> </nav>` element is used to describe a navbar. This could include child element `<ul> </ul>` or `<ol> </ol>` for bulleted list and numbered ones respectively.
One can change the display of the list and align them horizontally. 

Headings begin from h1 to h6, with h1 being the largest heading.

#### Tables
The most interesting thing on html, imo. I think one could really work around with the skills on tables to create something nice.
The `<table>` element takes a child element table-row, `<tr>` that also takes a child element of table data, `<td>`. `<th>` table header could also be a child element for `<tr>`.

Other table elements include: `<thead></thead>`, `<tbody> </tbody>`, and `<tfoot></tfoot>`
`<colgroup> </colgroup>` is used to specify a group of 1or more columns in a table.

#### Random Hacks
- To create space, create another paragraph with the `<p> </p>` tag rather than using the `<br>` tag several times.
- `<blockquote>` tag allows content to standout while `<q> </q>` is used for short quote.
- `<code>` tag allows the browser to know you have code there.
- What do you think `<mark>` tag is used for?b