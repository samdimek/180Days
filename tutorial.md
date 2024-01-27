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
`<div> </div>` element is the most commonly used, for pretty much anything. It takes in some attrbutes; class, id. ID attribute is used only for one particular attribute and not multiple.