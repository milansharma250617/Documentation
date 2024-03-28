<h1 align="center">HTML</h1>

# Table of Content

[What is HTML](https://github.com/milansharma250617/Documentation/tree/main#what-is-html-1)
-
[What is an HTML Element?](https://github.com/milansharma250617/Documentation/tree/main#what-is-an-html-element-1)
-
[Web Browsers](https://github.com/milansharma250617/Documentation/tree/main/README.md#web-browsers-1)
-
[HTML Page Structure](https://github.com/milansharma250617/Documentation/blob/main/README.md#html-page-structure-1)
-
[HTML Elements](https://github.com/milansharma250617/Documentation/blob/main/README.md#html-elements-1)
-
[Nested HTML Elements](https://github.com/milansharma250617/Documentation/blob/main/README.md#nested-html-elements-1)
-
[Never Skip the End Tag](https://github.com/milansharma250617/Documentation/tree/main/README.md#never-skip-the-end-tag-1)
-
[Empty HTML Elements](https://github.com/milansharma250617/Documentation/blob/main/README.md#empty-html-elements-1)
-
[HTML Attributes](https://github.com/milansharma250617/Documentation/blob/main/README.md#html-attributes-1)
-
[The href Attributes](https://github.com/milansharma250617/Documentation/blob/main/README.md#the-href-attribute)
-
[The src Attribute](https://github.com/milansharma250617/Documentation/blob/main/README.md#the-src-attribute-1)
-
[The width and height Attributes](https://github.com/milansharma250617/Documentation/tree/main/README.md#the-width-and-height-attributes-1)
-
[The style Attributes](https://github.com/milansharma250617/Documentation/blob/main/README.md#the-style-attribute)
-
[HTML Horizontal Rules](https://github.com/milansharma250617/Documentation/blob/main/README.md#html-horizontal-rules-1)
-
[Background color and Text Alignment](https://github.com/milansharma250617/Documentation/blob/main/README.md#background-color)
-
[HTML Formatting Elements](https://github.com/milansharma250617/Documentation/blob/main/README.md#html-formatting-elements-1)
-
[HTML Tables](https://github.com/milansharma250617/Documentation/tree/main/README.md#html-tables-1)
-
[HTML Description Lists](https://github.com/milansharma250617/Documentation/tree/main/README.md#html-description-lists-1)
-
[HTML Forms](https://github.com/milansharma250617/Documentation/blob/main/README.md#html-forms-1)
-
[Text Fields](https://github.com/milansharma250617/Documentation/blob/main/README.md#text-fields-1)
-
[The Submit Button](https://github.com/milansharma250617/Documentation/tree/main/README.md#the-submit-button-1)
-

# What is HTML?
HTML stands for Hyper Text Markup Language
HTML is the standard markup language for creating Web pages
HTML describes the structure of a Web page
HTML consists of a series of elements
HTML elements tell the browser how to display the content
HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.
### Example
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
         <h1>My name is Milan Sharma</h1>
         <h2>My name is Milan Sharma</h1>
         <h3>My name is Milan Sharma</h1>
         <h4>My name is Milan Sharma</h1>
         <h5>My name is Milan Sharma</h1>
         <h6>My name is Milan Sharma</h1>
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
# Paragraph Tag
### Example
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
    <h1>my name is Milan Sharma</h1> 
    <p>this is a simple paragraph</p>
    </body>
    </html>
   

# Web Browsers
The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.
A browser does not display the HTML tags, but uses them to determine how to display the document:
![Alt Text](https://www.w3schools.com/html/img_chrome.png)
# HTML Page Structure
    Below is a visualisation of an HTML page structure:
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
    <h1>my name is Milan Sharma</h1> 
    <br>
    <p>this is a simple paragraph</p>
    <a href="https://www.google.com">Visit google</a>
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

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>

        <p>This is a paragraph
        <p>This is a paragraph

    </body>
    </html>
# Empty HTML Elements
    HTML elements with no content are called empty elements.
    The <br> tag defines a line break, and is an empty element without a closing tag:
### Example

         
    <!DOCTYPE html>
    <html lang="en">
    <head>
          <meta charset="UTF-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Document</title>
    </head>
    <body>
    <h1>my name is Milan Sharma</h1> 
    <br>
    <p>this is a simple paragraph</p>
    </body>
    </html>

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
## 1. Absolute URL 
- Links to an external image that is hosted on another website. Example: src="https://www.google.com/images/img_boys.jpg".
Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.
## 2. Relative URL
 - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_boys.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_boys.jpg".
Tip: It is almost always best to use relative URLs. They will not break if you change domain.
# The width and height Attributes
    The <img> tag should also contain the width and height attributes, which specify the width and height of the image (in pixels):
### Example       
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>

        <p>This is a paragraph
        <p>This is a paragraph
          <img src="https://media.istockphoto.com/id/1298623104/photo/happy-young-caucasian-boy-in-casual-outfit-with-arms-crossed-isolated-over-white- 
          background.jpg?s=612x612&w=0&k=20&c=9fHNGNfGAIyviDNmBvsYc8tjhSd4sL3b-2I5gd9bMIg=">
          <img src="https://media.istockphoto.com/id/1298623104/photo/happy-young-caucasian-boy-in-casual-outfit-with-arms-crossed-isolated-over-white- 
          background.jpg?s=612x612&w=0&k=20&c=9fHNGNfGAIyviDNmBvsYc8tjhSd4sL3b-2I5gd9bMIg=" width="500" height="600">
    </body>
    </html>

# The style Attribute
The style attribute is used to add styles to an element, such as color, font, size, and more.
### Example
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
        <p>This is a paragraph
        <p>This is a paragraph
            <p style="color:red;">This is a red paragraph.</p>
    </body>
    </html>
         
# HTML Headings
HTML headings are defined with the to tags.
### Example
       <h1>Heading 1</h1>
       <h2>Heading 2</h2>
       <h3>Heading 3</h3>
       <h4>Heading 4</h4>
       <h5>Heading 5</h5>
       <h6>Heading 6</h6>
# HTML Paragraphs
The HTML element defines a paragraph.
### Example
        <p>This is a paragraph.</p>
        <p>This is another paragraph.</p>
# HTML Horizontal Rules
          The <hr> tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.
          The <hr> element is used to separate content (or define a change) in an HTML page:
### Example
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>

        <h1>My name is Milan Sharma</h1>
        <hr>
        <p>This is a simple paragraph</p>
    
    </body>
    </html>
    
      # The HTML <pre> Element
      The HTML <pre> element defines preformatted text.
      The text inside a <pre> element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks:
### Example
    <!DOCTYPE html>
    <html lang="en">
    <head>
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <title>Document</title>
    </head>
    <body>

         <h1>My name is Milan Sharma</h1> 
         <pre>
             My Bonnie lies over the ocean.
             My Bonnie lies over the sea.
             My Bonnie lies over the ocean.
             Oh, bring back my Bonnie to me.
         </pre>
    
    </body>
    </html>
# Background Color
The CSS background-color property defines the background color for an HTML element.
### Example                                                                      
    <!DOCTYPE html>
    <html lang="en">
    <head>
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <title>Document</title>
    </head>
    <body style="background-color:powderblue;">
         <h1>This is a heading</h1>
         <p>This is a paragraph.</p>
    </body>
    </html>
# Text Alignment
    The CSS text-align property defines the horizontal text alignment for an HTML element:
### Example
    <!DOCTYPE html>
    <html lang="en">
    <head>
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <title>Document</title>
    </head>
    <body 
         <h1>This is a heading</h1>
         <p>This is a paragraph.</p>
         <h1 style="text-align:center;">Centered Heading</h1>
         <p style="text-align:center;">Centered paragraph.</p>
    </body>
    </html>


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


# HTML Tables
  HTML tables allow web developers to arrange data into rows and columns.


## HTML Table Tags
         Tag            Description

       <table>         Defines a table
       <th>           Defines a header cell in a table
       <tr>           Defines a row in a table
       <td>           Defines a cell in a table
      <caption>        Defines a table caption
      <colgroup>       Specifies a group of one or more columns in a table for formatting
       <col>           Specifies column properties for each column within a <colgroup> element
      <thead>          Groups the header content in a table
      <tbody>          Groups the body content in a table
      <tfoot>          Groups the footer content in a table
  

### Example
     <!DOCTYPE html>
    <html lang="en">
    <head>
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <title>Document</title>
    </head>
    <body 
    <table>
         <tr>
             <th>Company</th>
             <th>Contact</th>
             <th>Country</th>
         </tr>
         <tr>
             <td>Alfreds Futterkiste</td>
             <td>Maria Anders</td>
             <td>Germany</td>
         </tr>
         <tr>
             <td>Centro comercial Moctezuma</td>
             <td>Francisco Chang</td>
             <td>Mexico</td>
         </tr>
    </table>
    </body>
    </html>


# HTML Description Lists
    HTML also supports description lists.
    A description list is a list of terms, with a description of each term.
    The <dl> tag defines the description list, the <dt> tag defines the term (name), and the <dd> tag describes each term:
### Example
    <!DOCTYPE html>
    <html lang="en">
    <head>
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <title>Document</title>
    </head>
    </head>
    <body 
    <ol>
         <li>Item 1</li>
         <li>Item 2</li>
         <li>Item 3</li>
    </ol>
    <ul>
         <li>Item 1</li>
         <li>Item 2</li>
         <li>Item 3</li>
    </ul>
    </body>
    </html>


## HTML List Tags
   
      Tag                  Description
      <ul>             Defines an unordered list
      <ol>             Defines an ordered list
      <li>             Defines a list item
      <dl>             Defines a description list
      <dt>             Defines a term in a description list
      <dd>             Describes the term in a description list

 
 
# The <span> Element
     The <span> element is an inline container used to mark up a part of a text, or a part of a document.
     The <span> element has no required attributes, but style, class and id are common.
     When used together with CSS, the <span> element can be used to style parts of the text:
### Example
          <p>My mother has <span style="color:blue;font-weight:bold;">blue</span> eyes and my father has <span style="color:darkolivegreen;font-weight:bold;">dark 
          green</span> eyes.</p>
# HTML Forms
An HTML form is used to collect user input. The user input is most often sent to a server for processing.
    
    ## The <form> Element
     The HTML <form> element is used to create an HTML form for user input:
     <form>
     form elements
     .
     </form>
    The <form> element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.
    All the different form elements are covered in this chapter: HTML Form Elements.
### Example
    <!DOCTYPE html>
    <html lang="en">
    <head>
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <title>Document</title>
    </head>
    <body 
    <form action="/submit-form" method="post">
         <label for="name">Name:</label>
         <input type="text" id="name" name="name" required>
         <label for="email">Email:</label>
         <input type="email" id="email" name="email" required>
         <label for="message">Message:</label>
         <textarea id="message" name="message" rows="4" required></textarea>
         <button type="submit">Submit</button>
    </form>
    </body>
    </html>

# The <input> Element
     The HTML <input> element is the most used form element.
     An <input> element can be displayed in many ways, depending on the type attribute.
     Here are some examples:
        Type                             Description
     <input type="text">              Displays a single-line text input field
     <input type="radio">             Displays a radio button (for selecting one of many choices)
     <input type="checkbox">          Displays a checkbox (for selecting zero or more of many choices)
     <input type="submit">            Displays a submit button (for submitting the form)
     <input type="button">            Displays a clickable button
# Text Fields
    The <input type="text"> defines a single-line input field for text input.
### Example
    <!DOCTYPE html>
    <html lang="en">
    <head>
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <title>Document</title>
    </head>
    <body 
    <form>
         <label for="fname">First name:</label><br>
         <input type="text" id="fname" name="fname"><br>
         <label for="lname">Last name:</label><br>
         <input type="text" id="lname" name="lname">
         </form>
    </body>
    </html>

# The <label> Element
     Notice the use of the <label> element in the example above.
     The <label> tag defines a label for many form elements.
     The <label> element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focuses on the input element.
     The <label> element also helps users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks 
     the text within the <label> element, it toggles the radio button/checkbox.
     The for attribute of the <label> tag should be equal to the id attribute of the <input> element to bind them together.


# The Submit Button
     The <input type="submit"> defines a button for submitting the form data to a form-handler.
     The form-handler is typically a file on the server with a script for processing input data.
     The form-handler is specified in the form's action attribute.
### Example
    <!DOCTYPE html>
    <html lang="en">
    <head>
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <title>Document</title>
    </head>
    <body 
         <button type="submit">Submit</button>
    </body>
    </html>

# The Name Attribute for <input>
Notice that each input field must have a name attribute to be submitted.
If the name attribute is omitted, the value of the input field will not be sent at all.
### Example
            <form action="/action_page.php">
            <label for="fname">First name:</label><br>
            <input type="text" id="fname" value="John"><br><br>
            <input type="submit" value="Submit">
            </form>
         

   
   
   
   
  




   





   


   







