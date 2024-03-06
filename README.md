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
# Empty HTML Elements
HTML elements with no content are called empty elements.
The <br> tag defines a line break, and is an empty element without a closing tag:
### Example

         <p>This is a <br> paragraph with a line break.</p>

# HTML Attributes
All HTML elements can have attributes
Attributes provide additional information about elements
Attributes are always specified in the start tag
Attributes usually come in name/value pairs like: name="value"
# The href Attribute
The <a> tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to:
### Example
          <a href="https://www.google.com">Visit google</a>

# The src Attribute
The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:
### Example
         <img src="img_boys.jpg">
There are two ways to specify the URL in the src attribute:
## 1 Absolute URL 
- Links to an external image that is hosted on another website. Example: src="https://www.google.com/images/img_boys.jpg".
Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.
## 2. Relative URL
 - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_boys.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_boys.jpg".
Tip: It is almost always best to use relative URLs. They will not break if you change domain.
# The width and height Attributes
The <img> tag should also contain the width and height attributes, which specify the width and height of the image (in pixels):
### Example       
         <img src="img_boys.jpg" width="500" height="600">
# The style Attribute
The style attribute is used to add styles to an element, such as color, font, size, and more.
### Example
          <p style="color:red;">This is a red paragraph.</p>
# HTML Headings
HTML headings are defined with the <h1> to <h6> tags.
### Example
       <h1>Heading 1</h1>
       <h2>Heading 2</h2>
       <h3>Heading 3</h3>
       <h4>Heading 4</h4>
       <h5>Heading 5</h5>
       <h6>Heading 6</h6>
# HTML Paragraphs
The HTML <p> element defines a paragraph.
### Example
        <p>This is a paragraph.</p>
        <p>This is another paragraph.</p>
# HTML Horizontal Rules
The <hr> tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.
The <hr> element is used to separate content (or define a change) in an HTML page:
### Example
         <h1>This is heading 1</h1>
         <p>This is some text.</p>
         <hr>
         <h2>This is heading 2</h2>
         <p>This is some other text.</p>
         <hr>
# The HTML <pre> Element
The HTML <pre> element defines preformatted text.
The text inside a <pre> element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks:
### Example
          <pre>
           My Bonnie lies over the ocean.
           My Bonnie lies over the sea.
           My Bonnie lies over the ocean.
           Oh, bring back my Bonnie to me.
          </pre>
# Background Color
The CSS background-color property defines the background color for an HTML element.
### Example                                                                      
           <body style="background-color:powderblue;">
           <h1>This is a heading</h1>
           <p>This is a paragraph.</p>
           </body>
# Text Alignment
The CSS text-align property defines the horizontal text alignment for an HTML element:
### Example
           <h1 style="text-align:center;">Centered Heading</h1>
           <p style="text-align:center;">Centered paragraph.</p>




# HTML Formatting Elements
Formatting elements were designed to display special types of text:


           <b> - Bold text
           <strong> - Important text
           <i> - Italic text
           <em> - Emphasized text
           <mark> - Marked text
           <small> - Smaller text
           <del> - Deleted text
           <ins> - Inserted text
           <sub> - Subscript text
           <sup> - Superscript text





