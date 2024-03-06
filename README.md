# HTML
# What is HTML?
HTML stands for Hyper Text Markup Language
HTML is the standard markup language for creating Web pages
HTML describes the structure of a Web page
HTML consists of a series of elements
HTML elements tell the browser how to display the content
HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.
### Example
       <idoctype.html>
       <html>
       <head>
       <title> page title </title>
       </head>  
       <body>
       <h1> This is a heading </h1>
       <p1> This is paragraph
       <hr><br> What is your name </p1>

       </body>
       </html>
### Example Explained
The <!DOCTYPE html> declaration defines that this document is an HTML5 document
The <html> element is the root element of an HTML page
The <head> element contains meta information about the HTML page
The <title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
The <body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
The <h1> element defines a large heading
The <p> element defines a paragraph

# What is an HTML Element?
An HTML element is defined by a start tag, some content, and an end tag:
<tagname> Content goes here... </tagname>
The HTML element is everything from the start tag to the end tag:
<h1>My First Heading</h1>
<p>My first paragraph.</p>


# Web Browsers
The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.
A browser does not display the HTML tags, but uses them to determine how to display the document:
![Alt Text](https://www.w3schools.com/html/img_chrome.png)
# HTML Page Structure
Below is a visualisation of an HTML page structure:
        <html>
        <head>
        <title>Page title</title>
        </head>
        <body>
        <h1>This is a heading</h1>
        <p>This is a paragraph.</p>
        <p>This is another paragraph.</p>
        </body>
       </html>

# HTML Elements
The HTML element is everything from the start tag to the end tag:
<tagname>Content goes here...</tagname>
### Examples of some HTML elements:
        <h1>My First Heading</h1>
       <p>My first paragraph.</p>

# Nested HTML Elements
HTML elements can be nested (this means that elements can contain other elements).
All HTML documents consist of nested HTML elements.
The following example contains four HTML elements.

### Example
       <!DOCTYPE html>
       <html>
       <body>


       <h1>My First Heading</h1>
       <p>My first paragraph.</p>


       </body>
       </html>
# Never Skip the End Tag
Some HTML elements will display correctly, even if you forget the end tag:
### Example

        <html>
        <body>

        <p>This is a paragraph
        <p>This is a paragraph

        </body>
        </html>
